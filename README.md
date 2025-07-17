# CreditCardFraudDetection
# Credit Card Fraud Detection

![Fraud Detection](https://img.shields.io/badge/status-active-brightgreen) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📌 Overview

This project focuses on building a machine learning model to **detect fraudulent credit card transactions** using a real-world, anonymized dataset. Due to the highly imbalanced nature of fraud detection (fraudulent transactions are a tiny fraction of total transactions), the project explores preprocessing strategies, model training, evaluation metrics, and handling data imbalance.

## 🗂️ Dataset

- Source: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Features: 30 columns including anonymized PCA features (V1 to V28), `Amount`, `Time`, and a binary `Class` label (1 = fraud, 0 = not fraud)
- Rows: 284,807 transactions

## 🧠 Objective

To identify fraudulent transactions as accurately as possible using:
- Logistic Regression
- Decision Trees
- Random Forests
- XGBoost
- Other ML techniques with metrics like F1-Score, ROC-AUC, Precision-Recall curves

## 🔍 Exploratory Data Analysis

- Checked for missing values, class distribution, outliers
- Visualized class imbalance using bar plots
- Used correlation heatmaps to understand feature importance

## ⚙️ Model Pipeline

1. **Data Preprocessing**
   - Normalization of `Amount` and `Time`
   - Train-test split
   - SMOTE (or other resampling methods) to handle class imbalance

2. **Model Training**
   - Multiple classification models were trained
   - Evaluation with appropriate metrics due to class imbalance

3. **Evaluation Metrics**
   - Confusion Matrix
   - ROC Curve
   - Precision, Recall, F1-Score
   - AUC Score

## 📊 Results

- Final model achieved high recall and precision on fraudulent transactions
- Proper resampling and metric selection helped address the imbalance

