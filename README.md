# E-Commerce Sales Performance Dashboard (Power BI)

# Live Dashboard

https://app.powerbi.com/groups/me/reports/6350fa7a-2cf9-42da-ae0a-f84704924195/7586e25c82006bdbe823?experience=power-bi

# Project Overview

In this project, I used Power BI to analyze e-commerce sales data and create an interactive dashboard. The goal was to understand sales performance, product demand, and regional sales trends through clear visualizations and KPIs.

# Data Cleaning (Power Query) 
While working with the dataset, I found some data quality issues that needed cleaning:

* Removed extra characters (;) from sales values so they could be used in calculations.
* Found issues in the Order Date column because some dates were stored in a shortened Hijri format and included null values.
* Instead of focusing on time-based analysis, I shifted the dashboard toward regional and category analysis.
* Removed blank and null values from filters such as Region, Category, and Segment to improve the user experience.

# DAX Measures

Created simple DAX measures to calculate:

* Total Sales
* Total Orders
* Unique Products

# Dashboard Highlights

* KPI cards showing total sales, total orders, and unique products.
* Slicers for filtering data by region and customer segment.
* Bar chart showing top-selling product categories.
* Donut chart showing sales distribution by category.
* Column chart comparing category sales across different regions.

# Key Findings

* Total sales exceeded $2 million.
* Technology was the highest-performing category.
* Phones and Chairs generated the highest sales.
* The West region achieved the strongest sales performance.

# Tools Used

* Power BI Desktop
* Power Query
* DAX
* Power BI Servic
