---Overview---

This Jupyter Notebook contains an analysis of customer churn in the telecom industry. The project explores a dataset containing customer information to identify patterns and factors that contribute to customer churn. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization to understand the characteristics of customers who leave the service (churn) versus those who stay.

---Dataset---

The dataset used in this analysis is named Customer Churn.csv and contains 7043 rows with 21 columns of customer information, including:

Customer demographics: gender, senior citizen status, partner/dependents

Account information: tenure, contract type, paperless billing, payment method

Service details: phone service, multiple lines, internet service, online security, online backup, device protection, tech support, streaming TV, streaming movies

Charges: monthly charges, total charges

Target variable: Churn (Yes/No)


---Key Findings---

Data Cleaning:

Converted TotalCharges from string to float type after replacing blank values with '0'

Transformed SeniorCitizen values from 0/1 to 'no'/'yes' for better readability

Verified no missing values or duplicates in the dataset

Exploratory Analysis:

The dataset shows approximately 26.5% churn rate (1869 customers churned out of 7043)

Key visualizations include:

Countplot of churn distribution

Analysis of numerical features (tenure, monthly charges, total charges)

Examination of categorical features (contract type, payment method, etc.)

Notable Observations:

Customers with month-to-month contracts have higher churn rates

Higher monthly charges correlate with increased churn

Customers with longer tenure are less likely to churn

Electronic check payment method shows higher churn compared to other methods

---How to Use This Notebook---
Prerequisites:
Python 3.x

Jupyter Notebook

Required Python packages:

pandas

numpy

matplotlib

seaborn

Running the Notebook: 
Clone the repository or download the notebook file

Ensure the dataset Customer Churn.csv is in the specified path or update the file path in the notebook

Run the notebook cells sequentially

---Code Structure---

Data Loading: Imports necessary libraries and loads the dataset

Data Exploration: Initial examination of the dataset structure and content

Data Cleaning: Handles missing values, data type conversions, and feature engineering

Exploratory Analysis: Visualizations and statistical summaries to understand patterns

Key Insights: Interpretation of findings and business implications
