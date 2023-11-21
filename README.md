# Home_Sales
Project Overview
This project involves analyzing home sales data using PySpark, focusing on performing various data manipulations and answering specific queries utilizing SparkSQL. The dataset used for analysis is contained in the home_sales_revised.csv file.

Project Instructions
1. File Renaming and Initial Setup
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.
Import the necessary PySpark SQL functions required for this assignment.
2. Reading Data and Creating Temporary Table
Read the home_sales_revised.csv data into a Spark DataFrame.
Create a temporary table called home_sales using the Spark DataFrame.
3. Answering Questions with SparkSQL
Question 1: Calculate the average price for a four-bedroom house sold for each year, rounded off to two decimal places.
Question 2: Determine the average price of a home for each year it was built that has three bedrooms and three bathrooms, rounded off to two decimal places.
Question 3: Find the average price of a home for each year that meets specific criteria (3 bedrooms, 3 bathrooms, 2 floors, and area >= 2,000 square feet), rounded off to two decimal places.
Question 4: Retrieve the "view" rating for homes priced at $350,000 or more. Calculate the runtime for this query, rounded off to two decimal places.
4. Caching Data
Cache the temporary table home_sales.
Check whether the home_sales temporary table is cached.
5. Cached Data Analysis
Utilize the cached data to execute the query filtering view ratings with an average price >= $350,000. Determine the runtime and compare it with uncached runtime.
6. Partitioning and Parquet Data
Partition the formatted parquet home sales data by the "date_built" field.
Create a temporary table for the parquet data.
7. Query Analysis on Parquet Data
Run the query filtering view ratings with an average price >= $350,000 using the parquet data. Calculate the runtime and compare it with uncached runtime.
8. Uncaching Data
Uncache the home_sales temporary table.
Verify that the home_sales temporary table is uncached using PySpark.

