# GlobalTech Sales Analysis

## Overview

This project analyzes quarterly sales data using Python and pandas. The
dataset includes product sales across multiple regions, categories, and
promotional conditions.

The script performs data exploration, filtering, aggregation, and
business analysis to generate insights and recommendations.

## Technologies Used

-   Python
-   pandas
-   numpy

## Features

### Data Loading and Exploration

-   Loads dataset from a simulated CSV file
-   Converts date column to datetime format
-   Displays dataset structure, dimensions, and summary statistics

### Column Analysis

-   Selects key columns such as Product, Units, and Total_Sales
-   Calculates total units sold
-   Computes total revenue
-   Determines average unit price

### Data Filtering

-   Filters sales by region (North America)
-   Identifies high-volume sales transactions
-   Extracts promotional sales for specific products
-   Filters data by month (February 2024)

### Advanced Analysis

-   Identifies the top-performing product by revenue
-   Calculates total sales by region
-   Computes average units sold per category
-   Compares performance between promoted and non-promoted sales

### Missing Data Analysis

-   Counts missing values in each column
-   Calculates percentage of missing data

### Business Insights

-   Identifies top-performing categories in each region
-   Calculates average price per category
-   Analyzes revenue contribution by product

## How to Run

1.  Install required libraries: pip install pandas numpy

2.  Run the script: python your_script_name.py

3.  Review the printed analysis and report in the console.

## Output

The script prints: - Dataset overview and statistics - Sales performance
metrics - Regional and category breakdowns - Promotion effectiveness -
Data quality report - Business recommendations

## Key Insights

-   Revenue varies significantly across regions
-   Promotions impact average sales performance
-   Certain products contribute a large share of total revenue
-   Missing data exists in key fields such as Units and Unit_Price

## Recommendations

-   Increase promotions for high-revenue products
-   Focus efforts on top-performing regions
-   Improve data collection processes to reduce missing values

## Notes

-   Dataset is simulated using StringIO
-   No external files are required
-   Script runs end-to-end

## Author

Justin Dixon
