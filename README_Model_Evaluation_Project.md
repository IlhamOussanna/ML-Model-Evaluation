
# ML Model Evaluation: Financial Risk & Marketing Predictions

This project compares the performance of five supervised machine learning models—**Logistic Regression**, **Decision Tree**, **Random Forest**, **XGBoost**, and **K-Nearest Neighbors (KNN)**—on two binary classification problems:

- **Default Prediction**: Using the "Default of Credit Card Clients" dataset to predict whether a customer will default on their credit card payment.
- **Marketing Subscription**: Using the "Bank Marketing" dataset to predict whether a client will subscribe to a term deposit.

## Goals

- Evaluate model performance using metrics beyond accuracy.
- Understand model strengths in imbalanced data situations.
- Present results using tables, confusion matrices, ROC-AUC, and PR curves.

## Tools & Libraries

- Python
- scikit-learn, XGBoost
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Files Included

| File Name                                   | Description                                         |
|--------------------------------------------|-----------------------------------------------------|
| `ML_Model_Evaluation_Report.pdf`           | Final report summarizing methodology and findings   |

## Key Findings

- **XGBoost** and **Random Forest** outperformed others in Recall and F1-Score for the minority class in both datasets.
- ROC-AUC and Precision-Recall curves showed ensemble models are better suited for imbalanced classification.
- Logistic Regression remained a strong and interpretable baseline.

## Datasets

- [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- [Default of Credit Card Clients](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

## Future Enhancements

- Hyperparameter tuning with GridSearchCV
- Apply SMOTE to oversample minority class
- Build an interactive dashboard to visualise model outputs


