# Task 6 – Sales Trend Analysis Using SQL

##  Objective
The goal of this task was to analyze monthly sales trends using SQL. Specifically, we calculated monthly revenue and the number of unique orders from a sales dataset.

##  Dataset Overview
We used a table named Transactions with the following columns:
- Transaction_ID
- order_date
- Product_Category
- Product_Name
- Units_Sold
- Unit_Price
- Total_Revenue
- Region
- Payment_Method


##  Tools Used
- Oracle SQL (SQL*Plus)
- GitHub 

## What I Did
- Created the Transactions table
- Inserted sales data (with corrected SQL syntax for Oracle)
- Wrote a SQL query to:
  - Extract month and year from order_date
  - Sum Total_Revenue for each month
  - Count distinct `Transaction_ID`s
  - Group and sort results by year and month


## Key Concepts Used
- EXTRACT(YEAR FROM ...) and EXTRACT(MONTH FROM ...)
- SUM() and COUNT(DISTINCT ...)
- GROUP BY and ORDER BY
  
