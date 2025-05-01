# TASK 5: CREDIT_CARD_FRAUD DETECTION
## Overview
The aim of this task is to identify fraudulent credit card transactions using machine learning techniques. By analyzing transaction patterns and addressing data imbalance, the project builds a classification model to distinguish between normal and fraudulent activities effectively.

## Project Details
* Data Components:
  - Transaction Features: Amount, time, and anonymized features representing transaction characteristics.
  - Target Variable: Class, where 0 represents normal transactions and 1 represents fraud.
* Approach:
  - Addressed data imbalance by undersampling normal transactions to balance with fraudulent cases.
  - Created balanced datasets for training and testing the model.
  - Built and trained a Logistic Regression model to classify transactions.
* Model Training:
  - Splitting data: 80% for training, 20% for testing, with stratified sampling to maintain class balance.
  - Model evaluation through training and testing accuracy scores.
    
## Key Features
* Balancing Class Distribution:
  - Undersampled normal transactions to match the number of fraud cases (492 each) for balanced training.
* Logistic Regression Model:
  - Simple yet effective approach for binary classification.
  - Achieved ~93.9% training accuracy and ~91.87% testing accuracy.
* Evaluation Metrics:
  - Accuracy scores used to measure model performance.
  - Highlights the effectiveness of Logistic Regression in identifying fraudulent transactions.
* Potential for Improvement:
  - Explored advanced techniques like Random Forest or XGBoost for enhanced prediction accuracy.
  - Suggested integration of SMOTE (Synthetic Minority Oversampling Technique) to handle imbalance more robustly.

### This module demonstrates a real-time fraud detection framework with promising accuracy.
