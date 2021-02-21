# Diabetes-Prediction-Data-Science-Project

### Diabetes
Diabetes is a chronic (long-lasting) health condition that affects how your body turns food into energy.

Most of the food you eat is broken down into sugar (also called glucose) and released into your bloodstream. When your blood sugar goes up, it signals your pancreas to release insulin. Insulin acts like a key to let the blood sugar into your body’s cells for use as energy.

If you have diabetes, your body either doesn’t make enough insulin or can’t use the insulin it makes as well as it should. When there isn’t enough insulin or cells stop responding to insulin, too much blood sugar stays in your bloodstream. Over time, that can cause serious health problems, such as heart disease, vision loss, and kidney disease.

### Business Problem
My objective is to predict whether the patient has diabetes or not based on various features inclueds Number of times pregnant, Glucose, Blood Pressure, skin Thickness, Insulin, BMI, Family history of diabetes and Age. We will perform all the steps from Data gathering to Model deployment.

### Data 
![image](https://user-images.githubusercontent.com/75037992/108632732-840d4f00-7481-11eb-813e-32046d9ef628.png)

We have 9 columns and 768 records and we not have null records.

### Data Description
Pregnancies:Number of times pregnant.
Glucose:Plasma glucose concentration a 2 hours in an oral glucose tolerance test.
BloodPressure:Diastolic blood pressure (mm Hg).
SkinThickness:Triceps skin fold thickness (mm).
Insulin:2-Hour serum insulin (mu U/ml).
BMI:Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction:Diabetes pedigree function.
Age:Age (years).
Outcome:Class variable (0 or 1) 268 of 768 are 1, the others are 0, 1 have diabetes and 0 not have diabetes.

### Data Explore
### Target Distribution
![image](https://user-images.githubusercontent.com/75037992/108632811-e1a19b80-7481-11eb-9fb6-c65fe3c84892.png)

People have diabetes is 34.90% and 65.10% has not diabetes

### Disturbuition values for each feature
![image](https://user-images.githubusercontent.com/75037992/108633131-a99b5800-7483-11eb-837f-3bc9460bc9f0.png)

### Correlation Between Features
![image](https://user-images.githubusercontent.com/75037992/108633551-dfd9d700-7485-11eb-8218-0567dacc20a3.png)

There is a high correlation between Outcome and Glucose, BMI and Age.

### Machine Learning 
I applied four models 
## Baiseline Model
## Logistic Regression
## SGD Classifier Model
## KNN

## We compare various machine learning algorithms on the basis of accuracy_score and find the best one
