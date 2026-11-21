# Customer & Sales Performance Analytics Dashboard
# Project Overview
This project presents an interactive four-page Power BI dashboard designed to analyze sales performance, customer behaviour, product performance, and order trends.

The dashboard helps users explore business data and identify useful insights through interactive visualizations and slicers.

# Tools & Technologies
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Datasets
- GitHub

# Dataset
The project uses two datasets:

- Customers: Customer ID, name, country, state, city, and score.
- Orders: Order ID, order date, customer ID, product name, product category, quantity, and sales.

# Data Preparation
- Imported customer and order datasets into Power BI.
- Cleaned and transformed data using Power Query.
- Created a relationship between Customers and Orders using Customer ID.
- Created calculated measures using DAX.

# Dashboard Pages
# 1. Sales Overview
- Total Sales
- Total Quantity
- Total Orders
- Total Customers
- Sales by Year and Quarter
- Sales by Product
- Sales by Product Category
- Sales by Country

# 2. Customer Analysis
- Total Customers
- Total Sales
- Average Customer Score
- Top 10 Customers by Sales
- Sales by City
- Customers by Country
- Country, State, and City slicers

# 3. Product Analysis
- Total Sales
- Total Quantity
- Total Orders
- Sales by Product Category
- Sales by Product
- Quantity Sold by Category
- Product Category slicer

# 4. Order Analysis
- Total Orders
- Total Sales
- Average Order Value
- Orders Over Time
- Orders by Product Category
- Sales by Order Date
- Order Date slicer

# Key DAX Measures
--> Total Sales = SUM(Orders[Sales])
--> Total Orders = DISTINCTCOUNT(Orders[Order_ID])
--> Total Customers = DISTINCTCOUNT(Customers[Customer_ID])
--> Total Quantity = SUM(Orders[Quantity])
--> Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)
--> Average Customer Score = AVERAGE(Customers[Score])

# Project Files
- Power BI dashboard (.pbix)
- Customers dataset
- Orders dataset
- Dashboard screenshots

# Key Learnings
-> Data cleaning and transformation using Power Query.
-> Data modelling and table relationships.
-> Creating DAX measures.
-> Designing interactive dashboards.
-> Analysing sales, customer, product, and order performance.

# Conclusion
--> This project demonstrates practical Power BI skills, including data preparation, data modelling, DAX calculations, and interactive        dashboard development.

# Dashboard Preview
1. Sales Overview
   [Sales Overview](01_Sales_Overview.png)

2. Customer Analysis
   [Customer Analysis](02_Customer_Analysis.png)

3. Product Analysis
   [Product Analysis](03_Product_Analysis.png)

4. Order Analysis
   [Order Analysis](04_Order_Analysis.png)

