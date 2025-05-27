# Credit_Card_Fraud_Detection
# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. It utilizes a dataset of transactions and builds a classification model to distinguish between legitimate and fraudulent activities.

## 📌 Overview

Credit card fraud is a growing concern in the financial sector. This project demonstrates how machine learning can help in identifying suspicious transactions efficiently by analyzing patterns in transaction data.

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib / Seaborn

## 📂 Dataset

The dataset used is the publicly available [Credit Card Fraud Detection dataset from Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains 284,807 transactions made by European cardholders in September 2013. It includes:

- 492 frauds (0.17% of all transactions)
- Anonymized features (V1 to V28) plus `Time`, `Amount`, and `Class` (target)

## 📊 Project Structure
📈 Model Performance
We used Random Forest and Logistic Regression classifiers. Random Forest gave the best performance with:

Accuracy: ~99.9%

Precision: ~90.2%

Recall: ~86.3%

F1 Score: ~88.2%

✅ Features
Preprocessing and feature scaling

Handling class imbalance with SMOTE

Model training and evaluation

Confusion matrix visualization

📝 Future Work
Integrate deep learning models

Real-time detection with stream processing

Model deployment as a REST API

Alert system integration

📚 References
Scikit-learn Documentation

Kaggle Dataset

imbalanced-learn Documentation
