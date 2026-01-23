# Grocery-sales-and-Outlet-Performance-Analysis
## Table of Content
   - [Project Overview](#project-overview)
   - [Business Problem](#business-problem)
   - [Data Sources](#data-sources)
   - [The Process](#the-process)
### Project Overview
This project analyzes grocery sales data to uncover insights on product performance, outlet efficiency, and key factors influencing sales. The analysis was conducted using Power BI with interactive dashboards and business-focused KPIs.
<img width="1178" height="660" alt="Sales_analysis" src="https://github.com/user-attachments/assets/1c1e5e61-7719-4fc6-8e41-03e7d837b26c" />
<img width="1176" height="662" alt="product and outlets_analysis" src="https://github.com/user-attachments/assets/6317795c-9775-43da-a9b4-54aad446d584" />

### Business Problem
Grocery business generate large volumes of sales data across products and outlets but often lack clear visibility into what drives revenue and performance. Without actionable insights, it becomes challenging to optimize inventory, product assortment, and outlet strategy.
This project aims to transform grocery sales data into meaningful insights that help identify top-performing products, effective outlet types, examine sales trends based on outlet establishment year and key drivers of sales.

### Data Sources
The dataset used in this project contains grocery retail data with the following key informations:
-	Item details: item identifier, item type, item fat content, item visibility, item weight.
-	Outlet details: outlet identifier, outlet type, outlet size, outlet location type, outlet establishment year.
-	Performance metrics: sales and customer ratings.

### The Process
#### 1.Data Cleaning and Transformation
Power Query (Power BI) was used to prepare the dataset for analysis by :
- Standardizing categorical fields (e.g item fat content).
- Correcting data types for numeric and date fields.
- Removing duplicates and unnecessary columns.
#### 2.Data Modeling
- Proper relationships established in the table.
- Fact table containing sales and ratings.
-	Dimension attributes for items and outlets.
#### 3.Dax Measures Created
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

### Key Insights From Dashboard
- Fruits and Vegetables and Snack Food are major revenue contributors
- Low-fat products outperform regular products across most outlet types
- Medium-sized outlets generate the highest total sales
- Tier 3 Outlet locations show higher average sales per outlet
- Older outlets demonstrate more consistent sales performance
#### Detailed Insights Explanation
-	Fruits and Vegetables and Snack Food are major revenue contributors: Among all product categories, fruits and vegetables and snack food generate the highest share of total sales. These items are frequently purchased and appeal to a broad customer base.
-	Low-fat products outperform regular products across most outlet types: Across multiple outlet types, low-fat products consistently record higher sales than regular-fat products. This indicates a strong customer preference for healthier product options.
-	Medium-sized outlets generate the highest total sales: The analysis shows that medium-sized outlets contribute the highest overall sales when compared to small and large outlets. This suggests that medium outlets strike a balance between operational efficiency and customer reach.
-	Tier 3 Outlet locations show higher average sales per outlet: Outlets located in Tier 3 locations record higher average sales per outlet compared to Tier 1 and Tier 2 locations. This suggests stronger individual outlet performance in less saturated markets.
-	Older outlets demonstrate more consistent sales performance: Outlets that were established earlier show more stable and consistent sales patterns compared to newer outlets.
  
### Tools Used
-	Power BI Desktop
-	Power Query (data cleaning and transformation)
-	DAX (KPIs and calculated measures)
  
### Project Deliverables
Interactive dashboard providing insights into grocery sales performance, product attributes, outlet characteristics, customer ratings, and key factors influencing revenue across different outlet types and locations.

### Potential Extentions 
-	Incorporate customer demographic data for deeper analysis
-	Add time-based sales analysis (monthly or quarterly trends)



