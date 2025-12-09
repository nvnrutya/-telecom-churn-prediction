📊 Telecom Customer Churn Prediction
📌 Project Overview

This project focuses on predicting customer churn for a telecom company using machine learning techniques. Customer churn is a critical challenge in the telecom industry, as losing customers directly impacts revenue and growth. By analyzing historical customer data, this project aims to identify customers who are likely to churn so that proactive retention strategies can be applied.

🎯 Objective

To build a robust and reliable classification model that predicts whether a customer will churn based on historical data. Special attention is given to handling class imbalance issues commonly present in churn datasets.

🧩 Problem Statement

Customer churn is a major issue in the telecom sector. Identifying customers who are at high risk of leaving enables companies to take preventive actions such as targeted offers, improved customer support, or personalized plans. This project applies machine learning models to solve this problem efficiently.

🔄 Workflow
Data Collection

Historical telecom customer data in CSV format.

Exploratory Data Analysis (EDA)

Univariate analysis

Bivariate analysis

Distribution of churn vs non-churn

Correlation analysis

Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Handling class imbalance using SMOTE / undersampling

Modeling

Logistic Regression

Random Forest

XGBoost

Evaluation Metrics:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Model Evaluation

Confusion Matrix

Classification Report

ROC Curve

Feature Importance

Model Export

Best-performing model saved using Pickle (.pkl)

📂 Dataset Overview

Typical columns include:

Customer ID

Tenure

Monthly Charges

Contract Type

Internet Service

Payment Method

Total Charges

Churn (Target Variable)

🛠 Tech Stack

Python

Pandas, NumPy

Scikit-learn

XGBoost

Imbalanced-learn (SMOTE)

Matplotlib, Seaborn

Jupyter Notebook

Streamlit

Pickle

📈 Results

Best Performing Model: XGBoost

Accuracy: 91%

ROC-AUC: 0.86

Class Imbalance Handling: SMOTE / Undersampling

🚀 Installation & Usage
git clone https://github.com/your-username/telecom-churn-prediction.git
cd telecom-churn-prediction
pip install -r requirements.txt
streamlit run app.py

After running the application:

Upload the input.csv file from the Data/ folder

View churn prediction results in the Streamlit app

🤝 Acknowledgement

This project was completed with reference to and inspiration from an open-source project by Vignesh Bhat N. The work was carried out for learning and academic purposes, following proper licensing and attribution.
