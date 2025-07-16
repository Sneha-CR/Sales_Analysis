# 🧠 SQL Sales_Data Analysis Project: Customer, Product & Sales Insights
## 📌 Project Overview
This SQL-based project is a comprehensive exploratory and advanced data analysis of a retail sales database. The goal is to extract valuable business insights from customer, product, and sales data using structured SQL queries. This project mimics real-world scenarios where analysts must dig through large volumes of data to generate actionable business intelligence.

## 🗂️ Dataset Description
The analysis is performed on a simulated retail database containing the following tables:

gold.fact_sales – Sales transaction data
![Dataset](data_set/gold.fact_sales.csv)

gold.dim_customers – Customer demographic details
![Dataset](data_set/gold.dim_customers.csv)

gold.dim_products – Product catalog and pricing details
![Dataset](data_set/gold.dim_products.csv)

Each table follows a star schema structure typically used in data warehousing systems.

## 🎯 Objectives
This project is structured in stages, each aiming to answer key business questions using SQL:

Database Exploration

Dimension Analysis

Time & Date Exploration

Key Measures & Metrics

Magnitude Comparisons

Top-N & Bottom-N Rankings

Time Series Trends

Cumulative Metrics

Performance Benchmarking

Part-to-Whole Contribution

Data Segmentation

Reporting Views for Business Use

## 🔍 Step-by-Step Analysis
✅ Step 1: Database Exploration
Extract metadata from INFORMATION_SCHEMA

Discover available tables and columns

✅ Step 2: Dimension Analysis
Explore unique values in countries, categories, products

Understand grouping and segmentation for future analysis

✅ Step 3: Date Exploration
Identify earliest & latest order dates

Calculate the total sales range in years

Find youngest and oldest customers by birthdate

✅ Step 4: Business Measures
Total sales, quantity sold, average price

Number of unique orders, products, and active customers

Generate a consolidated business summary report

✅ Step 5: Magnitude Comparisons
Customers by country and gender

Products by category

Revenue contribution by category and customer

✅ Step 6: Ranking
Top 5 best-selling products

Bottom 5 underperforming products

Top 10 revenue-generating customers

Customers with fewest orders

✅ Step 7: Change Over Time
Monthly sales, customer acquisition, and quantity sold

Identify seasonality and sales trends

✅ Step 8: Cumulative Analysis
Year-wise cumulative sales and moving averages

Track business growth year-over-year

✅ Step 9: Performance Analysis
Compare current product sales to:

Historical average

Previous year’s performance

Label as Above/Below Average or Improving/Declining

✅ Step 10: Part-to-Whole Contribution
What percent of total revenue is contributed by each category

✅ Step 11: Segmentation
Group products into cost ranges (e.g., <100, 100–500, >1000)

Count of products in each segment
![Document]()

## 📊 Reporting Views
Two SQL views were created for reuse in dashboards or automated reporting:

## 🧾 gold.report_customers
Includes segmentation by age group, order history, and recency

Classifies customers into segments: VIP, Regular, New
![Customer_report]()

## 📦 gold.report_products
Segments products as High, Mid, or Low Performance

Calculates average selling price, total sales, and customer reach
![Product_report]()

## 🛠️ Tools Used
Tool	Purpose
SQL Server	Query execution and views
GitHub	Project versioning & sharing
Markdown	Documentation

