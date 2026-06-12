
# Fraud Detection ML System

## Overview
This project builds a machine learning system to detect fraudulent credit card transactions using real-world imbalanced data.

## Problem
Fraud detection requires identifying rare but high-impact events in large datasets.

## Solution
We implemented a full ML pipeline including:
- Data preprocessing
- Feature engineering
- SMOTE for imbalance handling
- Logistic Regression and Random Forest models
- Model evaluation using ROC-AUC and classification metrics

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost, SMOTE, Matplotlib

## Results
- Improved fraud detection using ensemble models
- Handled severe class imbalance using SMOTE
- Evaluated model using ROC-AUC and recall-focused metrics

## Key Insight
In fraud detection, recall is more important than accuracy due to the cost of false negatives.
