# Diabetes Prediction Data Science Project

## Author: Aljowhara Alblaihed 


### Diabetes
Diabetes is a chronic (long-lasting) health condition that affects how your body turns food into energy.

Most of the food you eat is broken down into sugar (also called glucose) and released into your bloodstream. When your blood sugar goes up, it signals your pancreas to release insulin. Insulin acts like a key to let the blood sugar into your body’s cells for use as energy.

If you have diabetes, your body either doesn’t make enough insulin or can’t use the insulin it makes as well as it should. When there isn’t enough insulin or cells stop responding to insulin, too much blood sugar stays in your bloodstream. Over time, that can cause serious health problems, such as heart disease, vision loss, and kidney disease.

### Business Problem
My objective is to predict whether the patient has diabetes or not based on various features inclueds Number of times pregnant, Glucose, Blood Pressure, skin Thickness, Insulin, BMI, Family history of diabetes and Age. 

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
### Baiseline Model
A baseline is the result of a basic model. You generally create a baseline and then try to make more complex solutions in order to get a better result. If you achieve a better score than the baseline, it is good.
#### Accuracy 65.6 %Score, That means our diabetes classifier is doing a great job of identifying if person have diabetes or not.

### Logistic Regression Model
Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary). the logistic regression is a predictive analysis.  Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more independent variables.
#### Accuracy 75.9 %Score, That means our diabetes classifier is doing a great job of identifying if person have diabetes or not.

### Stochastic Gradient Descent (SGD) Classifier Model
Stochastic Gradient Descent (SGD) is an optimization algorithm used to find the values of parameters (coefficients) of a function that minimizes a cost function (objective function) and popular algorithm for training a wide range of models in Machine Learning.
#### Accuracy 75 %Score, That means our diabetes classifier is doing a great job of identifying if person have diabetes or not.

### K-Nearest Neighbors (KNN) Model
Classification is done by a majority vote to its neighbors. The data is assigned to the class which has the nearest neighbors. As you increase the number of nearest neighbors, the value of k, accuracy might increase.
#### Accuracy 81% %Score, That means our diabetes classifier is doing a great job of identifying if person have diabetes or not, after Optimize accuracy 84.4% that's best model.

### We compare various machine learning algorithms on the basis of accuracy_score (Baseline Mode) and find the best one before optimize model
![image](https://user-images.githubusercontent.com/75037992/108989598-d1b6d100-76a6-11eb-9a35-85a9c550baed.png)

![image](https://user-images.githubusercontent.com/75037992/109069574-74506d80-7702-11eb-8b2e-36ea8421de87.png)

Achived the best result in k-nearest neighbors Model with accuracy 81% score and ROC AUC 82%.

### We compare various machine learning algorithms on the basis of accuracy_score (Baseline Mode) and find the best one after optimize model
![image](https://user-images.githubusercontent.com/75037992/108988626-bdbe9f80-76a5-11eb-9310-f77ca8929002.png)

![image](https://user-images.githubusercontent.com/75037992/108989936-3a9e4900-76a7-11eb-8c35-a6399d812232.png)

Achived the best result in k-nearest neighbors Model with accuracy 84% score and ROC AUC 90%.




