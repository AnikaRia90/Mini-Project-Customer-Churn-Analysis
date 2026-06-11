# Customer Churn Analysis

Customer Churn Analysis is a data analysis and machine learning preparation project that focuses on understanding why customers leave a service. The project analyzes customer behavior, identifies important churn-related factors, and generates business insights that can help improve customer retention strategies.

## Project Overview

This project is based on customer churn data and follows a complete analysis workflow from data loading to business recommendations. The main goal is to explore customer patterns, understand churn behavior, and identify the key factors that influence customer churn.

The analysis includes data preprocessing, exploratory data analysis, churn distribution analysis, customer behavior analysis, important factor identification, business insights, and a basic preprocessing pipeline for future machine learning model development.

## Project Workflow

The project is divided into several sequential steps:

### 1. Dataset Loading and Overview
The dataset was loaded into Google Colab using Python. Initial exploration was performed to understand the dataset shape, column names, data types, and summary statistics.

### 2. Data Cleaning and Preprocessing
The dataset was checked for missing values, duplicate records, and incorrect data types. The `TotalCharges` column was converted into numeric format, and invalid or missing records were handled properly.

### 3. Churn Distribution Analysis
The overall distribution of churned and non-churned customers was analyzed. Basic visualizations were created to understand the proportion of customers who stayed and customers who left.

### 4. Customer Behavior Analysis
Customer behavior was analyzed using important service and billing-related features such as contract type, internet service, payment method, tenure, and monthly charges.

### 5. Important Factor Analysis
Several churn-related factors were analyzed to identify which customer groups had higher churn rates. The analysis focused on features such as contract type, internet service, payment method, tenure, monthly charges, online security, and tech support.

### 6. Business Insights and Recommendations
Based on the analysis, practical business recommendations were generated to help reduce customer churn and improve customer retention.

### 7. Preprocessing Pipeline
A basic preprocessing pipeline was created for future machine learning model development. The pipeline prepares numerical and categorical features for model training.

## Project Highlights

- Complete customer churn analysis workflow
- Data cleaning and preprocessing
- Exploratory Data Analysis with basic visualizations
- Customer behavior analysis
- Important churn factor identification
- Business insights and recommendations
- Basic preprocessing pipeline for future ML model development

## Key Findings

- Month-to-month contract customers showed a higher churn tendency.
- Customers using fiber optic internet had a higher churn rate.
- Electronic check payment users showed a higher churn rate compared to other payment methods.
- Customers with lower tenure were more likely to churn.
- Customers with higher monthly charges had a higher churn tendency.
- Customers without online security and tech support had higher churn rates.

## Business Recommendations

- Encourage short-term contract customers to move to longer-term contracts through discounts or loyalty benefits.
- Improve customer support and service quality for high-risk customer groups.
- Promote automatic payment methods to reduce churn risk.
- Focus on customer engagement during the early months of service.
- Offer better value packages, technical support, and security services to improve customer satisfaction.

## Files in This Repository

- `Mini_Churn_project (2).ipynb` - Google Colab notebook containing the full customer churn analysis
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` - Dataset used for the analysis

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Goal

The goal of this project is to analyze customer churn behavior, identify the major factors behind churn, and provide useful business recommendations. This project also prepares the dataset for future machine learning model development through a basic preprocessing pipeline.

## Conclusion

This project successfully analyzed customer churn behavior and identified several key factors related to customer churn. The findings can help businesses understand customer risk patterns and take better actions to improve customer retention.
