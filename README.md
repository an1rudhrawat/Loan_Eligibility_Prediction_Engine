# CreditWise: Loan Approval Prediction System

A machine learning-based loan approval prediction system that automates credit decision analysis using applicant financial and demographic information. The project compares multiple classification algorithms and applies hyperparameter tuning to identify the most effective model for predicting loan approval outcomes.

---

## Overview

Loan approval is a critical process for financial institutions, requiring careful evaluation of an applicant's financial profile and creditworthiness. This project leverages supervised machine learning techniques to predict whether a loan application is likely to be approved or rejected.

The workflow covers the complete machine learning lifecycle, including data preprocessing, feature engineering, model training, hyperparameter optimization, and performance evaluation.

---

## Objectives

- Predict loan approval status using applicant information.
- Compare the performance of multiple machine learning algorithms.
- Optimize model performance through hyperparameter tuning.
- Evaluate models using industry-standard classification metrics.

---

## Dataset Features

The dataset contains information related to loan applicants, including:

- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Term
- Credit History
- Education
- Self Employment Status
- Marital Status
- Dependents
- Property Area

### Target Variable

- Loan Status (Approved / Rejected)

---

## Machine Learning Workflow

### 1. Data Preprocessing

- Handling missing values using `SimpleImputer`
- Encoding categorical features
- Feature scaling using `StandardScaler`
- Data preparation for model training

### 2. Model Development

The following classification algorithms were implemented and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Random Forest Classifier
- XGBoost Classifier

### 3. Hyperparameter Optimization

Model tuning was performed using:

- GridSearchCV
- Cross Validation
- Recall-Based Model Selection

---

## Evaluation Metrics

Model performance was assessed using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## Key Features

- End-to-end machine learning pipeline
- Automated data preprocessing
- Multiple model comparison
- Hyperparameter tuning with GridSearchCV
- Classification-based loan approval prediction
- Performance-driven model selection

---

## Results

The project successfully compares multiple machine learning algorithms and identifies the best-performing model for loan approval prediction through systematic evaluation and hyperparameter optimization.
