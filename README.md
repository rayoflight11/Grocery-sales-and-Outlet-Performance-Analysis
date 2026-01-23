# Grocery-sales-and-Outlet-Performance-Analysis
### Project Overview
This project analyzes grocery sales data to uncover insights on product performance, outlet efficiency, and key factors influencing sales. The analysis was conducted using Power BI with interactive dashboards and business-focused KPIs.

### Business Problem
Grocery business generate large volumes of sales data across products and outlets but often lack clear visibility into what drives revenue and performance. Without actionable insights, it becomes challenging to optimize inventory, product assortment, and outlet strategy.
This project aims to transform grocery sales data into meaningful insights that help identify top-performing products, effective outlet types, examine sales trends based on outlet establishment year and key drivers of sales.

### Data Sources
The dataset used in this project contains grocery retail data with the following key informations:
-	Item details: item identifier, item type, item fat content, item visibility, item weight.
-	Outlet details: outlet identifier, outlet type, outlet size, outlet location type, outlet establishment year.
-	Performance metrics: sales and customer ratings.

### Data Cleaning and Transformation
Power Query (Power BI) was used to prepare the dataset for analysis by :
- Standardizing categorical fields (e.g item fat content).
- Correcting data types for numeric and date fields.
- Removing duplicates and unnecessary columns.
### Data Modeling
- Proper relationships established in the table.
- Fact table containing sales and ratings.
-	Dimension attributes for items and outlets.
### Dax Measures Created
Created measures using DAX for KPIs like:
 -  Total sales.
 - Average sales per outlet.
 - Number of items sold.
 - Established hierarchy for outlet establishment year.

### Dashboard Design and Visuals
The dashboard was designed with a clean, business-focused layout and includes:
- Created KPIs cards for high-level performance metrics
- Used bar and column charts for product and outlet comparison
- Line charts for trend analysis
- Stacked visuals to compare sales by fat content across outlet types
- Built interactive slicers funtionality

