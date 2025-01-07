# Adidas Sales Dashboard
## Preview

![Dashboard Preview](Image/Dashboard%204.png)

## Introduction
This project aims to analyze Adidas product sales data in the United States (USA) region. The dataset used, Adidas US Sales Dataset, was sourced from Kaggle and published by Heemali Chaudhari in 2023. The analysis produced four key insights:
- Monthly Sales
- Sales by State
- Sales by Sales Method
- Retail Sales
## Dataset Overview
The dataset contains 9,648 rows with 13 main columns, as follows:
- **Retailer**: Name of the retailer
- **Retailer ID**: Unique identifier for each retailer
- **Invoice Date**: Date of the sales transaction
- **Region, State, City**: Geographical details of sales
- **Product**: Type of Adidas product sold
- **Price per Unit**: Unit price of the product
- **Units Sold**: Quantity of products sold
- **Total Sales**: Gross sales revenue
- **Operating Profit**: Profit generated from operations
- **Operating Margin**: Percentage of profit relative to total sales
- **Sales Method**: Method of sales (Online, On-Site and Retail)

Preprocessing was conducted to ensure the data was ready for visualization in Tableau. The key steps included:

1. Converting raw data into CSV format for structured analysis.
2. Standardizing financial columns by removing dollar ($) symbols to ensure consistency.
3. Transforming key columns, such as "Price per Unit" and "Operating Profit," from string to integer formats to enable accurate numerical calculations.

This preprocessing phase was a critical foundation for effective analysis and dashboard development.

## Tools Used
- Microsoft Excel: Used for data preprocessing.
- Tableau: Used for data analysis and creating interactive visualizations.

## Feature
The interactive dashboard is equipped with filters based on:
- Product
- Region
- Year

These features make it easier for users to explore and interpret the analysis results.

## Key Findings
- In 2021, sales coverage expanded from 9 states in 2020 to over 50 states.
- This expansion significantly contributed to increased sales values, particularly in Sales by Method and Sales by Retail categories.
