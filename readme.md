# Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques.

The dataset is highly imbalanced because fraudulent transactions are much fewer than legitimate transactions. To handle this problem, SMOTE (Synthetic Minority Over-sampling Technique) is used to balance the training data.

Two machine learning models are trained and compared:

- Logistic Regression
- Random Forest

The models are evaluated using Precision, Recall, F1-Score, and ROC-AUC.

---

## 🎯 Objective

The main objectives of this project are:

- Understand the credit card transaction dataset.
- Identify the class imbalance problem.
- Split the data into training and testing sets.
- Use SMOTE to handle imbalanced classes.
- Build a Logistic Regression model.
- Build a Random Forest model.
- Use GridSearchCV for hyperparameter tuning.
- Compare both models using different evaluation metrics.
- Select the better-performing model for fraud detection.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook / Google Colab

---


├── fraud_detection.ipynb
├── creditcard.csv
└── README.md
