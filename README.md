## Loan-Approval-Predictor
A machine learning project that predicts whether a loan application wil be approved based on applicant details.

## Project Goal
- To build a Machine Learning model which helps in predicting loan approval status.

## Project Overview
- Language used: Python
- Required Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn.
- Environment used: Google Colab.

## Dataset
- Dataset features include applicant income, education, marital status, loan amount, dti ratio, etc..

## Model Overview 
1) Load Dataset: "/2) loan approval data.csv".
2) Perform Exploratory Data Analysis: Data Preprocessing, Understanding features and their relation(Histogram, Box plots, Correlation Matrix).
3) Feature Selection: Drop the non-predictive "Applicant_ID" column from the dataset.
4) Encoding: Used Label encoder and One Hot encoder.
5) Data Splitting: Splitting entire dataset into Training and Testing for 80% and 20% respectively.
6) Scaling: Scaling using Standard Scaler.
7) Model Selection: Used 3 different model and compared their performance a) Logistic Regression, b) Naive Bayes, c) KNN Classifier
8) Model training: Train each model on the dataset.
9) Evaluation: Use Evaluation metrics for these classification models.
10) Hyperparameter Tuning: Adjusted model parameters to improve performance.

## Results
a) Logistic Regression: 86.5%, 
b) Naive Bayes: 86.5%, 
c) KNN Classifier: 79%.
- Best performing models: Logistic Regression and Naive Bayes.
