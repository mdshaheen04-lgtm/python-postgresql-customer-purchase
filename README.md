 # 🛍️ Customer Shopping Behavior & Revenue Analysis

## 📌 Project Overview
This end-to-end data analytics project explores  3,900 customer shopping transactions across 18 attributes—including customer demographics, product categories, seasonal trends, subscription status, and discount usage. The goal is to clean raw retail data, uncover key revenue drivers, and build an interactive Power BI dashboard to support data-driven marketing and inventory decisions.

## 🛠️ Tools & Technologies Used
Python (Pandas, NumPy):  Data cleaning, missing value imputation, and exploratory data analysis (EDA).
SQL: Business querying, customer segmentation, and aggregation analysis.
Power BI: Interactive dashboarding, DAX measures, and visual storytelling.
Excel: Initial data inspection and validation.

## 📂 Dataset Summary
 Total Records: 3,900 customer transactions
 Total Features: 18 columns (`Customer ID`, `Age`, `Gender`, `Item Purchased`, `Category`, `Purchase Amount (USD)`, `Location`, `Size`, `Color`, `Season`, `Review Rating`, `Subscription Status`, `Shipping Type`, `Discount Applied`, `Promo Code Used`, `Previous Purchases`, `Payment Method`, `Frequency of Purchases`)
* **Product Categories:** Clothing, Footwear, Outerwear, Accessories

## 🧹 Data Cleaning & Preparation
1.  Handled Missing Values :  Identified missing entries in the `Review Rating` column and imputed them using category-wise median ratings to preserve data integrity without skewing distributions.
2.  Data Type Standardization : Verified numeric formatting for `Purchase Amount (USD)`, `Age`, and `Previous Purchases`, and standardized categorical labels.
3.  Feature Engineering : Created customer age brackets (Young Adult, Adult, Middle-Aged, Senior) and purchase frequency groups for deeper segmentation.

## 📊 Key Insights & Findings
Category & Seasonal Performance: Analyzed revenue distribution across Clothing, Footwear, Outerwear, and Accessories across all four seasons (`Winter`, `Spring`, `Summer`, `Fall`) to identify peak demand periods.
 Subscription & Discount Impact: Compared average order value (AOV) and repeat purchase counts (`Previous Purchases`) between subscribed (`Yes`) and non-subscribed (`No`) shoppers.
 Shipping & Payment Preferences : Evaluated customer preference across shipping speeds (`Express`, `Free Shipping`, `Next Day Air`, `Store Pickup`) and digital payment methods (`Venmo`, `PayPal`, `Credit Card`, `Debit Card`).
