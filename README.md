# Predicting Diabetes

# Problem Statement:
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

Diabetes is one of the most dangerous metabolic diseases in today's world. Diabetes is a chronic health issue. Approximately 400 million people worldwide are living with diabetes.
The objective of this project is to analytically predict whether a patient has diabetes, based on certain biological measurements included in the dataset.

# Data Source
We acquired our dataset from Kaggle. This dataset is from the National Institute of Diabetes and Digestive and Kidney Diseases
It’s a research study done by taking measures of various biological characteristics of women from a common community
Consist of 9 variables
![image](https://user-images.githubusercontent.com/92898544/146424874-89a6bb25-9c04-45e2-a832-841185c5b101.png)

Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skin fold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index (weight in kg/(height in m)^2)

DiabetesPedigreeFunction: Diabetes pedigree function

Age: Age (years)

Outcome(Target variable): Class variable (0 or 1) 268 of 768 are 1, the others are 0. 1 represents woman is diabetic, 0 represents no diabetes

# Data Preperation
We performed data cleaning and pre-processing. Also checked for missing values and necessary data type conversions if needed.

# Data Modelling
We applied two data model on outcome variable and other predictors. We compared the results we got with evaluation metrices and got the best performing model.
# Transformation
Created label from target variable
Applied vector assembler to transform variables into features
Applied Logistic Regression, Random forest, Naïve Bayes and gradient boost classifier

# Estimation
Created parameter grid to get best performing model
Applied pipeline to cross validator with two folds

# Evaluation

Applied predictions obtained from trained model to get accuracy, roc
Created confusion matrix to study the accuracy, precision and recall
From evaluation got best and worst performing model

# Results

Random forest classifier is the best performing model with 74.4% accuracy
![image](https://user-images.githubusercontent.com/92898544/146425369-5b1a6ee4-a026-4a0a-bff6-a895b5a8d1b8.png)


# Conclusion
Glucose, BMI and Family History are important factors for predicting diabetes

Blood Pressure and Insulin play moderate role
![image](https://user-images.githubusercontent.com/92898544/146425416-fbd0ceff-87c4-4ca2-bebc-78fa3b82b634.png)


