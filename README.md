# Bank-Customer-Churn-Prediction
A customer churn prediction model using various models to identify bank customers at risk of leaving. 

## Project Description
Retaining customers is one of the most critical challenges in the modern banking sector. It is far more cost-effective to retain existing customers than to acquire new ones. This project focuses on analyzing historical customer data from a retail bank to predict **customer churn** (whether a customer will close their account and leave the bank) and uncover the underlying drivers of churn.

Using a dataset of 10,000 customers containing demographic metrics (age, gender, location) and financial profiles (credit score, balance, tenure, product ownership, activity status), we design, train, and compare several predictive models to flag at-risk customers.

## Objectives
1. **Data Preprocessing & Cleansing**: Handle categorical variables using One-Hot Encoding and scale numerical features using MinMax Scaling.
2. **Model Evaluation & Comparison**: Train and benchmark four distinct modeling paradigms:
   * **Linear Baseline**: Logistic Regression
   * **Ensemble Tree Classifiers**: Random Forest & XGBoost
   * **Deep Learning**: Sequential Artificial Neural Network (ANN) in Keras
3. **Class Imbalance Resolution**: Address the typical dataset imbalance (non-churners outnumbering churners 4-to-1) using **SMOTE** (Synthetic Minority Over-sampling Technique) to prioritize model **Recall** over simple Accuracy.
4. **Feature Importance & Strategy**: Extract model features to determine what factors (e.g., number of products, age, activity) drive customer exits, allowing the bank to design proactive retention campaigns.
