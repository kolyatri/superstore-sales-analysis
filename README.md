# Superstore Sales Analysis & Power BI Dashboard

A full **end-to-end data analytics project** using **Python** for data cleaning and exploratory analysis, and **Power BI** for interactive dashboards and business reporting.

The goal of this project is to analyze:

- sales performance
- profitability drivers
- customer value
- discount impact

using the **Superstore dataset**.

This project is designed as a **professional portfolio case** focused on business-oriented analytics and clear storytelling.

---

## Project Overview

This project demonstrates a complete analytics workflow:

- Data cleaning and preparation in Python  
- Exploratory Data Analysis (EDA) with statistical summaries and 15+ visualizations  
- Business insights based on real-world KPIs  
- Interactive dashboards built in Power BI  
- Final results packaged in a clean, structured GitHub repository  

---

## Dataset

**Source**
- Sample Superstore dataset (Kaggle)

**Scope**
- Approximately 10,000 orders
- Period: 2014–2017

**Key Columns**
- Sales, Profit, Discount, Quantity
- Category, Sub-Category
- Region, State, Segment
- Order Date, Ship Date

**Additional Fields Created After Cleaning**
- Profit Margin
- Order Year
- Order Month
- Order Month-Year (for time series)
- Shipping Delay (days)

---

## Tools Used

### Python Stack
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### BI / Visualization
- Power BI Desktop

**Key DAX Measures**
- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Profit Margin %
- Average Discount %
- Average Order Value (AOV)

---

## Project Structure

```
superstore-sales-analysis/
├── data/
│   ├── Sample - Superstore.csv
│   └── superstore_clean.csv
│
├── notebooks/
│   └── superstore_analysis.ipynb
│
├── dashboard/
│   ├── superstore_dashboard.pbix
│   └── screenshots/
│       ├── overview_full.png
│       ├── overview_kpis.png
│       ├── overview_profit_by_category.png
│       ├── deepdive_scatter_discount_profit.png
│       └── ...
│
├── outputs/
│   └── state_performance.csv
│
└── README.md
```

This structure mirrors a real-world professional analytics project.


---

## Exploratory Data Analysis (Python)

The EDA covers:

- Sales and profit by category and sub-category
- Regional and state-level performance
- Monthly sales and profit trends
- Discount impact on profitability
- Top 10 customers by profit
- Worst-performing products
- Geographic patterns
- Shipping delay analysis

The notebook includes:

- 12–18 visualizations
- GroupBy aggregation tables
- Business commentary under each analysis section

---

## Power BI Dashboard

### Page 1 — Overview

Includes:

- KPI cards:
  - Total Sales
  - Total Profit
  - Profit Margin %
  - Total Orders
- Profit by Category (bar chart)
- Sales by Sub-Category
- Monthly Sales trend (line chart)
- Sales, Profit, and Profit Margin by State (map)

**Interactive filters**
- Year
- Category
- Region

---

### Page 2 — Deep Dive

Includes:

- Discount vs Profit scatter plot (with trendline)
- Top 10 customers by profit
- Bottom 10 products by profit (most unprofitable)
- Profit margin distribution (histogram)
- Region × Category profit matrix (heatmap)

**Filters**
- Year
- Region
- Category
- Segment

---

## Key Business Insights

- Technology drives the majority of profit, while Furniture contains several loss-making products due to heavy discounting.
- Discounts above 20–30% consistently lead to negative profit, making discounting the primary source of profit erosion.
- A small group of top customers contributes a disproportionate share of total profit, following a strong Pareto (80/20) pattern.
- The Central region underperforms, with the highest concentration of unprofitable sales, while West and East regions lead in profitability.
- Bottom 10 products generate significant losses and require immediate pricing or catalog review.
- Profit margins are heavily skewed, with many orders operating at low or negative margins, indicating opportunities for pricing optimization.

---

## Dashboard Screenshots

Screenshots of the dashboard pages are available in:

dashboard/screenshots/


---

## How to Use This Repository

- Open the Jupyter notebook to review data cleaning and EDA
- Open the Power BI `.pbix` file to explore interactive dashboards
- Review screenshots for a quick visual overview
- Read this README for a concise summary of insights

This structure makes the project easy to evaluate for hiring managers.

---

## What I Learned

- Building production-grade EDA workflows
- Working with date features and time series
- Creating business-focused DAX measures
- Designing professional Power BI dashboards
- Extracting actionable insights from data
- Presenting results clearly to non-technical audiences

---

## Final Deliverables

- Cleaned dataset: `superstore_clean.csv`
- Python notebook: `superstore_analysis.ipynb`
- Interactive Power BI dashboard: `superstore_dashboard.pbix`
- Dashboard screenshots
- Project README

---

## Author

**Mykola Trybushkin**  
Data Analyst / Business Intelligence / Python Analytics  

GitHub: https://github.com/kolyatri  
LinkedIn: https://www.linkedin.com/in/mykola-trybushkin-217a44117/
