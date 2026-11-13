# Telco Customer Churn Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a telecommunications customer dataset to understand customer churn patterns and identify factors associated with customer retention and customer loss.

The analysis explores customer demographics, account information, subscribed services, contract types, payment methods, and billing information using Python.

## Objectives

- Understand the overall customer churn distribution.
- Explore relationships between customer attributes and churn.
- Identify customer groups with higher churn rates.
- Visualize important patterns using statistical and interactive charts.
- Provide data-driven business insights and recommendations.

## Dataset Information

- **Dataset:** IBM Telco Customer Churn Dataset
- **Total Records:** 7,043 customers
- **Total Features:** 21 columns
- **Target Column:** Churn

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Data Cleaning & Preparation

- Inspected dataset structure and data types.
- Checked missing values and duplicate records.
- Converted `TotalCharges` into numeric format.
- Handled 11 blank `TotalCharges` values by replacing them with 0 after checking that those customers had zero tenure.
- Prepared data for exploratory analysis.

## Exploratory Data Analysis

The project explores:

- Overall customer churn distribution.
- Churn patterns by contract type.
- Churn across different customer tenure groups.
- Payment method and internet service analysis.
- Customer demographics and subscribed services.
- Monthly and total charges comparison.
- Correlation analysis among numerical features.

## Key Findings

- Overall customer churn rate is approximately **26.54%**.
- Month-to-month contract customers have a higher churn rate (**42.71%**).
- Customers with 0–12 months of tenure show a higher churn rate (**47.44%**).
- Electronic check users have a churn rate of approximately **45.29%**.
- Fiber optic customers show a churn rate of approximately **41.89%**.
- Customers without Tech Support have a churn rate of approximately **41.64%**.
- Tenure and TotalCharges have a strong positive correlation of approximately **0.83**.

## Business Insights & Recommendations

Based on the analysis:

1. **Customer Retention:** Focus on improving customer onboarding and early-stage retention.
2. **Contract Strategy:** Explore incentives for customers to choose long-term contracts.
3. **Payment Experience:** Investigate why electronic check users show higher churn.
4. **Service Quality:** Further investigate customer satisfaction with Fiber Optic services.
5. **Technical Support:** Consider improving awareness and accessibility of technical support services.

*These findings indicate associations, not proven causes of customer churn.*

## Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, statistical summaries, and data visualization.

The analysis identified several customer groups associated with higher churn rates and highlighted potential areas for improving customer retention.

**This project focuses on Data Analysis and EDA. Machine Learning modeling is not included.**

## Future Scope

- Perform statistical hypothesis testing.
- Apply Machine Learning models to
