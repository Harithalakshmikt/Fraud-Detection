# Fraud Detection Project

This project focuses on detecting fraudulent transactions using machine learning techniques. Using a real-world transaction dataset, the project involves data preprocessing, feature engineering, and building a classification model with XGBoost.

## Features
- Data cleaning and feature extraction (e.g., time features from transaction timestamps)
- Handling imbalanced classes with class weighting
- One-hot encoding of categorical variables (e.g., CUSTOMER_ID, TERMINAL_ID)
- Training and evaluation of an XGBoost classifier
- Model evaluation using Accuracy, Precision, Recall, F1-score, and ROC AUC metrics
- Visualization of feature importance to interpret the model

## Dataset
The dataset consists of transaction records with features such as transaction time, customer ID, terminal ID, and fraud labels. Due to data privacy and size restrictions, the dataset is not included in this repository. You can replace it with your own transaction data structured similarly.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- xgboost
- matplotlib (optional, for plotting feature importance)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Harithalakshmikt/Fraud-Detection.git
