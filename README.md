# Bank-Marketing-Prediction-Using-Machine-Learning
This project predicts whether a customer will subscribe to a bank term deposit using Machine Learning.  The objective is to help banks identify potential customers instead of contacting everyone, reducing marketing costs while improving campaign efficiency.  ---

_____________________________________________________________________________________________________________________________
#  Bank Marketing Prediction Using Machine Learning

##  Project Overview

This project predicts whether a customer will subscribe to a bank term deposit using Machine Learning.

The objective is to help banks identify potential customers instead of contacting everyone, reducing marketing costs while improving campaign efficiency.

---

# Problem Statement

Banks spend significant resources on marketing campaigns.

Instead of contacting every customer, this project predicts customers who are most likely to subscribe to a term deposit.

---

# Objectives

- Perform Data Cleaning
- Perform Exploratory Data Analysis (EDA)
- Build Machine Learning Models
- Compare Multiple Models
- Select the Best Model
- Explain Predictions using SHAP
- Deploy using Streamlit

---

# Dataset

Dataset Source:

UCI Bank Marketing Dataset

Target Variable:

deposit

Classes:

- Yes
- No

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP
- Streamlit
- Joblib

---

# Data Preprocessing

- Missing Value Checking
- Duplicate Removal
- Label Encoding
- One-Hot Encoding
- Standard Scaling
- ColumnTransformer
- Pipeline

---

# Exploratory Data Analysis

Performed analysis on:

- Customer Age
- Balance
- Job Type
- Marital Status
- Education
- Contact Type
- Campaign
- Previous Outcome
- Housing Loan
- Personal Loan
- Month
- Subscription Distribution

---

# Machine Learning Models

The following models were trained:

- Logistic Regression
- Decision Tree
- Random Forest
- Gaussian Naive Bayes
- XGBoost
- Support Vector Machine
- K-Nearest Neighbors

---

# Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score
- Cross Validation

---

# Best Model

Random Forest Classifier

Reason:

- Highest Accuracy
- Better Precision
- Better Recall
- Better Generalization
- Robust Performance

---

# Explainable AI (SHAP)

SHAP was used to explain model predictions.

Generated:

- SHAP Summary Plot
- SHAP Bar Plot

Top Important Features:

- Duration
- Contact Type
- Housing Loan
- Previous Campaign Outcome
- Balance
- Age

---

# Deployment

The trained pipeline was saved using Joblib and deployed with Streamlit.

Users enter customer information and receive:

- Prediction
- Prediction Probability
- SHAP Explanation

---

# Project Structure

```
Bank-Marketing-Prediction
│
├── Dataset
├── Notebook
├── Model
├── README.md
```

---

# Results

Random Forest achieved the best overall performance compared to all other models.

The model successfully predicts whether a customer is likely to subscribe to a term deposit.

SHAP provides transparent explanations for every prediction.

---

# Future Improvements

- Hyperparameter Optimization
- Feature Selection
- Ensemble Models
- Cloud Deployment
- Real-Time Prediction API

---

# Author

**Abdul Malik**

Software Engineering Student

University of Sahiwal

GitHub:
https://github.com/VkmalikTech

LinkedIn:
(https://www.linkedin.com/in/abdul-malik-19024032a)
