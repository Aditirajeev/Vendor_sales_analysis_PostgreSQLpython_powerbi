# Vendor_sales_analysis_PostgreSQLpython_powerbi

Brief One Line Summary

End-to-end vendor sales analysis project using PostgreSQL, Jupyter Notebooks, and Power BI for actionable business insights.

Overview

This project analyzes vendor sales data to understand vendor performance, sales contribution, and stock turnover. It integrates PostgreSQL queries, Python notebooks for data wrangling, and Power BI dashboards to provide decision-making insights.

Problem Statement

Organizations often struggle to pinpoint vendors with low turnover and excess stock. Manual analysis delays insights, impacting inventory allocation and vendor negotiations.

Dataset

Vendor sales summary dataset (CSV/DB extract).

Key fields:

VendorName

PurchaseContribution%

StockTurnover

SalesValue

InventoryDetails

Tools and Technologies

Python (Jupyter Notebook) → Data wrangling & preprocessing (vendor.ipynb)

PostgreSQL → SQL queries & data extraction (postgres.ipynb)

Power BI → Interactive dashboard & reporting

Log files → Execution logs for debugging and reproducibility

Methods

SQL queries to filter & aggregate vendor-level data

Python for EDA, data cleaning, and transformations

DAX & Power BI visuals for performance dashboards

Key Insights

Top 10 vendors contribute to majority of purchases

Low turnover vendors identified as risk for overstock

Clear mapping of vendor contribution vs. efficiency

Dashboard/Model/Output

📊 Power BI Dashboard: Interactive filters, Top 10 Vendor Contribution Donut Chart, KPIs

📓 Notebooks:

vendor.ipynb → Data wrangling and analysis

postgres.ipynb → SQL queries and outputs

📝 Logs: Execution and error logs for reproducibility
