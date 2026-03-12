## Sales Analytics Dashboard – Power BI
## Project Overview

This project presents an interactive Sales Analytics Dashboard built using Power BI to analyze retail sales performance and extract actionable business insights. The dashboard tracks key performance indicators such as total sales, profit, profit margin, year-over-year growth, and regional contribution.

The dataset is directly imported into Power BI, and analytical metrics are created using DAX measures to support dynamic business analysis.

The dashboard enables stakeholders to:
- Monitor overall sales performance
- Analyze profitability
- Track year-over-year growth trends
- Identify top-performing products
- Understand regional sales contributions

## Business Objective
The objective of this project is to design a data-driven sales performance monitoring system that helps business decision-makers:

- Evaluate revenue and profitability
- Identify top-performing products
- Analyze regional sales distribution
- Monitor year-to-date and yearly growth
- Track average selling price trends

## Dataset Information
The dataset used in this project contains retail sales transaction data including:

- Date of transaction
- Product name
- Category
- Quantity sold
- Sales amount
- Cost
- Region

From these fields, multiple business metrics and KPIs were derived using DAX.

---

## Key KPIs & Metrics

The dashboard includes the following analytical measures:

| KPI | Description |
|-----|-------------|
| Total Sales | Total revenue generated |
| Total Units Sold | Total quantity sold |
| Profit | Sales minus cost |
| Profit Margin % | Profitability percentage |
| Average Selling Price | Average price per unit |
| Current Year Sales | Total sales for current year |
| Last Year Sales | Sales from previous year |
| YoY Growth % | Year-over-year sales growth |
| YTD Sales | Year-to-date revenue |
| Region Profit Contribution % | Profit contribution by region |
| Top Product | Product generating highest sales |
| Last Refresh | Dashboard refresh timestamp |

---

## DAX Measures Used

The project uses several Power BI DAX functions including:

- CALCULATE()
- DIVIDE()
- SUM()
- FILTER()
- ALL()
- DATESYTD()
- SAMEPERIODLASTYEAR()
- YEAR()
- FORMAT()
- NOW()

These functions enable dynamic time intelligence calculations and KPI analysis.

---

## Dashboard Features

Key visualizations included in the dashboard:

- Sales trend over time
- Region-wise sales analysis
- Product performance comparison
- Profitability insights
- Year-over-Year growth analysis
- KPI summary cards for business metrics

Interactive filters allow users to analyze data by:

- Region
- Product
- Category
- Time period

---

## Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Power BI | Data visualization and dashboard development |
| DAX | Analytical calculations and KPI creation |
| Power Query | Data transformation |
| Excel / CSV Dataset | Source data |

---

## Project Workflow

- Import sales dataset into Power BI.
- Perform basic data cleaning and transformation.
- Create calculated DAX measures for KPIs.
- Build interactive visualizations and dashboard layout.
- Implement filters and slicers for dynamic analysis.
- Publish insights through an interactive dashboard.

---

## Insights Generated

The dashboard helps identify:

- High revenue generating products
- Regional profit contribution
- Year-over-year sales trends
- Profitability patterns across product categories
- Average selling price variations

These insights support data-driven decision making for sales strategy.

---

## Repository Contents

```
Sales-Analytics-Dashboard
│
├── SalesDashboard.pbix
├── dataset.csv
├── dashboard_screenshot.png
└── README.md
```

---

## Future Improvements

Potential enhancements for this project include:

- Integration with cloud data warehouses
- Automated data refresh pipelines
- Advanced forecasting models
- Customer segmentation analysis

---

## Author

Hemavalli

⭐ If you found this project useful, consider giving it a star!

