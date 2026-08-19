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

## Three models:

- Logistic Regression
- Random Forest
- XGBoost

## Results

| Model | PR-AUC | ROC-AUC |
|---|---:|---:|
| Logistic Regression | **0.759** | **0.961** |
| XGBoost | 0.751 | 0.960 |
| Random Forest | 0.737 | 0.959 |

- PR-AUC: How well the model finds fraud while avoiding too many false alarms.
- ROC-AUC: How well the model separates fraud cases from normal cases overall.

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
