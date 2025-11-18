# HCL_CUSTOMER_CHURN_ESPADA
A simple, end-to-end project that predicts customer churn using a small, imbalanced dataset. The Colab notebook includes all steps—EDA, preprocessing, handling imbalance, training models, and evaluating them with metrics like ROC-AUC. 

This project provides an end-to-end workflow for predicting customer churn using a structured dataset of 1,000 records. The dataset includes demographic, usage, and behavioral attributes such as Age, Gender, MonthlyUsageHours, NumTransactions, SubscriptionType, Complaints, and a Churn flag. The churn distribution is deliberately imbalanced (≈30%), reflecting a realistic business scenario.

All analysis is contained within a single Google Colab notebook, covering exploratory data analysis, preprocessing, imbalance handling, model training, and performance evaluation. Models are assessed using ROC-AUC, precision, recall, and F1-score to ensure balanced measurement beyond accuracy.

HOW TO USE

-Open the Colab notebook.

-Upload the dataset.

-Execute the notebook sequentially to view EDA, modeling steps, and final evaluation.

Key Highlights

Complete churn-prediction pipeline in one notebook

Practical treatment of imbalanced data

Model comparison (Logistic Regression, Random Forest, XGBoost)

Clear and interpretable metric-based evaluation

Future Enhancements

Incorporation of explainability techniques (e.g., SHAP)

Advanced hyperparameter tuning

Optional API-based deployment
