📊 E-Commerce Sales Performance Dashboard — Power BI

📌 Project Overview

This project is an interactive Sales Performance Dashboard developed using Microsoft Power BI.

The dashboard analyzes sales data to provide insights into:

Sales performance,
Profitability,
Order volume,
Regional performance,
Product performance,
Profit trends over time


The project demonstrates the complete data analytics workflow, including data cleaning, transformation, DAX calculations, visualization, interactive filtering, drill-through analysis, and business insights.

🎯 Project Objectives

The main objectives of this project are to:

Clean and transform raw sales data using Power Query
Handle missing values and duplicate records
Standardize date formats and data types
Analyze order distribution across regions
Identify the Top 5 products by order volume
Analyze profit trends over time
Create meaningful KPIs using DAX
Build an interactive multi-page Power BI dashboard
Provide actionable business insights and recommendations
🗂️ Dataset

Dataset: SalesData_1000Rows_WithIssues_copy.csv

The dataset contains sales transaction information, including:

OrderID,
OrderDate,
CustomerName,
Region,	
Product	,
Category,	
Quantity	,
UnitPrice	,
Sales	,
Cost	,
Profit.	

🧹 Data Cleaning & Transformation

Power Query was used to prepare the dataset for analysis.

Cleaning activities included:
Handling missing values
Removing duplicate records
Standardizing OrderDate
Correcting data types
Validating numerical fields
Handling missing Sales, Cost and Profit values
Replacing missing categorical values where appropriate
Data Types
OrderID → Whole Number
OrderDate → Date
CustomerName → Text
Region → Text
Product → Text
Category → Text
Quantity → Whole Number
UnitPrice → Decimal Number
Sales → Decimal Number
Cost → Decimal Number
Profit → Decimal Number

📑 Dashboard Pages
🏠 Page 1 — Executive Overview

The Executive Overview provides a high-level summary of sales performance.

KPIs
Total Orders
Total Sales
Total Quantity
Total Profit
Visualizations
Orders by Region
Top 5 Products by Orders
Profit Trend Over Time
🌍 Page 2 — Regional Analysis

This page provides a detailed view of regional performance.

Analysis includes:
Order distribution by region
Sales by region
Profit by region

📦 Page 3 — Product Analysis

This page focuses on product-level performance.

Analysis includes:
Top 5 Products
Sales by Product
Profit by Product
Quantity by Product

🔎 Page 4 — Product Details

A Drill-through page was created to provide detailed information for a selected product.

Users can:
Select a product from the Product Analysis page
Right-click the product
Select Drill-through → Product Details

The page displays product-specific:

Total Orders
Total Sales
Total Quantity
Total Profit
Sales Trend
Profit Trend
Regional Sales Performance

💡 Page 5 — Insights & Recommendations

The final page converts the dashboard analysis into business-oriented insights.


Users can navigate between:

Executive Overview → Regional Analysis → Product Analysis → Product Details → Insights & Recommendations


Drill-through

Product-level drill-through allows users to move from the Product Analysis page to detailed product information.


🛠️ Tools & Technologies

Microsoft Power BI
Power Query
DAX
CSV Dataset
