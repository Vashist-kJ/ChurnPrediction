
# Telecom Customer Churn Prediction

This project focuses on predicting customer churn for a telecom company using a machine learning approach. The goal is to help the company identify customers likely to churn and take appropriate actions to retain them.

## Project Overview
The dataset used contains information about telecom customers, including demographics, services they have subscribed to, their tenure, and whether they have churned. The project involves data preprocessing, exploratory data analysis (EDA), model building, and evaluation to predict customer churn.

### Key Steps:
- **Data Loading**: Reading and exploring the dataset from a CSV file.
- **Data Cleaning**: Handling missing values and correcting data types for certain columns.
- **Exploratory Data Analysis (EDA)**: Analyzing churn distribution and relationships between features using visualizations.
- **Feature Engineering**: Creating new features, and converting categorical data to numerical values for modeling.
- **Modeling**: Training machine learning models such as Logistic Regression, Decision Trees, and Random Forest to predict customer churn.
- **Evaluation**: Assessing model performance using accuracy, precision, recall, and AUC-ROC curves.

## Dataset
The dataset consists of 7043 records and 21 columns, including features such as:
- **Customer Information**: `customerID`, `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- **Service Information**: `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, etc.
- **Contract Information**: `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`
- **Target**: `Churn`

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn



