# Customer Churn Prediction Using Machine Learning

## Overview

This project presents an end-to-end machine learning solution for predicting customer churn using the Telco Customer Churn dataset.

The objective is to identify customers who are likely to leave a telecommunications company so that businesses can take proactive actions to improve customer retention.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, optimization, explainability, and deployment through an interactive interface in Google Colab.

---

## Problem Statement

Customer churn is one of the biggest challenges faced by subscription-based businesses. Losing existing customers increases acquisition costs and reduces long-term profitability.

This project builds a predictive model capable of identifying customers who are at high risk of churning before they leave.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, subscribed services, contract details, billing information, and churn status.

Target variable:

- **Churn**
  - Yes
  - No

---

## Project Workflow

### 1. Data Exploration
- Dataset inspection
- Missing value handling
- Exploratory Data Analysis (EDA)
- Data visualization

### 2. Data Preprocessing
- Data cleaning
- Feature engineering
- One-Hot Encoding
- Train/Test Split

### 3. Model Development
- Random Forest Classifier
- Cross Validation
- Hyperparameter Tuning using GridSearchCV

### 4. Model Evaluation
- Accuracy
- Confusion Matrix
- Classification Report

### 5. Model Explainability
- Feature Importance Analysis
- Top 10 Most Important Features

### 6. Interactive Prediction
- User-friendly prediction interface using Google Colab widgets
- Predict customer churn for new customer information

---

## Results

### Initial Model

Accuracy:

**78.50%**

### Optimized Model

Accuracy after GridSearchCV:

**80.62%**

The optimized model demonstrated improved predictive performance through hyperparameter tuning.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- ipywidgets

---

## Repository Structure

```
customer-churn-prediction-ml/

│── Final_Project.ipynb
│── Customer_Churn_Prediction_Final_Report.pdf
│── Telco-Customer-Churn.csv
│── README.md
```

---

## Key Features

- End-to-end machine learning pipeline
- Data preprocessing and feature engineering
- Random Forest classification
- Hyperparameter optimization
- Cross Validation
- Model evaluation
- Feature Importance visualization
- Interactive prediction interface

---

## Future Improvements

- Deploy the model as a web application using Streamlit or Flask.
- Compare multiple machine learning algorithms.
- Perform probability calibration.
- Integrate SHAP explainability for individual predictions.

---

## Author

**Mohammed Harkan**

Business Intelligence Analyst Student

GitHub:
https://github.com/Mohammedharkan