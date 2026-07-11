# 📊 Financial Performance Dashboard (Power BI)

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black)

![Dashboard Preview](assets/page1-executive-summary.png)

---

# 📌 Project Overview

The **Financial Performance Dashboard** is an interactive Business Intelligence solution developed in **Microsoft Power BI** to analyze and monitor organizational financial performance.

The dashboard enables users to explore Revenue, Profit, Budget, Profit Margin, Customer Segments, Product Categories, Regional Performance, and Business Insights through dynamic visualizations, KPIs, and interactive filtering.

This project demonstrates practical Business Intelligence skills including **data modeling, Power Query, DAX, KPI development, dashboard design, and analytical storytelling.**

---

# 📑 Table of Contents

- Project Overview
- Dashboard Features
- Dashboard Pages
- Dashboard Preview
- Data Model
- Tech Stack
- Key KPIs
- Visualizations Used
- DAX Measures
- Repository Structure
- Additional Documentation
- Skills Demonstrated
- Business Insights
- Future Enhancements
- Author

---

# 🎯 Dashboard Features

- Executive KPI Dashboard
- Interactive Slicers
- Financial Performance Monitoring
- Revenue vs Budget Analysis
- Profitability Analysis
- Regional Performance Analysis
- Product Category Analysis
- Customer Segment Analysis
- Conditional Formatting
- Advanced Power BI Visuals
- Dynamic Cross Filtering

---

# 📄 Dashboard Pages

## 📈 Executive Summary

A high-level overview of business performance.

### Includes

- Total Revenue
- Total Profit
- Profit Margin
- Budget
- Budget Variance
- Monthly Revenue Performance
- Regional Revenue Distribution
- Product Category Revenue Distribution
- Customer Segment Profit Distribution

---

## 💼 Financial Analysis

Detailed financial reporting and performance comparison.

### Includes

- Revenue versus Budget Analysis
- Product Revenue Contribution (Treemap)
- Regional Profit Analysis
- Financial Performance Summary Matrix
- Revenue per Transaction
- Profit per Transaction
- Conditional Formatting

---

## 🔍 Business Insights

Advanced analytical page designed to identify business drivers.

### Includes

- Profit Driver Analysis (Decomposition Tree)
- Profit Influencing Factors (Key Influencers)
- Revenue versus Profit Analysis (Scatter Chart)
- Regional Performance Trend (Ribbon Chart)

---

# 📊 Dashboard Preview

## Executive Summary

![Executive Summary](assets/page1-executive-summary.png)

---

## Financial Analysis

![Financial Analysis](assets/page2-financial-analysis.png)

---

## Business Insights

![Business Insights](assets/page3-business-insights.png)

---

# 🗂️ Data Model

The dashboard follows a **Star Schema** consisting of:

### Fact Table

- FactFinancial

### Dimension Table

- DimDate

The DimDate table enables chronological reporting and supports DAX time intelligence calculations.

---

# 🛠️ Tech Stack

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset
- GitHub

---

# 📈 Key KPIs

- Total Revenue
- Total Profit
- Total Cost
- Total Budget
- Budget Variance
- Profit Margin %
- Revenue per Transaction
- Profit per Transaction
- Average Discount %
- Total Transactions

---

# 📉 Visualizations Used

- KPI Cards
- Clustered Column Chart
- Line & Clustered Column Chart
- Treemap
- Clustered Bar Chart
- Matrix
- Scatter Chart
- Ribbon Chart
- Decomposition Tree
- Key Influencers
- Slicers

---

# 🧮 DAX Measures

The dashboard contains multiple custom DAX measures including:

- Total Revenue
- Total Profit
- Total Cost
- Total Budget
- Profit Margin %
- Budget Variance
- Revenue per Transaction
- Profit per Transaction
- Average Discount %
- Total Quantity
- Total Transactions

📄 **Complete DAX Documentation:**  
➡️ [DAX_Measures.md](DAX_Measures.md)

---

# 📂 Repository Structure

```
financial-performance-dashboard-powerbi/
│
├── assets/
│   ├── page1-executive-summary.png
│   ├── page2-financial-analysis.png
│   ├── page3-business-insights.png
│   └── dashboard-preview.png
│
├── Financial_Performance_Dashboard.pbix
├── Financial_Dataset.csv
├── README.md
├── DAX_Measures.md
├── Data_Dictionary.md
├── PROJECT_SUMMARY.md
└── LICENSE
```

---

# 📖 Additional Documentation

This repository includes additional project documentation.

| File | Description |
|------|-------------|
| 📘 DAX_Measures.md | Complete list of DAX measures used in the dashboard |
| 📙 Data_Dictionary.md | Description of every dataset column and measure |
| 📗 PROJECT_SUMMARY.md | Project objectives, approach, methodology, and conclusion |

---

# 🚀 Skills Demonstrated

- Business Intelligence
- Dashboard Development
- Data Modeling
- Power Query
- DAX Calculations
- KPI Development
- Financial Reporting
- Interactive Dashboard Design
- Data Visualization
- Analytical Storytelling
- Business Analytics

---

# 📚 Key Business Insights

The dashboard enables users to:

- Monitor overall financial performance.
- Compare actual revenue against planned budget.
- Evaluate regional profitability.
- Analyze product category performance.
- Identify profitable customer segments.
- Understand key drivers influencing profit.
- Explore revenue and profit relationships.
- Track performance trends over time.

---

# 📁 Dataset

This project uses a **synthetic financial dataset** created for portfolio and educational purposes.

The dataset includes:

- Revenue
- Cost
- Profit
- Budget
- Discount
- Quantity
- Product
- Product Category
- Region
- Customer Segment
- Transaction Date

---

# ▶️ How to Use

1. Clone or download this repository.
2. Open **Financial_Performance_Dashboard.pbix** using Microsoft Power BI Desktop.
3. Refresh the dataset if required.
4. Use the slicers to filter the report by:
   - Year
   - Region
   - Product Category
5. Navigate through the three dashboard pages to explore different business insights.

---

# 🔮 Future Enhancements

Potential future improvements include:

- SQL Server integration
- Live database connectivity
- Incremental Refresh
- Forecasting
- Row-Level Security (RLS)
- Drill-through Reports
- Mobile Dashboard Layout
- Power BI Service Deployment

---

# 👨‍💻 Author

**Aakanksh Kumar Marwaha**

- GitHub: https://github.com/AakankshMarwaha
- LinkedIn: https://www.linkedin.com/in/aakanksh-kumar-marwaha-970023412

---

## ⭐ If you found this project interesting, consider giving the repository a star!

Feedback and suggestions are always welcome.
