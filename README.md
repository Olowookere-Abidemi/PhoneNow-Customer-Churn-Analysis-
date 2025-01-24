# PhoneNow-Customer-Churn-Analysis-
This analysis dives into the churn patterns, demographics, service preferences, and financial impact of various customer groups to provide actionable insights. 

Service Dashboard                               |      Reveue Dashboard                                       |          Customer Dasboard
:----------------------------------------------:|:-----------------------------------------------------------:|:------------------------------------------------------:
![](https://github.com/Olowookere-Abidemi/PhoneNow-Customer-Churn-Analysis-/blob/main/Services-Dashboard.png)| ![](https://github.com/Olowookere-Abidemi/PhoneNow-Customer-Churn-Analysis-/blob/main/Revenue-Dashboard.png) | ![](https://github.com/Olowookere-Abidemi/PhoneNow-Customer-Churn-Analysis-/blob/main/Customer-Dashboard.png)

## Introduction

Customer churn is one of the most pressing challenges for subscription-based businesses like PhoneNow. With a churn rate of 27%, retaining customers has become an opportunity to improve the bottom line and enhance long-term revenue potential. This report dives into the churn patterns, demographics, service preferences, and financial impact of various customer groups to provide actionable insights. It also outlines recommendations to address churn and create a more engaged and loyal customer base.

## Overview of the Dataset

The dataset used contains information on customer demographics, subscription details, account information, and service usage for a telecommunications company. It is designed to analyze customer behavior, identify churn trends, and provide actionable insights to improve customer retention and business performance. Below is a summary of the key components of the dataset:

## Key Dataset Features

**_Customer Demographics:_**

- Gender: Identifies whether the customer is male or female.
- SeniorCitizen: Indicates whether the customer is a senior citizen (1) or not (0).
- Partner: Whether the customer has a partner (Yes/No).
- Dependents: Whether the customer has dependents (Yes/No).
  
**_Services Signed Up by Customers:_**
- PhoneService: Whether the customer has a phone service (Yes/No).
- MultipleLines: Whether the customer has multiple phone lines (Yes/No/No phone service).
- InternetService: Type of internet service (DSL, Fiber optic, or No internet service).
- OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies: Whether the customer has subscribed to these internet-based services (Yes/No).
  
**_Account Information:_**
  
- Contract Type: Customer’s contract type (Month-to-Month, One-Year, Two-Year).
- PaperlessBilling: Whether the customer uses paperless billing (Yes/No).
- PaymentMethod: Customer’s payment method (Electronic check, Mailed check, Bank transfer, Credit card).
- MonthlyCharges: Monthly charges incurred by the customer.
- TotalCharges: Cumulative charges incurred over the customer’s tenure.
- Tenure: Length of time (in months) the customer has been with the company.
  
**_Customer Support Metrics:_**

- AdminTickets: Number of administrative tickets opened by the customer.
- TechTickets: Number of technical support tickets opened by the customer.
  
**_Churn Information:_**
  
- Churn: Indicates whether the customer has churned (Yes/No).

## The Problem Solved

The primary challenge addressed was identifying the reasons for customer churn and providing actionable insights to reduce churn rates. Churn significantly impacts the telecommunications company's revenue and operational efficiency. By analyzing the dataset, the following solutions were developed:

**Understanding Customer Churn:**

- Identified key factors contributing to churn, such as high monthly charges, short tenure, and lack of long-term contracts.
- Highlighted demographic groups and service combinations with the highest churn rates.
  
**Improving Retention Strategies:**

- Suggested offering discounts or benefits for month-to-month customers to encourage them to switch to longer-term contracts.
- Recommended targeting customers with high monthly charges and offering personalized plans to reduce churn risk.

**Enhancing Customer Support:**

- Identified that churned customers had a higher frequency of technical and administrative support tickets.
- Proposed improving the efficiency of support services to address customer grievances promptly.

**Optimizing Revenue Streams:**

- Segmented customers based on their subscription details to identify high-value customers and tailored strategies to retain them.
- Highlighted services that were underutilized, such as online security and tech support, for better marketing and cross-selling efforts.

**Data-Driven Decision Making:**

- Provided the company with interactive dashboards for ongoing monitoring of churn rates, service usage trends, and customer satisfaction metrics.

## Insights

**1. Demographics: Who Are Our Customers?**

Understanding customer demographics provides a foundation for analyzing behavior patterns.

**_Gender:_**

- The customer base is evenly distributed between males (50.48%) and females (49.52%), but revenue tells a slightly different story. Male customers contribute $8.1M (50.7%), while female customers contribute $7.95M (49.3%).
- The difference is minor, suggesting that gender does not significantly influence churn or revenue patterns.
  
**_Dependents:_**

- Only 29.96% of customers (2,110) have dependents, contributing a smaller share of revenue compared to those without dependents (70.04%, 4,933 customers).
- This may indicate dependents influence service decisions, potentially driving lower spend.

**_Partners:_**

- Nearly half of the customers (48.30%) have a partner, but the revenue contribution shows no strong disparity between partnered and non-partnered customers.
- This suggests relationship status has limited direct impact on churn.

The even distribution in gender and partner status points to a balanced demographic mix. However, customers with dependents may represent a different behavior group that warrants targeted messaging or family-oriented packages.

**2. Service Usage: What Do Customers Value?**

The services customers choose directly influence revenue and satisfaction.

_Internet Service:_

- Fiber optic: The most popular service, used by 3,096 customers, generates the highest revenue at $9.9M. This group is likely satisfied with high-speed internet but may benefit from value-add bundles to further solidify loyalty.
- DSL: While less popular, 2,421 customers use DSL, contributing $5.1M. Efforts to transition these customers to fiber could improve revenue and satisfaction.
- No internet service: The smallest segment, with 1,526 customers contributing $1M. These customers may be overlooked, presenting an opportunity to upsell internet services.
- 
_Other Services:_

Bundles including streaming services, tech support, and online security are associated with lower churn, highlighting their role in customer satisfaction.

The success of fiber optic internet highlights its importance as a premium offering. Customers value reliable, high-quality services, and upselling internet packages to DSL and non-users could unlock further revenue.

**3. Churn Analysis: Where Are We Losing Customers?**

_Churn Rate:_

- 27% (1,869 customers) have churned, representing $3M in lost revenue.
- Active customers (5,174, 73%) generate $13M in revenue.

_Contract Types:_

- Month-to-month customers: This group dominates churn showing higher instability. Flexibility may make it easier for these customers to leave.
- One-year and two-year contracts: Long-term contracts reduce churn. Two-year contracts, in particular, are associated with more stable revenue.

_Tenure:_
- Short-tenured customers (<2 years) contribute disproportionately to churn. Nearly 60% of churned customers are in their first two years.
- Longer-tenured customers (5–6 years) generate higher revenue and have stronger loyalty, e.g., 6-year tenure customers contribute $7.3M alone.

Month-to-month flexibility appeals to many but comes with a higher churn risk. Retaining these customers and improving loyalty among short-tenure customers are critical areas for intervention.

**4. Payment and Billing: How Do Customers Pay?**

- Paperless Billing: This is preferred by 59% (4,171 customers), but this group exhibits slightly higher churn rates. This may indicate a need to improve communication for digitally-engaged customers.
- Payment Methods: Electronic checks, though widely used (2,365 customers), are linked to higher churn. Traditional methods like mailed checks have lower churn, suggesting a potential comfort factor among older or less tech-savvy customers.

While digital payment methods dominate, their link to churn suggests an opportunity to create seamless billing experiences and enhance trust with these customers.

**5. Support Tickets: How Does Support Impact Retention?**

- 2,955 tech tickets and 3,632 admin tickets were logged.
- High ticket volumes could signal service or support inefficiencies, leading to dissatisfaction. Addressing recurring issues or improving ticket response times could significantly reduce churn.

Support efficiency is a critical factor. Customers expect quick and reliable resolution of their issues, and falling short could push them toward competitors.

**6. Revenue Patterns: Where Are Opportunities for Growth?**

_High Revenue Generators:_

Long-tenured customers (5–6 years) generate the highest revenue. Retention strategies should prioritize maintaining these relationships.

_At-Risk Revenue:_

- Month-to-month contracts and short-tenure customers represent a high churn risk.
- Targeted loyalty programs for these groups could prevent further revenue loss.

_Upselling Opportunities:_

- Customers using DSL or no internet present opportunities to upsell to premium services like fiber optic.

Revenue stability lies in retaining long-tenured customers and converting at-risk customers into long-term loyal ones.

## Recommendations

_Loyalty Programs for Short-Tenure Customers:_

- Offer rewards, discounts, or enhanced services for customers in their first two years.
- Encourage migration from month-to-month to longer-term contracts with special incentives.
  
_Upsell Fiber Optic Services:_

- Target DSL and non-internet users with promotions highlighting the benefits of high-speed internet.
- Optimize Billing and Payment Methods:
- Simplify electronic check payments and offer educational materials for digital options to improve satisfaction.

_Improve Customer Support:_
- Reduce ticket response times and address common issues to enhance customer satisfaction.
- Targeted Campaigns for Paperless Billing Users:
- Engage paperless billing customers with personalized communication to reduce churn in this group.

## Conclusion

The analysis reveals that churn is most common among short-tenure customers and those on flexible, month-to-month contracts. Fiber optic internet is a strong revenue driver, and opportunities exist to upsell to other customer groups. Retention strategies focused on loyalty, better customer support, and targeted billing improvements can help reduce churn and maximize revenue growth.

 

 
