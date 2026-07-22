# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

Customer churn is one of the biggest challenges for telecommunication companies because retaining existing customers is more cost-effective than acquiring new ones. This project analyzes customer behavior to identify the key factors influencing churn and provides actionable business recommendations to improve customer retention.

The analysis was performed using Python in a Jupyter Notebook, following a complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), visualization, and business insight generation.

---

## 🎯 Business Problem

**Central Question:**

> **Why are customers churning, and what actions can the telecom company take to reduce customer churn?**

The objective is to identify customer characteristics associated with churn and translate those insights into practical business strategies.

---

## 📂 Dataset

- **Dataset:** Telecom Customer Churn Dataset
- **Source:** Kaggle
- **Records:** Customer information including contract details, service usage, charges, and churn status.

### Features

- Churn
- AccountWeeks
- ContractRenewal
- DataPlan
- DataUsage
- CustServCalls
- DayMins
- DayCalls
- MonthlyCharge
- OverageFee
- RoamMins

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
   - Checked missing values
   - Removed duplicates
   - Verified data types
4. Exploratory Data Analysis (EDA)
5. Business Insight Generation
6. Data Visualization
7. Business Recommendations

---

## 📊 Key Findings

### 1. Contract Renewal Significantly Impacts Customer Churn

Customers who did not renew their contracts were substantially more likely to leave the company than customers with renewed contracts.

**Business Impact:**
Targeting customers before contract expiration can improve retention.

---

### 2. Frequent Customer Service Calls Indicate High Churn Risk

Customers making multiple customer service calls showed a much higher tendency to churn, suggesting unresolved service issues.

**Business Impact:**
Early intervention for dissatisfied customers can reduce churn.

---

### 3. Higher Monthly Charges Increase Churn Probability

Customers paying higher monthly charges were more likely to discontinue their services.

**Business Impact:**
Providing better pricing options or value-added services may improve customer loyalty.

---

### 4. New Customers Are More Likely to Churn

Customers with shorter account tenure showed higher churn rates than long-term customers.

**Business Impact:**
Improving onboarding and early customer engagement can increase long-term retention.

---

## 💡 Business Recommendations

- Introduce personalized contract renewal campaigns before customer contracts expire.
- Monitor customers with frequent service calls and provide proactive support.
- Review pricing strategies for customers with higher monthly charges.
- Implement customer onboarding and engagement programs for new customers.

---

## 📊 Visualizations Included

- Customer Churn Distribution
- Contract Renewal vs Churn
- Customer Service Calls vs Churn
- Monthly Charges vs Churn
- Account Tenure vs Churn
- Overage Fee vs Churn
- Correlation Heatmap

---

## 📁 Repository Structure

```
├── telecom_churn.csv
├── week-4.ipynb
├── README.md
└── images/
    ├── churn_distribution.png
    ├── contract_vs_churn.png
    ├── customer_service_calls.png
    ├── monthly_charges.png
    ├── account_weeks.png
    └── heatmap.png
```

---



## 📌 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business-Oriented Data Analysis
- Data Visualization
- Business Insight Generation
- Customer Churn Analysis
- Communicating Findings Through Visualizations

