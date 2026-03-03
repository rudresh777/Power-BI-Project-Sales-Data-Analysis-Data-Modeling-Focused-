📊 Power BI Sales Data Analysis (Data Modeling Focused)

📌 Project Overview

This project presents an end-to-end Sales Data Analysis solution using Power BI, focusing on:

Data Modeling (Star Schema)

Data Cleaning & Transformation (Power Query)

DAX Measures

KPI Analysis

Business Insights

The dashboard provides insights into Sales, Profit, Discounts, Promotions, Product Performance, and Regional Trends.
---------------------------------------------------------------------------------------------------------------------------------------------------
🎯 Business Problem

The objective of this project is to analyze sales performance across:

Cities

Products

Promotions

Time periods

And identify:

Top & Bottom Performing Products

Impact of Discounts

Profit vs Net Sales Relationship

Sales Trends Over Time
----------------------------------------------------------------------------------------------------------------------------------------------------------
🏗 Data Modeling (Star Schema)

This project implements a Star Schema Model consisting of:

Fact Table:

Sales Transactions

Units Sold

Net Sales

Profit

Discount Values

Dimension Tables:

Dim Product

Dim Customers

Dim Promotion

Relationships:

One-to-Many between Dimension and Fact tables

Optimized for analytical queries

📷 Model View:

(Add: data_model.png)
------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔄 Data Cleaning & Transformation (Power Query)

Performed:

Merged Queries

Expanded Dimension Tables

Removed Unnecessary Columns

Renamed Columns

Changed Data Types

Replaced Null Values

Added Custom Columns

📷 Power Query Steps:

(Add: power_query_steps.png)
------------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Dashboard Features
1️⃣ Sales by City (Geographical Analysis)

Map Visualization

Regional Sales Distribution

2️⃣ KPI Cards

Total Orders

Total Sales

Total Profit

Total Quantity Sold

3️⃣ Promotion Analysis

Average Discount by Promotion Category

Impact on Sales

4️⃣ Profit vs Net Sales Scatter Plot

Shows correlation between Profit & Sales

5️⃣ Sales Trends by Year

Year-wise Sales Performance (2020–2024)

6️⃣ Top & Bottom Products Analysis

Top 5 by Sales

Bottom 5 by Sales

Top 5 by Profit

Bottom 5 by Profit

Top 5 by Quantity

Bottom 5 by Quantity
-------------------------------------------------------------------------------------------------------------------
🧮 DAX Measures Used

Total Sales = SUM(Fact[Total Sales])

Total Profit = SUM(Fact[Profit])

Total Quantity = SUM(Fact[Units Sold])

Net Sales = SUM(Fact[Net Sales])

Discount Percentage Calculations

Year-wise Aggregations
-------------------------------------------------------------------------------------------------------------------------------
📊 Key Insights

Strong positive correlation between Profit and Net Sales.

Certain promotional categories drive higher discount averages.

Few products generate majority of revenue (Pareto principle).

Sales peak observed in 2023 before sharp decline in 2024.

Bottom products have high discounts but low profitability.
----------------------------------------------------------------------------------------------------------------------------------------
🛠 Tools & Technologies Used

Power BI

Power Query

DAX

Data Modeling (Star Schema)

Excel (Data Source)
---------------------------------------------------------------------------------------------------------------------------------------------
