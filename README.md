# ❤️ Heart Disease Classification

## Overview
This project compares Decision Tree and Random Forest classifiers on the Heart Disease dataset. It includes model training, evaluation, visualization, and interpretation.

## Dataset
- Source: UCI Heart Disease Dataset
- Target: Presence of heart disease (binary)

## Workflow
1. Data preprocessing and train-test split
2. Train Decision Tree and visualize structure
3. Control overfitting via pruning
4. Train Random Forest and compare accuracy
5. Interpret feature importances
6. Evaluate with cross-validation and ROC curves
7. Hyperparameter tuning with GridSearchCV

## Results
| Model           | Train Acc | Test Acc | CV Acc | AUC |
|----------------|-----------|----------|--------|-----|
| Decision Tree  | 1.00      | 0.99     | 0.83   | 0.80 |
| Random Forest  | 1.00      | 0.99     | 1.00   | 1.00 |

## Feature Importances
- `thal`, `cp`, `ca`, `oldpeak` were most predictive.

## Tools
- Python, pandas, scikit-learn, matplotlib, seaborn
