# Sales Performance and Customer Insights

## Project Overview

The **Sales Performance and Customer Insights** project analyzes e-commerce sales data from January 2024 to January 2026 to evaluate business performance and understand customer purchasing behavior.

The project uses Python, Pandas, Matplotlib, and Streamlit to clean, process, analyze, and visualize sales data.

## Project Objectives

- Analyze overall sales and revenue performance.
- Identify the highest-performing products and categories.
- Examine geographical sales distribution.
- Understand customer spending patterns.
- Identify repeat and new customer contributions.
- Present the results through data visualizations and an interactive dashboard developed using Streamlit.

## Tools and Technologies

- **Python** – Data analysis and processing
- **Pandas** – Data cleaning and manipulation
- **Matplotlib** – Data visualization
- **Streamlit** – Interactive dashboard development
- **Jupyter Notebook** – Data analysis and documentation

## Repository Contents

- `notebooks/` – Jupyter Notebook containing the data analysis and calculations.
- `data/` – Cleaned customer, product, order, and order item datasets.
- `charts/` – Five generated data visualizations.
- `Executive Summary.txt` – Summary of the project's major findings.
- `One-Page Insights Summary.pdf` – One-page presentation of the key business insights.

## Key Findings

- **Total Calculated Revenue:** ₱9,237,598.93
- **Total Unique Orders:** 14,701
- **Average Order Value:** ₱628.37
- **Highest-Revenue Category:** Electronics (₱1,282,129.54)
- **Second-Highest-Revenue Category:** Toys (₱1,255,350.95)
- **Highest-Revenue Product:** KidJoy Toys 607 (₱40,445.79)
- **Highest-Revenue City:** Olongapo (₱591,334.47)
- **Repeat Customer Revenue:** ₱8,742,510.71 (94.64%)
- **New Customer Revenue:** ₱495,088.23 (5.36%)
- **Highest Monthly Revenue:** October 2024 (₱405,778.61)
- **Lowest Monthly Revenue:** February 2025 (₱336,527.87)

## Data Visualizations

The project includes five visualizations generated using Matplotlib:

1. Monthly Revenue Trend
2. Top 10 Products by Revenue
3. Revenue by City
4. Revenue by Product Category
5. Customer Spending Distribution

An interactive dashboard was also developed using Streamlit to present and explore the sales analysis results.

## Data Cleaning and Preparation

The datasets underwent several preparation steps:

- Removed duplicate records.
- Standardized product categories.
- Removed records with zero quantities.
- Converted purchase prices into numeric values.
- Handled missing discount and shipping fee values.
- Standardized date formats.
- Removed records with missing purchase prices and unmatched relationships.
- Integrated customer, product, order, and order item datasets.

## Important Note

The calculated revenue includes all retained transaction records, regardless of order status. Therefore, the revenue figures should not be interpreted as completed-order revenue only.

## Conclusion

The analysis provides insights into sales performance, product contributions, geographical distribution, and customer purchasing behavior. These findings can support better marketing strategies, customer retention, inventory planning, and business decision-making.