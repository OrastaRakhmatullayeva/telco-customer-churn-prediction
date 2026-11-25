
# Telco Customer Churn Prediction

A machine learning project focused on identifying customers 
at risk of leaving a telecom company.

## Dataset

[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

- 7,043 customers
- 19 input features
- Target: Customer Churn (Yes/No)

## Methodology

- Data cleaning and exploratory data analysis
- One-Hot Encoding and feature scaling
- Stratified train-test split (80/20)
- Scikit-learn preprocessing pipeline
- Class imbalance handling
- Hyperparameter tuning with GridSearchCV

## Models

- Logistic Regression
- Random Forest
- Class-weighted Random Forest
- Tuned Random Forest

## Evaluation

Models are evaluated using Accuracy, Precision, Recall, 
F1-score, and ROC-AUC.

The notebook includes model comparison, confusion matrices, 
ROC curves, and feature importance analysis.

## Business Value

The model helps identify customers at risk of churn 
and supports customer retention strategies.

## Tech Stack

Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## How to Run

Download the dataset, open the notebook in Google Colab,
and run all cells.
