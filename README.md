# 📊 Customer Churn Analysis (Python + SQL + Power BI)

## 🚀 Project Overview

This project analyzes customer churn behavior for a telecom company using **Python for data cleaning** and **SQL for data analysis**, followed by an **interactive Power BI dashboard** for business insights.

The goal is to identify key factors driving customer churn and provide actionable recommendations to improve retention.

---

## 🎯 Objectives

* Analyze customer churn patterns
* Identify high-risk customer segments
* Understand impact of contract type, pricing, and services
* Provide business-driven insights for retention strategies

---

## 🛠️ Tools & Technologies

* **Python (Pandas)** → Data Cleaning
* **SQL Server** → Data Analysis
* **Power BI** → Data Visualization & Dashboard
* **GitHub** → Project Documentation

---

## 📂 Dataset Information

The dataset contains customer-level information including:

* Demographics (Gender, Senior Citizen, Partner, Dependents)
* Services (Internet, Streaming, Security)
* Account Details (Contract, Payment Method)
* Financials (Monthly & Total Charges)
* Target Variable → **Churn (Yes/No)**

---

## 🧹 Data Cleaning (Python)

Key steps performed:

* Converted `TotalCharges` to numeric format
* Handled missing values using median
* Removed inconsistencies:

  * "No internet service" → "No"
  * "No phone service" → "No"
* Verified:

  * No null values
  * No duplicate records

---

## 🗄️ Data Analysis (SQL)

Performed SQL-based analysis to answer key business questions:

* Total customers & churn rate
* Churn by contract type
* Churn by payment method
* Impact of monthly charges on churn
* Tenure-based churn segmentation
* Internet service influence
* Senior citizen churn behavior

---

## 📊 Key Insights

* 🔴 **26.5% customers churn**, indicating a retention challenge
* 📉 **Month-to-month contracts** have the highest churn (~43%)
* 💳 **Electronic check users** churn the most (~45%)
* 💰 Customers with **higher monthly charges** are more likely to churn
* ⏳ **New customers (<1 year)** show the highest churn (~47%)
* 🌐 **Fiber optic users** have higher churn compared to DSL
* 👴 **Senior citizens** are more likely to churn

---

## 📈 Power BI Dashboard

The dashboard provides:  [View Dashboard (PDF)](https://github.com/siddharthsinghnegi/CUSTOMER_CHURN/blob/main/POWER%20BI.pdf)

* KPI overview (Total Customers, Churn Rate, Avg Charges, Tenure)
* Churn distribution visualization
* Contract & payment method analysis
* Tenure and service-based insights
* Interactive filters for deeper exploration

---

## 🧠 Business Recommendations

* Encourage customers to shift to **long-term contracts**
* Improve **onboarding experience for new customers**
* Promote **automatic payment methods**
* Review **pricing strategy for high-paying customers**
* Enhance **service quality for fiber users**
* Provide **targeted support for senior citizens**

---

## 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── data/
│   └── cleaned_churn_data.csv
│
├── python/
│   └── data_cleaning.ipynb
│
├── sql/
│   └── churn_analysis.sql
│
├── dashboard/
│   └── churn_dashboard.pbix
│
└── README.md
```

---

## 🏆 Key Highlights

* End-to-end project (Python → SQL → Power BI)
* Strong focus on **business insights**
* Interactive and **story-driven dashboard**
* Real-world problem-solving approach

---

## 📌 Conclusion

Customer churn is driven by a combination of **contract flexibility, pricing, and early customer experience**. By targeting high-risk segments and improving service offerings, the business can significantly reduce churn and improve customer retention.

---

## 🙌 Connect With Me

If you found this project useful or have feedback, feel free to connect!

---
