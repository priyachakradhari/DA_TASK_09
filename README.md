# Retail and Warehouse Performance Analysis

## Project Overview

This project presents a comprehensive analysis of retail and warehouse sales data to derive actionable business insights. The analysis focuses on evaluating performance over time, identifying top and underperforming suppliers and products, and measuring profitability across different sales channels. The project integrates SQL for data querying, Python for data exploration and validation, and Tableau for interactive data visualization and reporting.

---

## Problem Statement

Analyze retail and warehouse performance over time, identify top and underperforming suppliers and items, evaluate profitability, and generate business insights using SQL, Python, and Tableau.

This project aims to address key business questions, such as:
- Which suppliers are consistently high performers, and which are underperforming?
- What trends exist in retail and warehouse sales over time?
- Which items and item types are most profitable?
- How do retail transfers impact overall performance?
- What decisions can be made to optimize supply chain and sales strategy?

---

## Dataset Structure

The dataset includes transactional and dimensional data across the following fields:

### Time Dimension
- `YEAR`: The calendar year of the transaction
- `MONTH`: The calendar month of the transaction

### Supplier Dimension
- `SUPPLIER`: The name or code of the supplier providing the items

### Product Dimension
- `ITEM CODE`: Unique identifier for each item
- `ITEM DESCRIPTION`: Descriptive label of the item
- `ITEM TYPE`: Categorization of the item (e.g., electronics, furniture, etc.)

### Measures (Sales Channels)
- `RETAIL SALES`: Sales revenue generated from retail operations
- `RETAIL TRANSFERS`: Internal transfers between retail units
- `WAREHOUSE SALES`: Sales revenue from warehouse distribution

---

## Objectives

- Analyze performance trends across time (monthly/yearly)
- Rank suppliers based on contribution to revenue and consistency
- Highlight underperforming items to support discontinuation decisions
- Evaluate the distribution of sales across retail and warehouse channels
- Measure the impact of internal transfers on overall profitability
- Present insights in an accessible and interactive format for stakeholders

---

## Tools and Technologies

- **SQL**: Used to extract, clean, and summarize the data through advanced querying techniques including aggregations, groupings, filtering, and joins.
- **Python (Pandas, Matplotlib, Seaborn)**: Used for exploratory data analysis (EDA), validation of SQL logic, and generating intermediate plots to support Tableau dashboards.
- **Tableau**: Used to design and publish dashboards that summarize key metrics and trends for business users and stakeholders.

---

