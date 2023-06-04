# Home_Sales

This repository contains code for analyzing home sales data using PySpark SQL. The analysis focuses on answering various questions about the home sales data using SparkSQL. The main tasks include calculating average prices, filtering data based on specific criteria, caching data for optimization, and comparing query runtimes.

Contents

Home_Sales.ipynb: Jupyter Notebook file containing the code implementation for the home sales analysis.
home_sales_revised.csv: CSV file containing the home sales data.
README.md: This file, providing an overview of the repository.

Analysis Steps

File Renaming: Rename the notebook file from Home_Sales_starter_code.ipynb to Home_Sales.ipynb.
Importing Dependencies: Import the necessary PySpark SQL functions for the analysis.
Data Loading: Read the home sales data from the home_sales_revised.csv file into a Spark DataFrame.
Temporary Table Creation: Create a temporary table called home_sales for easy querying.
Analysis Queries: Use SparkSQL to answer specific questions about the home sales data, such as calculating average prices based on different criteria.
Caching: Cache the home_sales temporary table for faster subsequent queries.
Table Caching Check: Verify if the home_sales temporary table is cached.
Filtered Query with Caching: Run a query using the cached data to filter out specific criteria and compare the runtime with the uncached runtime.
Data Partitioning: Partition the formatted parquet home sales data based on the "date_built" field.
Parquet Data Temporary Table: Create a temporary table for the parquet data.
Filtered Query with Parquet Data: Run a query using the parquet data to filter out specific criteria and compare the runtime with the uncached runtime.
Temporary Table Uncaching: Uncache the home_sales temporary table.
Table Uncaching Verification: Verify that the home_sales temporary table is successfully uncached using PySpark.
Repository Management: Download the Home_Sales.ipynb file and upload it to your "Home_Sales" GitHub repository.


Please refer to the Home_Sales.ipynb notebook for the detailed code implementation and analysis results.