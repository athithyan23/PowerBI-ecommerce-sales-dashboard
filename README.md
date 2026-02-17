# E-Commerce Sales Dashboard (Power BI)

## Project Overview
This project is an *E-Commerce Sales Analysis Dashboard* built using Microsoft Power BI.  
The dashboard provides key insights such as *Sales, Profit, Orders, Customers, and performance trends across **Category, Segment, and Region*.

## Key Insights in Dashboard
  Total Sales  
  Total Profit  
  Total Orders  
  Total Customers  
  Monthly Sales Trend  
  Sales by Category  
  Profit by Sub-Category  
  Sales by Segment  
  Sales by Region  

## Tools & Technologies Used
- Power BI
- DAX (Measures)
- CSV Dataset
- Data Cleaning & Data Modeling

## DAX Measures Used
```DAX
Total Sales = SUM(superstore_india_sample_v2[Sales])

Total Profit = SUM(superstore_india_sample_v2[Profit])

Total Orders = DISTINCTCOUNT(superstore_india_sample_v2[Order ID])

Total Customers = DISTINCTCOUNT(superstore_india_sample_v2[Customer ID])
