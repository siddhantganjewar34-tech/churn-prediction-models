# churn-prediction-models
Predicting customer churn using Logistic Regression, Random Forest, and XGBoost. Optimized for high Recall (0.88)


📄 Task 04: Churn-Prediction-Modeling
Churn-Prediction-Modeling

An end-to-end classification pipeline comparing Logistic Regression, Random Forest, and XGBoost. Optimized specifically for high recall to identify at-risk customers before they leave.

📉 Customer Churn Prediction

Internship Project — IncodeVision

📝 Overview
The goal was to build a model that doesn't just predict "No Churn" for everyone to get a high accuracy score. I focused on building a system that actually catches the 23% of customers who are planning to leave, providing a tool for targeted retention.

📊 Methodology

Data Splitting: 80/20 Stratified split to maintain the 77/23 churn ratio in both sets.

Model Selection: Evaluated a baseline (Logistic Regression) against ensemble methods (Random Forest and XGBoost).

Optimization: Used scale_pos_weight and class_weight to address class imbalance—ensuring the model prioritizes the minority "Churn" class.

Evaluation: Optimized for AUC-ROC and Recall rather than raw accuracy.

🛠️ Tech Stack

Language: Python

Libraries: Scikit-Learn, XGBoost, Joblib

Models: Logistic Regression, Random Forest, XGBoost

📈 Key Results

Winner: XGBoost

AUC-ROC: 91.63%

Churn Recall: 88% (Catches nearly 9 out of 10 at-risk customers)

Google Drive link - https://drive.google.com/drive/folders/1WWVQtFnF6FLxo5rCMRsQKqCYuL6hKL4L?usp=sharing
Google Colab link - https://colab.research.google.com/drive/1qmsUWPFQFHRUulI-XIOLN2aku_87EwLK?usp=sharing
