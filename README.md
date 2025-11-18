HCL_CUSTOMER_CHURN_ESPADA

A simple, end-to-end customer churn prediction project built using an imbalanced dataset. The entire workflow—EDA, preprocessing, imbalance handling, model training, and evaluation—is implemented in one Google Colab notebook.

This project uses ~7,000 customer records with demographic, usage, and behavioral features such as Age, Gender, Usage Frequency, SubscriptionType, Complaints, and Churn. The churn rate is intentionally imbalanced (~30%) to reflect real business scenarios.

Dataset

~7043 customer entries

Features: Age, Gender, Usage Frequency, SubscriptionType, Complaints

Target: Churn

Churn imbalance: ~30%

Notebook Contents

Exploratory Data Analysis (EDA)

Handling class imbalance

Model training: Logistic Regression, Random Forest, XGBoost

Evaluation using ROC-AUC, Precision, Recall, F1-score, PR-AUC

Final model comparison

Exploratory Data Analysis (EDA)
Includes:

Missing value analysis

Class distribution

Statistical summary

Numeric feature distributions

Categorical feature breakdown

Correlation matrix

Churn-wise feature comparison

Correlation Matrix

Visualizations:

Histograms

Boxplots

Bar charts

Heatmap

Data Cleaning & Preprocessing

Handling missing values

Outlier treatment (IQR/Winsorization)

One-hot encoding for categorical variables

Binary encoding for Gender

Scaling numerical features using StandardScaler

Stratified train/test split

Feature Engineering

One-hot encoded SubscriptionType

Binary Gender encoding

Derived feature: AvgUsagePerTransaction

Handling Imbalance

Since churn is ~30%, the following techniques were used:

class_weight='balanced'

Random Oversampling

Random Undersampling

SMOTE

Models Used

Logistic Regression

Random Forest

XGBoost

Evaluation Metrics

ROC-AUC

Precision, Recall, F1-score

PR-AUC

Confusion Matrix

ROC Curve Comparison

Confusion Matrix (XGBoost)

How to Use

Open the Colab notebook.

Upload the dataset.

Run all cells step-by-step.

Review EDA, preprocessing outputs, ROC curves, and model performance.

Key Highlights

Complete churn prediction pipeline in one notebook

Practical handling of imbalanced data

Comparison of Logistic Regression, Random Forest, XGBoost

Clear, interpretable evaluation metrics
