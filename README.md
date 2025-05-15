# 📊 Customer Churn Analysis – Power BI Project

This repository contains a Power BI project analyzing customer churn data for a fictional mobile network operator, **Databel**. The main objective of this analysis is to uncover the key drivers behind customer churn and provide actionable insights to reduce it.

---

## 📌 Project Objective

The goal was to identify patterns and behaviors that correlate with high churn rates. The dashboard was designed for stakeholders to interactively explore these insights and understand how different customer segments behave, enabling data-driven decisions to reduce churn.

---

## 🛠 Tools & Technologies

- **Power BI** (Data cleaning, modeling, DAX, and dashboard creation)
- **DAX** (used for calculated columns, measures, binning, logic with `SWITCH()`, `IF()`, `SUMX()` functions, etc.)
- **Data Modeling** (casted fields, transformed data types)
- **Interactive Visuals** (charts, tables, slicers, cards, filters, etc)

---

## 📈 Key Insights

1. **Contract Type Impact**  
   - Customers on **month-to-month** contracts have significantly higher churn rates compared to those with long-term contracts.
   - They are also more sensitive to **extra charges**, particularly on **data over charges**.

2. **Account Tenure**  
   - **Shorter account lengths** are strongly associated with churn. The longer a customer stays, the less likely they are to leave.
   - Most likely the *month-to-month* contract is too expensise and they want flexibility but affordable prices.
     
3. **International Plan Usage**  
   - Many customers have an **international plan** but **don’t use it**.
   - These customers have a high churn rate, indicating a mismatch between product offering and actual usage.
   - A **targeted downgrade recommendation** could improve satisfaction and retention.

4. **Data Usage Behavior**  
   - Most customers are **okay with paying extra** for additional data, except those on **month-to-month** contracts and those from **two-year** contract, who show dissatisfaction when billed for overages.

---

## 📄 Dashboard Overview

The analysis is presented in a **5-page interactive Power BI dashboard** covering:

- **Overview**
- **Churn reasons**
- **Churn by age and account length**
- **Data usage**
- **Cost and international usage**

Each page includes filters and dynamic visuals for stakeholders to explore the data.

---

## 📁 Repository Structure

📦 Databel-Customer-Churn-PowerBI
├── 📄 Databel.csv  # The fictional data provided by the stakeholder
├── 📄 Databel_Case_Study.pbix
└── 📄 README.md


---

## 🚀 Getting Started

1. Clone or download the repository.
2. Open the `.pbix` file with **Power BI Desktop**.
3. Explore the interactive dashboards and measures.

> 💡 **Note:** Data was cleaned and transformed entirely within Power BI. No external tools were used.

---

## 🧠 Skills Demonstrated

- Power BI data modeling
- DAX (advanced functions, logical conditions, dynamic calculations)
- Visual storytelling
- Interactive report design
- Business insight generation from raw data

---

## 📬 Contact

If you have any questions or would like to collaborate, feel free to reach out via GitHub issues or by the email danbgs93@gmail.com

---
