# Strategic Business Data Analysis & Insights

## Overview
This repository contains a comprehensive data-driven analysis focused on deriving actionable business insights from distributed sales and order datasets. The project investigates profitability structures, target achievement metrics, and regional performance trends to provide data-backed strategic recommendations.

## Analysis Objectives
The primary objective of this project is to analyze the dataset to address key business performance questions across three core domains:

### 1. Sales and Profitability Analysis
* **Data Integration:** Merged `List of Orders` and `Order Details` datasets via unique transaction identifiers.
* **Metric Calculation:** Determined total gross sales (Amount) for each product category across the full order history.
* **Profitability Assessment:** Computed average profit per order and total profit margin percentages per category to identify high-margin vs. high-volume segments.
* **performance Benchmarking:** Identified top-performing and underperforming categories with potential drivers for variances in performance.

### 2. Target Achievement Trends
* **Variance Analysis:** Utilized the `Sales Target` dataset to calculate month-over-month percentage changes in performance against expectations.
* **Trend Identification:** Pinpointed specific months and categories (specifically within the *Furniture* segment) exhibiting significant target fluctuations.
* **Strategy Development:** Developed data-aligned strategies for better reconciling target expectations with historical performance trajectories.

### 3. Regional Performance & Optimization
* **Geographical Mapping:** Analyzed distribution data to identify the top 5 states by order volume.
* **Regional Financials:** calculated total sales and average profit metrics for high-volume regions.
* **Opportunity Identification:** Highlighted regional disparities and identified specific underperforming urban centers for targeted business improvement and growth.

## Dataset Structure
The analysis utilizes a consolidated dataset (`jar_insights.xlsx`) containing the following schemas:
* **Transaction Records**: Granular order details including geographical metadata, dates, and customer information.
* **Product Financials**: Line-item details including category classifications, sales amounts, and profit margins.
* **Enterprise Targets**: Defined monthly growth and sales targets across primary business categories.

## Technical Implementation
* **Data Engineering:** Microsoft Excel (Advanced Functions, Pivot Table Analysis, VLOOKUP/XLOOKUP)
* **Analytical Modeling:** Comparative trend analysis and margin distribution modeling.
* **Visualization:** Performance dashboards and strategic charts for trend communication.

## Key Insights
* **Category Efficiency:** Identified segments with high volume but low margin, suggesting a need for price restructuring.
* **Regional Disparities:** Discovered specific states with high order volume but negative average profit due to logistical variables.
* **Forecasting Accuracy:** Normalized target expectations based on seasonal fluctuation trends identified in the historical data.

## Getting Started
1. **Repository Access:**
   ```bash
   git clone https://github.com/AaradhyaTodkar/jar_insights.git
   ```
2. **Reviewing Analysis:**
   Open `jar_insights.xlsx` to explore the underlying data model, calculation sheets, and visualization dashboards.

