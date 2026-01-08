Customer Shopping Behavior Analysis

End-to-End Data Analytics Project | Python • SQL (MySQL) • PostgreSQL • Power BI

 Project Overview
 
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover actionable insights related to spending patterns, product preferences, discount sensitivity, subscription behavior, and customer segmentation to support data-driven business decisions.

The project follows a complete analytics lifecycle — from data cleaning and feature engineering in Python, to business analysis using SQL, and final storytelling through an interactive Power BI dashboard.

 Dataset Summary

Total Transactions: 3,900

Total Features: 18

Data Types: Customer demographics, transaction details, and behavioral metrics

Key Attributes

Customer: Age, Gender, Location, Subscription Status

Transaction: Product, Category, Amount, Season, Size, Color

Behavioral: Discounts, Purchase Frequency, Previous Purchases, Ratings, Shipping Type

Data Quality Handling

Missing review ratings were imputed using median values per product category

Redundant features were identified and removed to improve analytical clarity

Tools & Technologies

Python: pandas, numpy (EDA, cleaning, feature engineering)

SQL: MySQL (business analysis queries)

Database: PostgreSQL (cleaned data storage)

Visualization: Power BI (interactive dashboard)

 Analytical Workflow
1️ Data Cleaning & Feature Engineering (Python)

Standardized column naming (snake_case)

Created age_group for demographic analysis

Engineered purchase_frequency_days to better reflect buying behavior

Validated and optimized schema before database loading

 Business Analysis (SQL – MySQL)

Key business questions answered:

Revenue contribution by gender

Spending comparison: subscribers vs non-subscribers

Identification of high-value discount shoppers

Top-rated products and most purchased items by category

Impact of shipping method on purchase value

Customer segmentation (New, Returning, Loyal)

Relationship between repeat purchases and subscription adoption

Revenue distribution across age groups

 Power BI Dashboard

An interactive dashboard was built to communicate insights visually, featuring:

Total customers & average purchase value

Revenue by product category

Subscription distribution

Sales and revenue by age group

Discount and shipping behavior filters

The dashboard enables dynamic exploration of customer behavior and supports business storytelling.

Key Business Insights

Loyal customers form the largest customer segment

Subscription users contribute significant long-term value

Certain products show high discount dependency

Young and middle-aged customers generate the highest revenue

Express shipping customers tend to have higher purchase values

 Recommendations

Increase subscription adoption via targeted incentives

Strengthen loyalty programs to convert returning customers

Optimize discount strategies to protect margins

Focus promotions on high-rated, high-volume products

Allocate marketing spend toward high-revenue age segments
