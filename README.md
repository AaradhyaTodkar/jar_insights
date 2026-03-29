# Jar Insights - Business Analyst Intern Assignment

## Overview
This repository contains the analysis and solutions for the Jar assignment. The project focuses on deriving actionable business insights from sales and order datasets. It investigates profitability, target achievements, and regional performance to provide strategic recommendations for business improvement.

## Problem Statement
The primary objective of this project is to analyze the provided dataset to answer key business questions across three main areas:

### Part 1: Sales and Profitability Analysis
* **Data Integration:** Merged `List of Orders` and `Order Details` datasets using Order ID.
* **Sales Calculation:** Calculated total sales (Amount) for each product category across all orders.
* **Profitability Metrics:** Computed the average profit per order and total profit margin (profit as a percentage of total sales amount) for each category.
* **Performance Identification:** Identified top-performing and underperforming categories based on the calculated metrics and provided strategic reasoning for the performance differences.

### Part 2: Target Achievement Analysis
* **Target Fluctuation:** Analyzed the `Sales Target` dataset to calculate the month-over-month percentage change in target sales specifically for the *Furniture* category.
* **Trend Analysis:** Identified months with significant target fluctuations.
* **Strategic Alignment:** Suggested actionable strategies for better aligning future target expectations with actual historical performance trends.

### Part 3: Regional Performance Insights
* **Top States:** Analyzed the `List of Orders` dataset to precisely identify the top 5 states with the highest overall order counts.
* **Regional Metrics:** Calculated total sales and average profit for each of these top 5 states.
* **Disparity Highlighting:** Highlighted regional disparities across sales and profitability.
* **Growth Priorities:** Suggested specific underperforming but high-potential regions and cities to prioritize for future growth and improvement.

## Dataset Description
The analysis utilizes a provided dataset (included in this repository as `jar_insights.xlsx`) comprising multiple specific tables:
* **List of Orders**: Contains high-level details about individual orders, including geographical data (state/city), order dates, and customer details.
* **Order Details**: Includes specific line-items per order, corresponding sales amounts, profits, and product categories.
* **Sales Target**: Contains monthly sales target expectations segmented by different product categories.

## Tools and Technologies 
* **Data Analysis & Cleaning:** Microsoft Excel (Pivot Tables, Functions, VLOOKUP/XLOOKUP) / Python (Pandas)
* **Data Visualization:** Charts and visual summaries for trend analysis and data presentation.

## Key Insights & Takeaways
*(Note to author: Update this section with your actual findings before sending it to recruiters!)*
* **Example Insight:** Category X has the highest volume but the lowest profit margin, indicating a potential supply chain inefficiency.
* **Example Insight:** Month Y showed a massive dip in target achievement due to over-forecasting.
* **Example Insight:** State Z processes the highest orders but yields negative average profit, highlighting the need for revised pricing or shipping structures in that area.

## How to View and Run This Project
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/jar-insights.git
   ```
2. Navigate to the project directory:
   ```bash
   cd jar-insights
   ```
3. Open the `jar_insights.xlsx` file using Microsoft Excel, Google Sheets, or any compatible spreadsheet software to view the raw data, merged tables, and analytical calculations. (If Python was used, explore the included `.ipynb` or `.py` files in the environment).
