Intermediate-Assessment
Power BI Sales Analysis Dashboard
 Project Overview

This project focuses on analyzing sales data using Microsoft Power BI. The goal is to clean and transform raw sales data, create meaningful visualizations, and generate insights into regional sales performance, product orders, and profit trends.

 Project Objectives

- Clean and prepare raw sales data.
- Handle missing values and remove duplicate records.
- Analyze order distribution across different regions.
- Identify the top 5 products by number of orders.
- Visualize profit trends over time.
- Create calculated tables, calculated columns, and measures using DAX.

 Tools & Technologies

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- CSV Dataset

**File:** `SalesData_1000Rows_WithIssues.csv`

The dataset contains sales transaction information, including:

- Order ID
- Order Date
- Customer Name
- Region
- Product
- Category
- Unit Price
- Sales
- Cost
- Profit

 Data Cleaning & Transformation

Data preparation was performed using Power Query Editor.

The following steps were completed:

1. Imported the CSV dataset into Power BI.
2. Handled missing text values by replacing them with "Unknown".
3. Handled missing numeric values by replacing them with 0.
4. Removed records with missing Order Dates.
5. Removed duplicate rows.
6. Standardized the OrderDate column to the Date data type.
7. Loaded the cleaned data into the Power BI data model.

Dashboard Visualizations

The dashboard includes three main visualizations:
 Order Distribution by Region
- Visualization: Pie Chart
- Displays the distribution of orders across different regions.
Top 5 Products by Number of Orders
- Visualization: Column Chart
- Identifies the five most frequently ordered products.
 Profit Trend Over Time
- Visualization: Line Chart
- Shows how profit changes over time.
DAX Calculations
Calculated Table – EastRegionOrders

Filters the original sales table to display only orders from the East region.
Calculates the difference between Profit and Cost for each row.
Calculates the total profit

Through this project, I gained practical experience in:

- Data cleaning and transformation using Power Query.
- Creating interactive dashboards in Power BI.
- Designing pie, column, and line charts.
- Applying DAX formulas.
- Creating calculated tables, calculated columns, and measures.
- Analyzing sales and profit-related data.
