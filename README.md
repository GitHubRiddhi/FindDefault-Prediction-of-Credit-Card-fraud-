# FindDefault: Prediction of Credit Card Fraud

Welcome to the GitHub repository for Prediction of Credit Card Fraud. This project aims to build a machine learning model that detects fraudulent credit card transactions. With the growing risk of credit card fraud, this solution aids financial institutions in enhancing transaction security.

## Table of Contents

 1. Project Overview
 2. Dataset
 3. Project Workflow
 4. Key Results
 5. Installation and Usage
 6. Technologies Used
 7. Acknowledgments

## Project Overview
Credit card fraud involves unauthorized transactions leading to financial losses. This project uses a dataset of European cardholders' transactions from September 2013. It is highly imbalanced, with fraud cases constituting only 0.172% of transactions. The focus is to preprocess the data, address imbalance, and build a classification model using Logistic Regression.

### Objectives:

- Perform Exploratory Data Analysis (EDA).
- Address data imbalance using sampling techniques.
- Train a Logistic Regression Model and evaluate its performance.
- Assess the model using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

### Dataset
- Source: European cardholders' credit card transactions (September 2013).
- Size: 284,807 transactions (492 fraud cases).
- Imbalance: 0.172% fraudulent transactions.

### Project Workflow
#### 1. Exploratory Data Analysis (EDA)
- Tasks:
Analyze missing values, outliers, and data types.
Check class distribution (fraudulent vs. non-fraudulent).
- Key Findings:
Highly imbalanced dataset.
#### 2. Data Preparation
- Balanced the dataset using undersampling of legitimate transactions.
#### 3. Feature Engineering and Selection
- Selected relevant features for better model performance.
#### 4. Model Building and Evaluation
- Model: Logistic Regression.
- Metrics: Accuracy, confusion matrix, precision, recall, F1-score, ROC-AUC.
#### 5. Model Evaluation
- Achieved a ROC-AUC score of 0.92, indicating strong performance.
### Key Results
- Accuracy: High on both training and test datasets.
- ROC-AUC: 0.92 (indicative of robust classification).
- Insights: Balanced datasets and model tuning significantly improved performance.



## Technologies Used
- Programming Language: Python
- Libraries: Data Handling: numpy, pandas
- Visualization: matplotlib, seaborn
- Machine Learning: scikit-learn
## Acknowledgments
This project was built as part of a credit card fraud detection case study. Special thanks to the dataset provider and the frameworks used to develop this model.

### Riddhi Sharma
#### Data Scientist


