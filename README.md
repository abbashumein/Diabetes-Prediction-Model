# Diabetes-Prediction-Model

Overview
This project implements and compares two machine learning models (Logistic Regression and Decision Tree) for predicting diabetes outcomes based on various health metrics. The project includes data preprocessing, model training, and comprehensive visualization of results.
Dataset Features

Glucose
Insulin
BMI
Age
Glucose_Insulin_Ratio
Other relevant health metrics
Outcome (Target variable: Diabetic/Non-diabetic)

Technical Implementation
Data Preprocessing

Handling infinite values in Glucose_Insulin_Ratio
Missing value imputation using SimpleImputer
Feature scaling using StandardScaler for Logistic Regression
Train-test splitting for model evaluation

Models Implemented

Logistic Regression

Includes feature scaling
Handles missing values through imputation
Hyperparameter tuning available


Decision Tree

Native handling of missing values
No scaling required
Includes hyperparameter tuning via GridSearchCV



Visualization Components

Feature importance comparison between both models
ROC curves with AUC scores
Confusion matrices
Cross-validation score distributions

Results
The project provides comprehensive comparisons between the two models:

Model accuracy and performance metrics
Feature importance analysis
ROC-AUC scores
Cross-validation results
