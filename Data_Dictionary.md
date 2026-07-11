# 📚 Data Dictionary

This document describes the fields used in the **Financial Performance Dashboard** dataset.

---

# Dataset Overview

The dataset contains transactional financial data for the years **2024–2025** and is designed for Business Intelligence and Power BI reporting.

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| Date | Date | Transaction date used for time-based analysis. |
| Year | Whole Number | Year of the transaction (2024 or 2025). |
| Month | Text | Month name of the transaction (January, February, etc.). |
| Month Year | Text | Month-Year combination used for chronological reporting (e.g., Jan 2024). |
| Region | Text | Geographic region where the transaction occurred (North, South, East, West). |
| Customer Segment | Text | Customer classification (Consumer, Corporate, Home Office). |
| Product Category | Text | High-level product classification (Electronics, Furniture, Office Supplies). |
| Product | Text | Individual product name. |
| Quantity | Whole Number | Number of units sold in a transaction. |
| Revenue | Decimal Number | Total revenue generated from the transaction. |
| Cost | Decimal Number | Total cost associated with the transaction. |
| Profit | Decimal Number | Profit earned from the transaction (Revenue − Cost). |
| Budget | Decimal Number | Planned or budgeted revenue for comparison. |
| Discount | Decimal Number | Discount percentage applied to the transaction. |
| Transaction ID | Text | Unique identifier for each transaction. |

---

# Calculated Measures (DAX)

The dashboard uses several custom DAX measures.

| Measure | Description |
|---------|-------------|
| Total Revenue | Sum of all revenue values. |
| Total Profit | Sum of all profit values. |
| Total Cost | Sum of all costs. |
| Total Budget | Sum of budget values. |
| Profit Margin % | Profit expressed as a percentage of revenue. |
| Budget Variance | Difference between actual revenue and budget. |
| Revenue per Transaction | Average revenue generated per transaction. |
| Profit per Transaction | Average profit generated per transaction. |
| Average Discount % | Average discount percentage across transactions. |
| Total Quantity | Total quantity sold. |
| Total Transactions | Count of all transactions. |

---

# Data Model

The dashboard uses a simple star schema consisting of:

- **FactFinancial** (Fact Table)
- **DimDate** (Date Dimension)

The **FactFinancial** table stores transactional business data, while **DimDate** enables time intelligence calculations and chronological analysis.

---

# Dashboard Usage

The dataset supports analysis across:

- Revenue Performance
- Profitability Analysis
- Budget vs Actual Comparison
- Regional Performance
- Product Analysis
- Customer Segment Analysis
- Financial KPIs
- Business Insights

---

# Notes

- This dataset was created for educational and portfolio purposes.
- All values are synthetic and intended to demonstrate Power BI reporting, DAX calculations, and dashboard design techniques.
