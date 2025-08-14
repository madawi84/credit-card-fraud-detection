# credit-card-fraud-detection
A logistic regression-based project for detecting fraudulent credit card transactions with evaluation on recall and accuracy.
# 💳 Credit Card Fraud Detection using Logistic Regression

This project applies machine learning to detect fraudulent transactions in credit card data. A logistic regression model was trained and evaluated using real-world transaction features, optimised for high recall on the fraud class.

## 📘 Dataset Overview

- **Transaction Count**: 56,746 non-fraud, 90 fraud cases
- **Features**: Time, Amount, and anonymised V1–V28
- **Imbalance Handling**: Focus on recall and false negatives

## 🔍 Evaluation Summary

| Metric                  | Value     |
|-------------------------|-----------|
| True Negatives (TN)     | 56,647    |
| False Positives (FP)    | 9         |
| False Negatives (FN)    | 27        |
| True Positives (TP)     | 63        |
| **Recall (Fraud Class)**| 0.70      |

> ✅ The model performed with near-perfect accuracy on non-fraud detection and achieved a **70% recall rate** on fraudulent cases, balancing sensitivity and precision.

## 🧠 ML Model

- Logistic Regression (`class_weight='balanced'`)
- Evaluated using precision, recall, and confusion matrix
- Trained/tested with a 75/25 split

## 📂 Project Structure
credit-card-fraud-detection/  
│  
├── credit_card_fraud_detection.ipynb  
├── requirements.txt  
└── README.md  

## 🛠️ Libraries

- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn

## 📄 Academic Context

- Created for course: **M10CT - Applied Data Science**
- Saudi Electronic University, 2025

## 👩‍💻 Author

Madawi Alsoyohi  
[LinkedIn](https://www.linkedin.com/in/madawi-alsoyohi-7134951a6) | [GitHub](https://github.com/madawi84)

