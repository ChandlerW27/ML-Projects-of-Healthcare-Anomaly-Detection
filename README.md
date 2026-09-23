# Healthcare Fraud Detection with Machine Learning 

## Overview

This project uses CMS healthcare claims data to detect possible fraud and unusual billing patterns.

It includes:

- Data cleaning and exploration
- Feature engineering
- Provider-level analysis
- Machine learning model training
- Model comparison

## Dataset from Kaggle

Prepares the data and creates provider-level features, including:

- Number of claims
- Number of patients
- Total reimbursement
- Average reimbursement
- Diagnosis and procedure counts
- Inpatient and outpatient activity

## Three models:

- Logistic Regression
- Random Forest
- XGBoost

## Results

Best model: Logistic Regression

              precision    recall  f1-score   support

   Non-Fraud     0.9849    0.9029    0.9421      1226
       Fraud     0.4803    0.8661    0.6180       127

    accuracy                         0.8995      1353
   macro avg     0.7326    0.8845    0.7801      1353
weighted avg     0.9375    0.8995    0.9117      1353



Logistic Regression performed best overall.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook


## Conclusion

This project shows a simple machine learning workflow for detecting possible healthcare fraud from claims data.
