Telco Customer Churn Project 

This project predicts customer churn using the Telco Customer Churn dataset.

It involves:
Cleaning and preprocessing the data
Label encoding categorical variables
Scaling features
Training a Random Forest classifier
Evaluating the model with accuracy and a confusion matrix
Visualizing the churn distribution and model results

Dataset
The dataset used is: Telco-Customer-Churn.csv
Source: Kaggle – Telco Customer Churn (by IBM)

Steps
Load and inspect the dataset
Convert 'TotalCharges' to numeric and fill missing values
Encode categorical columns using LabelEncoder
Split data into training and test sets
Scale the features
Train a Random Forest model
Predict and evaluate accuracy
Display churn count and confusion matrix plots

Requirements
Libraries used:
pandas, numpy, seaborn, matplotlib, scikit-learn
Install them with pip if not already available.

Output
Model accuracy printed in console
Confusion matrix displayed
Churn count plot shown
