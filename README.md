# Customer-Churn-Analysis-Telecom-Dataset
This notebook analyzes Telco customer churn across 7,043 customers with 21 features.


## Project Overview

This project analyzes customer churn in a telecom company using Python, data visualization, and machine learning techniques. The goal is to identify the factors that influence customer churn and build predictive models that can help businesses improve customer retention.

## Objectives

* Perform data cleaning and preprocessing
* Analyze customer churn patterns
* Visualize key business insights
* Engineer features for machine learning
* Train and compare multiple classification models
* Generate churn probability scores

## Dataset

The project uses the Telecom Customer Churn Dataset containing customer demographics, account information, services subscribed, billing details, and churn status.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* Jupyter Notebook

## Exploratory Data Analysis (EDA)

The analysis includes:

* Overall churn distribution
* Churn rate by gender
* Churn rate by contract type
* Churn rate by payment method
* Churn rate by internet service
* Churn rate by tech support
* Churn rate vs tenure
* Correlation heatmap

## Feature Engineering

* Missing value handling
* Data cleaning
* One-hot encoding of categorical variables
* Feature scaling using StandardScaler

## Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Random Forest Classifier

## Model Evaluation

Models were compared based on prediction accuracy. A confusion matrix and classification metrics were used to evaluate model performance.

## Key Business Insights

* Customers with shorter tenure are more likely to churn.
* Customers without technical support show higher churn rates.
* Contract type significantly influences customer retention.
* Monthly charges and total charges impact churn behavior.
* Long-term customers are less likely to leave the service.

## Project Structure

customer-churn-analysis/

├── data/

│ └── churn.csv

├── notebook/

│ └── customer_churn.ipynb

├── images/

│ └── correlation_heatmap.png

├── README.md

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Advanced ensemble models
* Deployment using Streamlit or Flask
* Real-time churn prediction dashboard

## Author

Rohit Jangid

Business Analyst | Aspiring Data Analyst & Data Engineer

