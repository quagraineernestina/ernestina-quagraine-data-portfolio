# Project 01: Sales & Inventory Analysis – KOPPA Style Footwear Business

## Overview
This project analyses sales and inventory data for a Ghana-based footwear business (inspired by real operational challenges). The goal is to identify sales performance patterns, detect stock issues, and provide practical recommendations for better inventory and sales management.

## Business Context
The analysis mirrors real situations faced in retail footwear operations in Ghana, including multiple branches, product categories, stock movements, and the need to balance sales performance with healthy stock levels.

## Objectives
- Analyse sales performance by branch, region, and product category
- Identify monthly sales trends
- Detect low stock situations and branches with weak inventory levels
- Provide clear, actionable business recommendations

## Tools Used
- Python (pandas, matplotlib, seaborn)
- Google Colab
- Jupyter Notebook

## Dataset
Synthetic but realistic dataset of 1,200 transactions with the following fields:
- Date, Branch, Region
- Product Category, Product Name, Size, Colour
- Quantity Sold, Unit Price (GHS), Total Sales (GHS)
- Quantity in Stock, Stock Movement
- Payment Method, Customer Type

## Key Insights
1. Cape Coast and Tema were the top-performing branches by total sales.
2. Greater Accra was the strongest region overall.
3. Sports Shoes generated the highest revenue among all product categories.
4. Monthly sales were mixed, with a noticeable decline in July 2025.
5. Kumasi recorded the lowest average stock levels.
6. Multiple low-stock situations (below 15 pairs) were identified across branches and categories.

## Recommendations
1. Review and improve stock replenishment processes in Kumasi to reduce stockout risk.
2. Increase focus on Sports Shoes, the highest-performing category, across all branches.
3. Investigate the sales decline in July 2025 to understand root causes (seasonality, stock availability, or competition).
4. Consider redistributing slow-moving stock from high-stock branches to low-stock locations.
5. Implement simple reorder alerts when stock falls below 15 pairs.

## Project Files
- `01_sales_inventory_analysis.ipynb` – Full analysis notebook
- `koppa_sales_inventory_data.csv` – Dataset used
- Charts: Sales by Branch, Sales by Category, Monthly Sales Trend

## How to Run
1. Open the notebook in Google Colab or Jupyter.
2. Run all cells.
