Telecom Customer Churn – Exploratory Data Analysis

Project Overview

This project presents an exploratory data analysis (EDA) of a telecom customer dataset to understand patterns and factors associated with customer churn. The analysis focuses on customer demographics, service usage, contract types, and billing behaviour to uncover insights that may support customer retention strategies.

Objective

The objective of this project is to explore and analyse customer churn behaviour by:

•	Examining customer demographics and service subscriptions

•	Identifying patterns in tenure, pricing, and contract types

•	Comparing churned and non-churned customers using visual and statistical analysis

•	Highlighting factors that may be associated with higher churn risk

Dataset

•	Number of observations: 7,043 customers

•	Target variable: Churn (Yes / No)

Key feature groups include:

•	Demographics: gender, senior citizen status, dependents

•	Services: internet service, streaming services, security, technical support

•	Contracts and billing: contract type, payment method, monthly charges, tenure

Tools and Libraries

The analysis was conducted using the following tools and libraries:

Python · pandas · numpy · matplotlib · seaborn

Analysis Workflow

Data Loading and Inspection

The dataset was loaded and inspected to understand its structure, including shape, column names, and data types. Sample records were reviewed to gain familiarity with the data.

1.	Data Quality Checks
   
Duplicate records were checked and none were found. Missing values were assessed across all variables, and the dataset was confirmed to be complete.

2.	Target Variable Analysis
   
The distribution of the churn variable was examined to assess class balance between churned and non-churned customers.

3.	Feature Categorisation
   
Variables were categorised into numerical and categorical features to support structured analysis.

4.	Univariate Analysis

Distributions of key numerical variables such as tenure and monthly charges were analysed. Frequency distributions of categorical variables were also examined.

5.	Bivariate Analysis
   
Churn behaviour was compared across contract types and internet service categories. Differences in tenure and monthly charges between churned and non-churned customers were analysed using boxplots.

6.	Correlation Analysis
   
Relationships between numerical variables were assessed to identify potential associations and multicollinearity.

Key Insights

•	Customer churn is more prevalent among customers with shorter tenure, indicating higher attrition early in the customer lifecycle.

•	Month-to-month contracts exhibit significantly higher churn compared to one-year and two-year contracts.

•	Customers with higher monthly charges are more frequently represented among churned customers.

•	Fiber optic internet users show higher churn counts compared to DSL users.

•	Longer contract commitments and lower pricing exposure are associated with improved customer retention.

Conclusion

The analysis highlights tenure, contract type, internet service, and pricing as important factors associated with customer churn. These insights can support business decisions related to pricing strategies, contract design, and early-stage customer engagement initiatives.

