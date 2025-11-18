# HCL_CUSTOMER_CHURN_ESPADA
A simple, end-to-end project that predicts customer churn using a small, imbalanced dataset. The Colab notebook includes all steps—EDA, preprocessing, handling imbalance, training models, and evaluating them with metrics like ROC-AUC. 

This project provides an end-to-end workflow for predicting customer churn using a structured dataset of 1,000 records. The dataset includes demographic, usage, and behavioral attributes such as Age, Gender, Usage Frequency, SubscriptionType, Complaints, and a Churn flag. The churn distribution is deliberately imbalanced (≈30%), reflecting a realistic business scenario.

All analysis is contained within a single Google Colab notebook, covering exploratory data analysis, preprocessing, imbalance handling, model training, and performance evaluation. Models are assessed using ROC-AUC, precision, recall, and F1-score to ensure balanced measurement beyond accuracy.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
DATASET

The dataset includes 7043 customers with features like Age, Gender, Usage Frequency, SubscriptionType, Complaints, and a Churn label.
Churn is intentionally imbalanced (~30%).
----------------------------------------------------------------------------------------------------------------------------------------------------------------
NOTEBOOK

EDA

Imbalance handling

Logistic Regression / Random Forest / XGBoost

ROC-AUC, Precision, Recall, F1-score

Final model comparison
----------------------------------------------------------------------------------------------------------------------------------------------------------------
EXPLORATORY DATA ANALYSIS (EDA):

EDA includes:

Missing-values analysis

Class distribution

Statistical summary

Distributions of numeric variables

Correlation matrix

Churn vs. key features analysis

Plots:

Histograms, boxplots

Bar plots for categorical features

Heatmap

Churn breakdown per feature and Data Cleaning & Preprocessing

Steps include:

Handling missing values

Outlier treatment (Winsorization or IQR capping)

One-hot encoding for categorical features

Scaling numeric features (StandardScaler)

Train/test split (stratified)
----------------------------------------------------------------------------------------------------------------------------------------------------------------
FEATURE ENGINEERING

One-hot encoding of SubscriptionType

Binary encoding Gender

Derived feature: AvgUsagePerTransaction

HANDLING IMBALANCE

Since churn ≈ 30%, the dataset is imbalanced.

Techniques used:

Class weights (class_weight='balanced')

Random Oversampling / Undersampling

SMOTE(Synthetic Minority Oversampling)


----------------------------------------------------------------------------------------------------------------------------------------------------------------
AI MODELS

Logistic Regression

Random Forest

XGBoost


----------------------------------------------------------------------------------------------------------------------------------------------------------------
Criteria:

ROC-AUC

Precision, Recall, F1-score

PR-AUC

Confusion matrix

----------------------------------------------------------------------------------------------------------------------------------------------------------------
HOW TO USE

-Open the Colab notebook.

-Upload the dataset.

-Execute the notebook sequentially to view the EDA and the performance metrics 



----------------------------------------------------------------------------------------------------------------------------------------------------------------
KEY HIGHLIGHTS

-Complete churn-prediction pipeline in one notebook

-Practical treatment of imbalanced data

-Model comparison (Logistic Regression, Random Forest, XGBoost)

-Clear and interpretable metric-based evaluation
![WhatsApp Image 2025-11-18 at 14 22 20_5e373523](https://github.com/user-attachments/assets/19838bd7-e123-4d7d-90c6-9fd302631284)
<img width="775" height="686" alt="image" src="https://github.com/user-attachments/assets/9ab919d9-0677-482d-93be-29a0eb70caed" />

<img width="701" height="556" alt="image" src="https://github.com/user-attachments/assets/0456eb19-9cbb-4269-a380-f6dba1bb8fbc" />
<img width="388" height="325" alt="image" src="https://github.com/user-attachments/assets/27f4d297-8274-422d-85a8-82e62730f945" />


