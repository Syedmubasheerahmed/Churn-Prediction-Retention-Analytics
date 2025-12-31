# TELCO CUSTOMER CHURN PREDICTION & RETENTION ANALYTICS

## Project Overview
![1](Outputs/1.png)

A comprehensive machine learning and data analytics project analyzing 7,043 telecommunications customers to predict churn risk and develop targeted retention strategies. This hands-on learning project demonstrates the complete analytics pipeline: exploratory data analysis → predictive modeling → business intelligence → actionable recommendations.

## Dataset Information

IBM Telco Customer Churn Dataset

Records: 7,043 customers

Features: 21 attributes

Target Variable: Churn (Yes/No)

## Data Attribution

Dataset: IBM Telco Customer Churn

Provider: IBM Sample Datasets

Platform: Kaggle

## Data Categories:

- Services: Phone, Internet (DSL/Fiber), Online Security, Backup, Device Protection, Tech Support, Streaming TV/Movies

- Account: Tenure (months), Contract type (Month-to-month/One-year/Two-year), Payment method, Monthly/Total charges

- Demographics: Gender, Senior citizen status, Partner, Dependents

## Impact:

- Identified 436 high-risk customers accounting for $37.7K monthly revenue at risk ($452K annually)

- Built predictive model with 80% accuracy and 84% AUC-ROC score

- Segmented all customers into 3 risk categories with specific retention actions

- Created executive dashboards for stakeholder decision-making

## Project Structure & Notebooks

Notebook 1: Data_Exploration.ipynb

Explores churn patterns across the customer base:

- Dataset validation and quality checks

- Overall churn rate analysis (26.5% of customers)

- Customer segmentation by contract, tenure, services

- Identification of high-risk customer groups

<img width="4762" height="2966" alt="churn_analysis_dashboard" src="https://github.com/user-attachments/assets/b5ab652f-5070-454e-b72a-265c0ca1b530" />

<img width="3794" height="1466" alt="churn_overview" src="https://github.com/user-attachments/assets/e6380173-855e-4c31-a5e8-3a830dc25eef" />

Notebook 2: Model_Building.ipynb

Develops and compares three classification models:

- Data preprocessing and feature engineering (15 categorical + 6 numerical features)

- Training three models: Logistic Regression, Random Forest, Gradient Boosting

- Model performance comparison across all metrics

- Selection of best-performing model

<img width="4170" height="1470" alt="model_performance" src="https://github.com/user-attachments/assets/e3365f7c-0ffe-46d9-908d-cc0b8912590d" />

Notebook 3: Risk_Segmentation.ipynb

Applies model to all customers and creates actionable outputs:

- Scores all 7,043 customers with churn probabilities

- Categorizes into High/Medium/Low risk segments

- Profiles high-risk customers (436 total)

- Quantifies revenue at risk by segment

- Develops retention strategies for each risk level

## Power BI Dashboard

- Churn Analysis Dashboard (interactive executive dashboard)

- Pages include: Home, Overview, Risk Analysis, Action Plan

- Filters available: Contract type, Internet service, Tech support

- Metrics displayed: Total customers, risk distribution, revenue at risk, churn by tenure

# Home 

<img width="1327" height="740" alt="1" src="https://github.com/user-attachments/assets/1346d412-6c06-4169-a1df-dbbdf86f21c6" />

# Overview

<img width="1325" height="745" alt="2" src="https://github.com/user-attachments/assets/5b5ba70e-0b9c-46f8-bfc9-0b1ca3922b40" />

# Risk Analysis

<img width="1326" height="744" alt="3" src="https://github.com/user-attachments/assets/bf95e779-ac93-4937-9445-15887de74fef" />

# Action Plan

<img width="1328" height="744" alt="4" src="https://github.com/user-attachments/assets/2571c7ea-b818-4efd-99f1-f83651b0d2b5" />

## Key Findings

Churn Reality (26.5% of customers)

- 1,869 out of 7,043 customers churned
  
- Represents $1.45M annual revenue impact
  
- Highest risk in first 6 months (53% churn rate)

Strongest Risk Factors

1. Contract Type: Month-to-month customers 15x more likely to churn (42.7% vs 2.8%)
  
2. Tenure: First 6 months critical period with 53% churn rate
   
3. Longer commitments dramatically improve retention (2+ years: 14% churn)

Model Performance
- Accuracy: 80% - Correct prediction 4 out of 5 times
  
- Recall: 55% - Identifies 55% of actual churners
  
- AUC-ROC: 85% - Good at ranking risk levels
  
- Precision: 65% - When predicting churn, usually correct

What This Means:

- Model catches the highest-risk customers (not all churners)
  
- Useful for targeting retention efforts on likely-to-churn customers
  
- Real-world accuracy is good for business application

# Learning Objectives Achieved
Data Analysis Skills

- Exploratory data analysis on 7,043 customer records

- Feature engineering and categorical encoding

- Statistical analysis of churn patterns

- Correlation and segmentation analysis

Machine Learning Skills

- Training multiple classification models

- Model evaluation using confusion matrix and ROC-AUC

- Feature importance analysis

- Model selection based on business metrics

Business Skills

- Translating technical findings into business recommendations

- Quantifying financial impact of churn (revenue at risk)

- Creating customer action lists for marketing teams

- Designing retention strategies by customer segment

Communication Skills

- Creating executive-level visualizations

- Writing clear business recommendations

- Organizing analysis for stakeholder presentations

- Documenting methodology transparently

## About This Learning Project

This is a self-directed learning project created to develop practical data analytics skills using a publicly available dataset. The project demonstrates both technical competence (ML modeling, data analysis, statistics) and business awareness (ROI calculations, stakeholder communication, actionable recommendations).

Each notebook uses a question-driven analytical approach where business problems frame the analysis, showing how data scientists think strategically about real-world challenges.

Data Privacy Note: This project uses the public IBM Telco Customer Churn dataset (available on Kaggle). All customer IDs are synthetic, and no personally identifiable information is contained in the analysis or outputs.
