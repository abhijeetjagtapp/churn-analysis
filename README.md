# 📊 Customer Churn Analysis
### End-to-End Data Analysis Project using Python, Pandas, SQL & Matplotlib

## Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses.
This project analyzes customer behavior, subscription history, complaints, and revenue to identify patterns that lead to customer churn.
The project covers the complete data analysis lifecycle from data cleaning and feature engineering to exploratory data analysis and business insights.

## Business Problem

A subscription business wants to understand:

- Why customers leave
- Which plans experience the highest churn
- Revenue at risk due to churn
- Customer retention trends
- Factors contributing to churn

## Objectives

- Clean and prepare raw data
- Merge multiple datasets
-  Perform exploratory data analysis
- Calculate churn KPIs
- Create visualizations
- Generate actionable business insights

## Dataset

The analysis uses three datasets:
- Customer Information
- Subscription Details
- Customer Support Records

The datasets were merged to create a unified analytical dataset.
<img width="1131" height="686" alt="image" src="https://github.com/user-attachments/assets/227285f2-175e-482d-a592-c507ca226165" />

## Tech Stack

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Git
GitHub

## 📌 Methodology

### 1. Data Collection
- Imported customer, subscription, and support datasets
- Inspected tables and data types

### 2. Data Cleaning
- Removed unnecessary columns
- Renamed columns for consistency
- Handled missing values
- Corrected data types
- Standardized categorical values

### 3. Feature Engineering
- Created Churn Flag
- Calculated Complaint Count
- Merged datasets using left joins
- Removed duplicate support records
- Created analytical dataset

### 4. Exploratory Data Analysis
- Churn Rate
- Retention Rate
- Average Revenue
- Average Customer Tenure
- Revenue at Risk
- Escalation Rate
- Average Complaints
- Correlation Analysis

### 5. Data Visualization
- Matplotlib
- Seaborn
- Heatmaps
- Pivot Tables

## 📈 Visualizations

### Matplotlib

- Monthly Churn Trend
- Churn by Plan Type
- Churn by Subscription Type

### Seaborn

- Correlation Heatmap
- Distribution Plots
- Count Plots

### Pivot Tables

- Churn by Plan
- Churn by Subscription
- Complaint Analysis



## ✨ Key Features

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Business KPI Calculation
- Pivot Table Analysis
- Correlation Analysis
- Seaborn Visualizations
- Matplotlib Visualizations
- Business Recommendations

## Key Insights

<img width="1259" height="546" alt="image" src="https://github.com/user-attachments/assets/a2061f73-1f43-4eac-9696-d450db1b1dc6" />

## 📊 Business KPIs

| KPI | Description |
|------|-------------|
| Churn Rate | Percentage of customers who left |
| Retention Rate | Percentage of retained customers |
| Average Revenue | Revenue generated per customer |
| Average Tenure | Customer lifetime |
| Revenue at Risk | Lost revenue from churned customers |
| Escalation Rate | Escalated complaints |
| Average Complaints | Complaints per customer |

Raw Data
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
Data Merging
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Pivot Tables
    │
    ▼
Matplotlib Visualizations
    │
    ▼
Seaborn Visualizations
    │
    ▼
Business Insights
    │
    ▼
Recommendations



## Recommendations

- Improve onboarding for Basic plan customers.
- Address complaints faster.
- Create retention campaigns for high-risk customers.
- Reward long-term subscribers.
- Monitor churn monthly using dashboards.


## Future Improvements

- Build an interactive Power BI dashboard
- Develop a churn prediction model
- Automate data ingestion
- Deploy a Streamlit application
- Perform customer segmentation

## How to Run
git clone ...

cd Customer-Churn-Analysis

pip install -r requirements.txt

jupyter notebook

Customer-Churn-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_import.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_eda.ipynb
│   ├── 05_visualization_matplotlib.ipynb
│   ├── 06_visualization_seaborn.ipynb
│   └── 07_business_insights.ipynb
│
├── images/
│   ├── churn_monthly.png
│   ├── churn_by_plan.png
│   ├── churn_subscription.png
│   ├── correlation_heatmap.png
│   └── pivot_tables.png
│
├── requirements.txt
├── README.md
└── LICENSE

## Author

Abhijeet Jagtap
