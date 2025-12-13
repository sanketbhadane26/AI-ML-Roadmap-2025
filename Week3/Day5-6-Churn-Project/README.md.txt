# Churn Prediction Project (Week 3)

This project focuses on predicting customer churn using a real-world telecom dataset.
It combines data preparation, feature engineering, imbalance handling, and model building.

## Dataset
- Telco Customer Churn
- Target variable: Churn (0 = No, 1 = Yes)

---

## Day 5 — Data Preparation & EDA
- Loaded and inspected dataset
- Cleaned missing and incorrect values
- Converted target variable to binary
- Identified numerical and categorical features
- Performed EDA on churn distribution
- Analyzed churn vs numerical features
- Analyzed churn vs categorical features
- Created new features (AvgMonthlySpend, IsSenior)
- Designed preprocessing and modeling strategy

---

## Day 6 — Modeling & Evaluation
- Built preprocessing pipelines using ColumnTransformer
- Applied SMOTE to handle class imbalance
- Trained models:
  - Logistic Regression
  - Random Forest
- Evaluated models using:
  - Precision, Recall, F1-score
  - ROC-AUC
- Compared model performance
- Selected best model based on recall and AUC

---

## Key Learnings
- Accuracy is misleading for imbalanced datasets
- SMOTE improves recall for minority class
- Pipelines prevent data leakage
- ColumnTransformer simplifies preprocessing
- Evaluation metrics must match business goals
