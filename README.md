# Credit-Card-Fraud-Detection
In the banking industry, detecting credit card fraud using machine learning is not just a trend — it’s a necessity. This project demonstrates how machine learning can be used to identify fraudulent transactions from a large pool of credit card data, helping banks implement proactive fraud prevention strategies.

# Overview
Credit card fraud is a growing concern in the banking industry. In this project, I built a machine learning model that detects fraudulent transactions using historical data.
The main goal is to help banks and financial institutions reduce manual reviews, chargebacks, and financial losses through proactive fraud detection.

# Project Objectives

Identify fraudulent transactions from a large and highly imbalanced dataset.
Compare multiple ML models to find the most effective fraud detection approach.
Perform a cost-benefit analysis to estimate the business impact.
Suggest strategies to minimize fraud risk and improve detection accuracy.

# Repository Structure
# File	Description
fraud_detection.ipynb: Main Jupyter Notebook containing data preprocessing, EDA, model training, and evaluation.
Cost^Benefit^Analysis.xlsx:	Excel file showing the cost-benefit analysis for different fraud scenarios.
CC_Fraud_Detection.ppt:	PowerPoint presentation summarizing the project, results, and recommendations.

# Dataset Details
The dataset is a simulated Kaggle dataset consisting of approximately 1.85 million transactions between January 2019 and December 2020.
Fraudulent transactions: 9,651 (~0.52%)
Legitimate transactions: 1,842,743
Target variable: is_fraud (1 = Fraud, 0 = Non-fraud)
Feature example: amt (transaction amount)
Since the dataset is highly imbalanced, I used techniques like SMOTE and undersampling to balance it before model training.

# Steps Followed
Data cleaning and preprocessing
Exploratory data analysis (EDA)
Feature engineering
Handling class imbalance (SMOTE / undersampling)
Model building – Logistic Regression, Random Forest, XGBoost
Model evaluation – precision, recall, F1-score, ROC-AUC
Cost-benefit analysis
Recommendations for fraud mitigation

# Tools & Technologies
Python, Google Colab
Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, imbalanced-learn
Excel (for cost-benefit analysis)
PowerPoint (for presentation)

# Results
Built a reliable fraud detection pipeline capable of identifying suspicious transactions effectively.
Achieved strong recall scores on the fraud class after handling data imbalance.
Cost-benefit analysis shows potential savings for financial institutions by integrating ML-based fraud detection.
