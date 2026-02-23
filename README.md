# Ecommerce-SQL-Python-Analytics
End-to-end data analytics project combining SQL and Python to analyze large-scale e-commerce data. Includes database creation, data import automation, advanced SQL querying, window functions, and data visualization for business insights.

=================================

Project Overview

This project analyzes a real-world e-commerce dataset containing approximately 100,000 orders from 2016–2018.

The objective was to simulate a professional analytics workflow by:

Importing large CSV datasets into MySQL using Python

Performing business-driven SQL analysis

Converting query outputs into Pandas DataFrames

Creating visualizations using Python

The project demonstrates how SQL and Python can be integrated for scalable data analysis.

Dataset

Source: Kaggle – Brazilian E-commerce Dataset

Includes multiple relational tables:

Customers

Orders

Order Items

Payments

Products

Sellers

Geo Location

The dataset represents a real-world multi-table relational e-commerce database.

Tools & Technologies

MySQL – Database creation and SQL querying
Python – Data import, query execution, analysis
Pandas – Data manipulation
mysql-connector-python – SQL connection
Matplotlib – Data visualization
Seaborn – Advanced visualization

Work Performed
4.1 Database Setup & Data Import

Created ecommerce database in MySQL

Designed tables matching CSV schema

Used Python scripts to import multiple CSV files

Automated data dumping process

Verified successful import of ~100,000 records

4.2 Basic SQL Analysis

Performed foundational queries such as:

Listing unique customer cities

Counting orders placed in specific years

Counting customers per state

Calculating percentage of installment payments

4.3 Intermediate SQL Analysis

Monthly order trends

Average products per order by city

Revenue contribution by product category

Correlation analysis between product price and purchase frequency

4.4 Advanced SQL Analysis

Used window functions and advanced techniques including:

Moving averages of customer order values

Cumulative monthly and yearly sales

Year-over-year growth rate of revenue

Seller ranking using DENSE_RANK()

Top 3 sellers per year by revenue

4.5 Python Data Processing & Visualization

Executed SQL queries through Python

Converted query results into Pandas DataFrames

Created bar charts for:

Customer distribution by state

Orders by month

Revenue by category

Top sellers by revenue

Applied formatting techniques for better clarity

Avoided misleading visual types (e.g., pie charts for large categories)

Key Insights

Majority of orders were paid in installments, reflecting customer payment behavior.

Product price and purchase frequency show neutral correlation.

Revenue growth trends vary across years.

Seller ranking highlights top revenue contributors annually.

SQL window functions enable deeper behavioral and performance analysis.

Business Impact

This project demonstrates how businesses can:

Monitor sales growth trends

Identify top-performing sellers

Understand customer payment preferences

Evaluate product category revenue contribution

Perform advanced customer behavior analysis

It showcases the integration of database systems and Python analytics for scalable business intelligence.

Outcome

Delivered a complete SQL-Python integrated analytics solution.

Successfully handled large relational datasets, executed advanced SQL logic, and translated results into meaningful visual insights.

Author

Ishant Behwal
