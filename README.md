# 💳 Credit and Loan Default Risk Analysis – EDA Project (Python)

This repository contains an end-to-end Exploratory Data Analysis (EDA) project that focuses on identifying risk patterns among loan applicants, using credit and loan application data. The goal is to help lending companies identify reliable customers and minimize financial risk due to defaulting clients.

---

## 🧠 Problem Statement

Loan-providing companies face challenges in granting loans to individuals with little or no credit history. This opens the door for potential defaulters who exploit the system. Our goal is to assist a consumer finance company that lends various types of loans to urban customers by performing EDA on their data to:

- **Identify the applicants likely to default**
- **Understand drivers behind loan repayment difficulties**
- **Reduce risk while maximizing business opportunities**

---

## 🎯 Business Objective

- Minimize risk of loan default by identifying key patterns and variables indicating financial unreliability.
- Ensure customers **capable of repaying** are **not rejected** due to insufficient data.
- Use insights for **portfolio risk assessment** and **interest rate optimization** based on risk.

---

## 🗃️ Dataset Description

The project uses three datasets:

| File Name                  | Description |
|---------------------------|-------------|
| `application_data.csv`    | Main applicant information at the time of loan application. |
| `previous_application.csv`| Details of clients' previous loans and application status. |
| `columns_description.csv` | Data dictionary with descriptions of all variables. |

Each application belongs to one of the following categories:

- `Approved`
- `Cancelled`
- `Refused`
- `Unused Offer`

---

## 📌 Analysis Performed

### ✅ Data Cleaning & Preprocessing

- Identified and handled missing values
- Cleaned column names and types
- Removed/replaced irrelevant or uninformative variables

### ✅ Outlier Detection

- Univariate outlier analysis using box plots
- Justified whether to retain or discard based on business logic

### ✅ Data Imbalance Check

- Examined the imbalance in the **target variable**
- Visualized imbalance using count plots and pie charts
- Discussed the impact on analysis

### ✅ Exploratory Data Analysis (EDA)

- **Univariate analysis** of categorical & numerical variables
- **Segmented univariate**: Analyzed distributions for defaulters vs. non-defaulters
- **Bivariate analysis**: Relationships between loan amount, income, credit score, etc.

### ✅ Correlation Analysis

- Segmented data by target variable
- Identified **top 10 correlated pairs** of continuous variables for each group
- Explained how these correlations could affect repayment behavior

---

## 📊 Tools & Libraries Used

- Python
  - `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- Jupyter Notebook (`.ipynb`)
- Power BI (separate dashboard - optional)
- (Optional: Tableau for presentation visuals)

---

## 📁 Project Structure
