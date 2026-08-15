# Explainable Loan Approval Prediction Using Machine Learning

## Project Overview

This project develops a machine learning framework for predicting loan approval decisions while improving model transparency through Explainable AI (XAI).

The study compares different classification algorithms and investigates the factors that influence loan approval predictions.

## Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

The models are optimised using hyperparameter tuning and five-fold stratified cross-validation.

## Explainable AI

Two XAI techniques are used:

- **SHAP** – identifies important features and explains their contribution to predictions.
- **LIME** – provides explanations for individual loan decisions.

The consistency between SHAP and LIME explanations is also evaluated.

## Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- Cross-validation

Statistical comparison and fairness analysis are also included.

## Key Findings

The Decision Tree achieved the highest numerical performance on the evaluated dataset. CIBIL score, loan term and loan-to-income ratio were identified as important factors influencing predictions. SHAP and LIME showed strong agreement in their feature rankings.

## Technologies

**Python | Scikit-learn | XGBoost | SHAP | LIME | Pandas | NumPy | Google Colab**

## Dataset

The project uses a publicly available Loan Approval Prediction dataset containing 4,269 loan applications and 14 input features.

