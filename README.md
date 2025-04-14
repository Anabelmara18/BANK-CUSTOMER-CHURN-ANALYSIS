# Table of Contents

## Overview
- [Project Description](#project-description)
- [Business Problem](#business-problem)
- [Business Objectives](#business-objectives)
- [About the Dataset](#about-the-dataset)

## Analysis Process
- [Data Cleaning](#data-cleaning)
  - [Handling Missing Values](#handling-missing-values)
  - [Handling Duplicates](#handling-duplicates)
  - [Handling Outliers](#handling-outliers)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Univariate Analysis](#univariate-analysis)
  - [Bivariate Analysis](#bivariate-analysis)
  - [Correlation Analysis](#correlation-analysis)

## Insights and Findings
- [Customer Demographics](#customer-demographics)
- [Account Information](#account-information)
- [Product Usage](#product-usage)
- [Customer Satisfaction and Engagement](#customer-satisfaction-and-engagement)
- [Churn Rate Analysis](#churn-rate-analysis)

## Recommendations
- [For Customer Retention](#for-customer-retention)
- [For Product Strategy](#for-product-strategy)
- [For Customer Service](#for-customer-service)

## Conclusion
- [Key Takeaways](#key-takeaways)
- [Future Work](#future-work)

## Resources
- [Dataset Source](#dataset-source)
- [Tools Used](#tools-used)

## BANK-CUSTOMER-CHURN-ANALYSIS
I analyzed a bank customer dataset to identify key churn drivers using SQL for data preparation, Power BI for visualization, and DAX for advanced calculations. Built an interactive dashboard to uncover actionable insights and support customer retention strategies.

##  Overview

This project focuses on analyzing customer behavior and identifying the factors contributing to customer churn in a banking institution. The aim is to uncover patterns, trends, and key churn drivers so the bank can take proactive steps to improve customer retention.

I performed data cleaning, exploratory data analysis (EDA), created dashboards, and generated actionable insights using **Power BI**, **SQL**, and **DAX**.

> **Dataset Source:**  
> [Bank Customer Churn - Kaggle](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)

---

##  Project Objective

The objective of this project is to analyze customer churn patterns for a bank, identify key factors contributing to churn, and provide actionable insights to improve customer retention. The dashboard visualizes churn distribution across demographics, customer behavior, financial metrics, and product usage to support data-driven decision-making and enhance customer relationship strategies.

---

## 🛠 Techniques Applied

- **Power BI**: Developed an interactive dashboard for visualizing churn trends and customer behavior.
- **SQL**: Used to create and transform raw datasets into structured tables for analysis, including aggregating churned metrics and filtering target customer groups.
- **DAX (Data Analysis Expressions)**: Applied to create measures, calculated columns, KPIs, and segmentation logic.
- **Data Modeling**: Built relationships between fact and dimension tables to enable efficient filtering and accurate reporting.

---

##  Insights

### 🔹 General Overview
- **Churn Rate**: 20.38%
- **Total Customers**: 10,000
- **Average Balance (Churned)**: $91.11K  
- **Average Salary (Churned)**: $101.51K

###  Demographic & Behavioral Insights
- **Gender**: Female churn rate (25.07%) is higher than male churn (16.47%).
- **Geography**: Highest churn in Germany and France.
- **Age**: Most churn occurs in customers aged 25–45.
- **Satisfaction Score**: Highest churn occurs at score 2.
- **Tenure**: Customers with 2–6 years show the highest churn.

###  Product & Financial Insights
- **Number of Products**: 69% of churned customers own only 1 product.
- **Credit Card**: Card ownership doesn't significantly affect churn.
- **Card Type**: Diamond card holders churn slightly more than others.
- **Credit Score**: Most churn happens in the 600–699 range.
- **Balance & Salary**: High-value customers are churning.

---

##  Recommendations

###  Customer Retention
- Focus on **females** and customers aged **25–45** with targeted offers.
- Encourage multi-product usage to reduce single-product churn.
- Investigate churn causes in **Germany and France**.
- Launch loyalty campaigns for customers with **2–6 years tenure**.
- Improve experience for customers with **low satisfaction scores**.

###  Financial/Product Actions
- Strengthen benefits for **Diamond & Platinum cardholders**.
- Review mid-range **credit score segment** policies.
- Prioritize **high-balance and high-income** customer retention with VIP banking services.

---

##  Conclusion

This project provides a comprehensive view of customer churn across key factors. Using **Power BI**, **SQL**, and **DAX**, the dashboard uncovers patterns and delivers actionable insights to help reduce churn and improve customer satisfaction.

---
![Screenshot 2025-04-14 010859](https://github.com/user-attachments/assets/c8f2e0b4-baf4-49b8-ad45-78667dd49f40)


![Screenshot 2025-04-14 010114](https://github.com/user-attachments/assets/cc6757b1-39a8-40c0-a5a3-4156cc34f680)


### 👤 Prepared By  
**Amankwe Amarachi**  
*Data Analyst*  
**Tools:** Power BI | SQL | DAX
