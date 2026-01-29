# Random-Forest-Credit-Card-Fraud-Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning models while handling severe class imbalance.

## Dataset
- File: `creditcard.csv`
- Target column: `Class` (0 = Non-Fraud, 1 = Fraud)

## Steps Performed
- Loaded dataset and analyzed fraud vs non-fraud class imbalance
- Separated features and target variable
- Applied stratified train-test split to preserve fraud ratio
- Trained a baseline Logistic Regression model
- Trained a Random Forest model for improved performance
- Evaluated models using Precision, Recall, and F1-score
- Compared Random Forest performance against Logistic Regression
- Visualized feature importance to identify key fraud indicators
- Saved the best-performing model using joblib

## Conclusion
Random Forest outperforms the baseline model on fraud-relevant metrics, making it more suitable for detecting rare fraudulent transactions.

