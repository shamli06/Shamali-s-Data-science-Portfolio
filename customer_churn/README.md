# 📊 ChurnGuard: Predicting & Preventing Customer Churn in a Subscription Business

---

## 🧩 Business Problem

A subscription-based telecom company is experiencing increasing customer churn, leading to revenue loss and rising customer acquisition costs. While the company invests heavily in marketing to acquire new customers, retaining existing customers is significantly more cost-effective.

Currently, the company does not have a data-driven system to:

- Predict which customers are likely to churn  
- Identify the key factors driving churn  
- Proactively intervene before customers leave  

As a result, retention efforts are reactive rather than strategic.

This project aims to build a predictive churn model and translate its outputs into actionable business strategies to reduce customer attrition and protect revenue.

---

## 📖 What is Customer Churn?

Customer churn refers to the percentage of customers who stop using a company's product or service within a given time period.

In subscription businesses, churn typically occurs when a customer:

- Cancels their subscription  
- Fails to renew their contract  
- Stops making payments  

### 📌 Churn Rate Formula
Churn Rate = Customers Lost During Period / Total Customers at Start of Period

**Example:**  
If 1,000 customers were active at the start of the month and 80 left, the churn rate = **8%**.

---

## 💰 Why Churn Matters

Customer churn directly impacts business performance in multiple ways:

### 1️⃣ Revenue Stability  
Recurring revenue businesses depend on predictable subscription income. High churn destabilizes revenue forecasting.

### 2️⃣ Customer Acquisition Cost (CAC)  
Acquiring a new customer is often 5–7x more expensive than retaining an existing one.

### 3️⃣ Customer Lifetime Value (CLV)  
Higher churn reduces the average duration a customer stays, lowering lifetime revenue per customer.

### 4️⃣ Competitive Risk  
High churn may indicate dissatisfaction, poor service quality, pricing issues, or competitive pressure.

> Even a small reduction in churn (e.g., 5%) can significantly increase long-term profitability.

---

## 📊 Business KPIs

This project focuses on the following key performance indicators:

---

### 1️⃣ Churn Rate

**Definition:**  
Percentage of customers who leave during a specific time period.

**Business Goal:**  
Reduce churn rate by identifying high-risk customers early and applying targeted retention strategies.

---

### 2️⃣ Customer Lifetime Value (CLV)

**Definition:**  
The total revenue expected from a customer over their entire relationship with the company.

### 📌 Basic CLV Formula
CLV = Average Monthly Revenue × Average Customer Lifespan (in months)

**Impact of Churn:**

- Higher churn → Shorter lifespan → Lower CLV  
- Lower churn → Longer retention → Higher CLV  

---

### 3️⃣ Revenue Loss Due to Churn
Revenue Loss = Number of Churned Customers × Average Monthly Revenue

This project will simulate potential revenue saved if high-risk customers are retained through targeted interventions.

---

## 🎯 Project Objectives

This project aims to:

1. Analyze historical customer data to understand churn patterns  
2. Build a predictive model to estimate churn probability  
3. Identify key churn drivers using model explainability  
4. Segment customers into risk categories  
5. Estimate potential revenue savings from targeted retention strategies  

The final outcome will provide business stakeholders with actionable insights to reduce churn and improve long-term profitability.

---

## 🗂 Repository Structure
churn-guard/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── sql/
│ ├── schema.sql
│ ├── churn_analysis.sql
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ ├── 02_eda.ipynb
│ ├── 03_modeling.ipynb
│
├── dashboard/
│
├── requirements.txt
└── README.md

### Folder Descriptions

- **data/raw/** → Original dataset files  
- **data/processed/** → Cleaned and feature-engineered datasets  
- **sql/** → SQL scripts for schema creation and churn analysis  
- **notebooks/** → Jupyter notebooks for analysis and modeling  
- **dashboard/** → dashboard files  
- **requirements.txt** → Python dependencies  
---

## 🚀 Expected Business Outcome

By implementing this predictive churn system, the company will be able to:

- Identify high-risk customers before they leave  
- Prioritize retention campaigns efficiently  
- Reduce revenue leakage  
- Increase overall Customer Lifetime Value  

This project demonstrates how data science can move from descriptive analysis to proactive business decision-making.
