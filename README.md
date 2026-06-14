# Customer-Credit-Risk-Preprocessing-and-Feature-Engineering
A complete Data Science preprocessing project on Customer Credit Risk data involving data acquisition from CSV, JSON, SQL and API sources, missing value handling, outlier treatment, encoding, scaling, feature engineering, feature transformation, and final dataset preparation for machine learning.
Customer-Credit-Risk-Preprocessing-and-Feature-Engineering
│
├── data
│   ├── customer_credit_risk_dataset.csv
│   ├── customer_metadata.json
│
├── notebook
│   └── Customer_Credit_Risk_Preprocessing.ipynb
│
├── reports
│   ├── EDA_Report.html
│   ├── Final_Report.pdf
│
├── images
│   ├── histogram.png
│   ├── boxplot.png
│   ├── heatmap.png
│
├── README.md
│
└── requirements.txt

# Customer Credit Risk Dataset Preprocessing and Feature Engineering

## Project Overview

This project performs complete data preprocessing and feature engineering on a Customer Credit Risk Dataset to prepare the data for machine learning model development.

## Objectives

- Data Acquisition from CSV, JSON, SQL and API
- Data Cleaning
- Missing Value Handling
- Outlier Detection and Treatment
- Feature Engineering
- Feature Scaling
- Data Transformation
- Final Dataset Preparation

## Dataset Features

- Customer Demographics
- Financial Information
- Behavioural Attributes
- Loan Default Target Variable

## Techniques Used

### Missing Value Handling

- Mean Imputation
- Median Imputation
- Mode Imputation
- Constant Imputation
- KNN Imputation
- MICE Imputation

### Outlier Handling

- Z-Score
- IQR Method
- Percentile Method
- Winsorization

### Encoding

- Ordinal Encoding
- Label Encoding
- One-Hot Encoding

### Scaling

- StandardScaler
- MinMaxScaler
- MaxAbsScaler
- RobustScaler
- Normalization

### Transformations

- Log Transformation
- Square Root Transformation
- Reciprocal Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation

### Feature Engineering

- Debt-to-Income Ratio
- Spending-to-Income Ratio
- Average Monthly Transactions
- Date Features

## Results

The dataset was cleaned, transformed, encoded, scaled and feature-engineered successfully. The final dataset is ready for machine learning model development.

The objective of this project is to prepare a Customer Credit Risk dataset for machine learning by performing comprehensive preprocessing and feature engineering. Data was collected from multiple sources, cleaned, transformed, encoded, and scaled. New features were constructed to improve predictive capability, resulting in a final dataset ready for loan default prediction models.
Project Files

1. Customer_Credit_Risk_Preprocessing.ipynb
   - Main notebook containing all preprocessing and feature engineering tasks.
2. customer_credit_risk_dataset.csv
   - Original customer credit risk dataset.
3. customer_metadata.json
   - Customer metadata used for JSON data acquisition demonstration.
4. customer.db
   - SQLite database used for SQL data acquisition demonstration.
5. EDA_Report.html
   - Automated data profiling report generated using ydata-profiling.
6. Final_Customer_Credit_Risk_Dataset.csv
   - Final cleaned and transformed dataset ready for machine learning.
7. README.md
   - Project documentation.
     
## Author

Anuj Rasaily
