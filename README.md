# Customer Curn Prediction
Customer churn presiction using Decision Trees and Random Forest algorithms.

## Overview

This project focuses on predicting customer churn for a telecommunications company. Customer churn refers to the phenomenon where customers stop using the services provided by the company. By accurately predicting churn, the company can take proactive measures to retain customers, thereby reducing revenue loss and improving customer satisfaction.

## Dataset

- **[Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)**

Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

The data set includes information about:

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents  

## Approach

### Data Preprocessing

- **Handling Missing Values:** Any missing values in the dataset are addressed using appropriate techniques such as imputation or removal.
- **Feature Encoding:** Categorical features are encoded using techniques like Label Encoding or One-Hot Encoding to prepare them for model training.
- **Stratified Cross-Validation:** To ensure robust model evaluation, a Stratified K-Fold Cross-Validation approach is employed, splitting the dataset into training and testing sets while preserving the class distribution.

### Model Selection

Two machine learning algorithms are utilized for churn prediction:

1. **Decision Tree Classifier:** A Decision Tree model is trained to learn decision rules from the data and predict customer churn based on their features.
2. **Random Forest Classifier:** A Random Forest model, an ensemble of decision trees, is employed to enhance predictive accuracy by reducing overfitting and capturing complex patterns in the data.

### Model Evaluation

The performance of the models is evaluated using various metrics, including accuracy, precision, recall, and F1-score. Additionally, confusion matrices are utilized to analyze the classification results and identify any discrepancies.

- Decision Tree Classifier achieved an accuracy of 78%.
- Random Forest Classifier achieved an accuracy of 80%.

![ConfMat](https://github.com/UlianaEzubchik/Customer_Curn_Prediction/assets/88460922/80277634-55b6-4555-be9c-bf63bea2a3d6)

## Dependencies

To run this project, you'll need the following Python packages:

- **[numpy](https://numpy.org/):** Fundamental package for scientific computing with Python.
- **[pandas](https://pandas.pydata.org/):** Data manipulation and analysis library.
- **[seaborn](https://seaborn.pydata.org/):** Data visualization library based on matplotlib.
- **[matplotlib](https://matplotlib.org/):** Comprehensive library for creating static, interactive, and animated visualizations in Python.
- **[scikit-learn](https://scikit-learn.org/):** Machine learning library providing simple and efficient tools for data mining and data analysis.

You can install these dependencies using pip, as shown below:

```
pip install numpy pandas seaborn matplotlib scikit-learn
```

## Contact
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ulyana-yezubchyk/)](https://www.linkedin.com/in/ulyana-yezubchyk/)
[![Email](https://img.shields.io/badge/Email-ulyaa.071@gmail.com-green.svg)](mailto:your_email@example.com)

[![Back to Top](https://img.shields.io/badge/-Back_to_Top-blue?style=flat-square)](#FCustomer-Curn-Predictionr)
