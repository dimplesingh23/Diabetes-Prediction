# Diabetes-Prediction
Overview
Diabetes is a chronic disease that affects millions of people worldwide, and its early detection is crucial to effective treatment and management. This project leverages machine learning to build a predictive model that identifies individuals at risk of diabetes based on medical and demographic data.

By analyzing key features such as glucose levels, blood pressure, BMI, and age, the project aims to uncover patterns that distinguish diabetic individuals from non-diabetic ones. The model can serve as a diagnostic aid for healthcare professionals, enabling proactive interventions to prevent or mitigate complications associated with diabetes.
Features
Data Preprocessing: Handles missing values, outliers, and scales features to prepare the dataset.
Feature Selection: Identifies the most relevant predictors for diabetes diagnosis.
Model Training: Implements various machine learning models such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
Model Evaluation: Assesses accuracy, precision, recall, F1 score, and ROC-AUC.

Dataset
The project utilizes the Pima Indians Diabetes Database, which includes the following features:
Number of Samples: 768

Features:
Pregnancies: Number of pregnancies.
Glucose: Plasma glucose concentration after a 2-hour oral glucose tolerance test.
BloodPressure: Diastolic blood pressure (mm Hg).
SkinThickness: Triceps skinfold thickness (mm).
Insulin: 2-hour serum insulin (mu U/ml).
BMI: Body Mass Index (weight in kg/(height in m)^2).
DiabetesPedigreeFunction: Diabetes pedigree function (genetic likelihood).
Age: Age of the individual.
Outcome: Target variable (0 = Non-diabetic, 1 = Diabetic).
