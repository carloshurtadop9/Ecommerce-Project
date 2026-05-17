# E-Commerce Sales Performance Analysis

## Project Overview:
This project analyzes E-commerce business performance based on data collected from 2022 to 2024. The project focuses on exploring revenue drivers, discount performance, and revenue and volume trends over time. The analyses were conducted utilizing SQL to merge datasets and basic data cleanup, and Python for Exploratory Data Analysis (EDA), feature engineering, and visualization. 

## Business questions:
1. Which regions and categories drive the most revenue?
2. What products or categories benefit most from discounts?
3. How do revenue and order volume trend over time?

## Key Findings:

1. Electronics dominated revenue performance
2. Discount effectiveness varies by category
3. Revenue shifts were not fully explained by volume changes

## Tools Used: 
- PostgreSQL: Building/querying a relational database workflow
- SQL: Dataset Querying and table joins/cleanup
- Pandas: EDA and feature engineering
- Matplotlib: Visualizations 
- Jupyter Notebooks: Project structuring and documenting

## Dataset Information:
- customers.csv: customer-level data
- products.csv: product-level data
- orders.csv: order-level data
- order_items.csv: line-item detail
- payments.csv: payment record per order

## Notes:
- Synthetic but realistic.
- Includes a small amount of messy data for cleaning practice:
  * some missing values
  * inconsistent category casing
  * trailing spaces in some region values
