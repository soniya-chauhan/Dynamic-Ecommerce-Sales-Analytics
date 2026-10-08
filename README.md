# Dynamic-Ecommerce-Sales-Analytics
End-to-end e-commerce sales analytics using Python, Pandas, MySQL, Power BI and DAX.

 Project Workflow

1. Load Data

Raw CSV files are loaded into Python using Pandas.

2. Data Cleaning & Validation

The datasets are checked for:

- Missing values
- Duplicate records
- Unique IDs
- Data types
- Date validity
- Numeric values
- Negative/zero values where applicable

3. Python ETL

Reusable Python scripts perform data cleaning, validation, and ETL before loading the datasets into MySQL.

CSV Files
   ↓
Python + Pandas
   ↓
Cleaning & Validation
   ↓
ETL
   ↓
MySQL

4. SQL Analysis

SQL queries are used in MySQL to analyze:

- Revenue and orders
- Average Order Value
- Product and category performance
- Customer segments
- Country performance
- Payment methods
- Refunds
- Monthly revenue trends

5. Power BI Dashboard

The MySQL data is connected to Power BI to create an interactive, refreshable dashboard using DAX measures and business-focused visualizations.

6. Business Insights

The dashboard is used to identify important trends and insights related to:
- Revenue
- Products
- Customers
- Payments
- Refunds

The analysis showed that the business generated about $63.5 million in revenue from 97,024 non-cancelled orders, with consumers contributing the majority of revenue.
The US was the strongest market, while apparel was the top revenue-generating category.I also identified a 5.34% refund rate and over 8,000 failed payment attempts,
which could be investigated further to identify operational and revenue-loss opportunities.

