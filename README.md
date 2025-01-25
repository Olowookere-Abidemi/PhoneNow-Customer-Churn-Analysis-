
# PhoneNow Customer Churn Analysis

This analysis dives into the churn patterns, demographics, service preferences, and financial impact of various customer groups to provide actionable insights.

---

## Dashboards

| **Service Dashboard**                                           | **Revenue Dashboard**                                        | **Customer Dashboard**                                       |
|-----------------------------------------------------------------|-------------------------------------------------------------|-------------------------------------------------------------|
| ![Services Dashboard](https://github.com/Olowookere-Abidemi/PhoneNow-Customer-Churn-Analysis-/blob/main/Services-Dashboard.png) | ![Revenue Dashboard](https://github.com/Olowookere-Abidemi/PhoneNow-Customer-Churn-Analysis-/blob/main/Revenue-Dashboard.png) | ![Customer Dashboard](https://github.com/Olowookere-Abidemi/PhoneNow-Customer-Churn-Analysis-/blob/main/Customer-Dashboard.png) |

---

## Introduction

Customer churn is a pressing challenge for subscription-based businesses like PhoneNow. With a churn rate of **27%**, retaining customers represents a significant opportunity to improve the bottom line and enhance long-term revenue potential. This report explores churn patterns, demographics, service preferences, and financial impacts of customer groups to provide actionable recommendations for reducing churn and fostering loyalty.

---

## Dataset Overview

The dataset contains customer demographics, subscription details, account information, and service usage for a telecommunications company. It was analyzed to identify churn trends, customer behavior, and actionable insights to improve retention and performance.

### Key Dataset Features

#### **Customer Demographics**
- **Gender**: Male or female.
- **SeniorCitizen**: Whether the customer is a senior citizen (1) or not (0).
- **Partner**: Indicates if the customer has a partner (Yes/No).
- **Dependents**: Whether the customer has dependents (Yes/No).

#### **Services**
- **PhoneService**: Indicates if the customer has phone service (Yes/No).
- **MultipleLines**: Shows if the customer has multiple phone lines (Yes/No/No phone service).
- **InternetService**: Type of internet service (DSL, Fiber optic, or No internet service).
- **Additional Services**: OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies (Yes/No).

#### **Account Information**
- **Contract Type**: Month-to-Month, One-Year, or Two-Year contracts.
- **PaperlessBilling**: Indicates if the customer uses paperless billing (Yes/No).
- **PaymentMethod**: Includes Electronic check, Mailed check, Bank transfer, or Credit card.
- **MonthlyCharges**: Monthly charges incurred by the customer.
- **TotalCharges**: Cumulative charges during the customer’s tenure.
- **Tenure**: Time (in months) the customer has been with the company.

#### **Customer Support Metrics**
- **AdminTickets**: Number of administrative tickets opened.
- **TechTickets**: Number of technical support tickets opened.

#### **Churn Information**
- **Churn**: Indicates whether the customer has churned (Yes/No).

---

## Problem Statement

Customer churn poses a significant challenge, impacting revenue and operational efficiency. This analysis addresses:
- **Identifying key drivers of churn.**
- **Improving retention strategies for at-risk groups.**
- **Enhancing customer support and satisfaction.**
- **Optimizing revenue streams through targeted strategies.**

---

## Insights

### **1. Demographics: Who Are Our Customers?**

#### **Gender**
- Male: 50.48% | Revenue: $8.1M (50.7%)
- Female: 49.52% | Revenue: $7.95M (49.3%)

#### **Dependents**
- Customers with dependents: 29.96% | Revenue: Lower compared to those without dependents.

#### **Partners**
- Nearly half of the customers (48.3%) have a partner, with minimal revenue disparity.

### **2. Service Usage: What Do Customers Value?**

#### **Internet Service**
- **Fiber optic**: Most popular (3,096 customers), contributing $9.9M.
- **DSL**: Less popular (2,421 customers), contributing $5.1M.
- **No internet**: Smallest segment (1,526 customers), contributing $1M.

#### **Other Services**
- Bundled services (e.g., Streaming, Tech Support) are associated with lower churn rates.

### **3. Churn Analysis: Where Are We Losing Customers?**

#### **Churn Rate**
- 27% (1,869 customers) churned, representing $3M in lost revenue.

#### **Contract Types**
- Month-to-Month contracts show higher churn compared to One-Year or Two-Year contracts.

#### **Tenure**
- Short-tenured customers (<2 years) account for most churn.

### **4. Payment and Billing**

#### **Paperless Billing**
- Preferred by 59% but linked to slightly higher churn rates.

#### **Payment Methods**
- Electronic checks are widely used but linked to higher churn compared to traditional methods like mailed checks.

### **5. Support Tickets**

- High ticket volumes (2,955 tech tickets and 3,632 admin tickets) correlate with higher churn rates.

### **6. Revenue Patterns**

#### **High Revenue Generators**
- Long-tenured customers (5–6 years) contribute the most revenue.

#### **At-Risk Revenue**
- Month-to-Month and short-tenure customers represent high churn risk.

#### **Upselling Opportunities**
- Customers with DSL or no internet services present opportunities for upselling.

---

## Recommendations

### **1. Loyalty Programs for Short-Tenure Customers**
- Introduce rewards for customers in their first two years.
- Offer incentives to migrate from Month-to-Month to longer-term contracts.

### **2. Upsell Fiber Optic Services**
- Target DSL and non-internet users with promotional offers for high-speed internet.

### **3. Improve Customer Support**
- Reduce ticket resolution times.
- Address recurring issues to improve satisfaction.

### **4. Optimize Billing and Payment Methods**
- Simplify electronic check processes and enhance communication for digital users.

### **5. Targeted Campaigns for Paperless Billing Users**
- Engage these customers with personalized communication to reduce churn.

---

## Conclusion

Churn is most prevalent among short-tenured and Month-to-Month contract customers. Strategies such as loyalty programs, enhanced customer support, and upselling services like fiber optic internet can help retain customers and maximize revenue growth.
