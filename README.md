# Home_Sales
 
## Introduction

This repository contains the solution for the Home Sales SparkSQL challenge. The challenge involves using PySpark and SparkSQL to analyze home sales data, create temporary views, partition data, cache and uncache temporary tables, and perform various queries to extract key metrics.

## Instructions

1. **Environment Setup in Google Colab:**
   - Open the `Home_Sales.ipynb` notebook in Google Colab.
   - Ensure you have the necessary libraries installed by running the first cell, which installs PySpark in Colab.

2. **File Structure:**
   - Ensure that the repository follows the following structure:
     ```
     /Home_Sales
         |-- Home_Sales.ipynb
         |-- home_sales_revised.csv
     ```

3. **Importing Necessary Libraries:**
   - The notebook begins by importing the required PySpark SQL functions.

## Completed Tasks
1. Importing Necessary Packages and Creating a SparkSession
2. Reading Data and Creating a Temporary View
3. SparkSQL Queries
   - Average price for a four-bedroom house sold in each year
   - Average price of a home for each year it was built with three bedrooms and three bathrooms
   - Average price of a home for each year with specific criteria
   - "View" rating for homes costing more than or equal to $350,000
4. Caching and Uncaching
5. Partitioning Data and Creating a Temporary Table for Parquet Data
6. Running Queries on Parquet Data and Comparing Runtimes
   
# References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
