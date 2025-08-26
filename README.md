# 📊 Superstore Sales & Returns Analysis


## 📌 Project Overview

This project analyzes the Superstore dataset using Python (EDA & cleaning) and Tableau (dashboarding).
The aim was to uncover sales trends, regional performance, product profitability, and return impacts to generate actionable business insights.

### 🔧 Tools & Technologies

- Python (Pandas, Matplotlib) – for data cleaning, transformation, and preliminary visualization.
- Tableau – for creating interactive dashboards.
- Excel/CSV – initial dataset storage and export and also, to get the overview of the data before working on it.

### 📂 Project Workflow

#### Data Cleaning (Python)
- Handled missing values and formatted columns.
- Broke down Order Date column into month and year seperately.
- Replaced NaN values in returns column with "No".
- Merged sales, people, and returns datasets into a final dataset.
- Dropped unimportant and duplicate rows and columns
- And a few more things

#### Exploratory Data Analysis (EDA)

- Shape of Data: ~50K+ rows × 31 columns (Orders), plus Returns & People sheets.
- Missing Values: Large nulls in Postal Code; critical fields like Order ID, Dates, Sales were clean. Missing values in Returned were filled with "No".
- Duplicates: Duplicate Order IDs detected and removed.
- Data Types: Converted Order Date & Ship Date to datetime. Created Order Month Name for trend analysis.
- Summary Stats: Sales varied widely; profits included negative values (losses). Most orders were small (1–5 items).
- Key Insight: Returns were clustered in specific categories; strong regional differences in sales and profit.

#### Visualization (Python & Tableau)

- Created 2–3 initial charts in Python for exploration.
- Built a Tableau dashboard with 5 detailed charts and 2 filters.

### 📊 Key Insights

- Seasonality: Sales peak in December (~1.6M) and drop to the least in February (~0.54M).
- Regional Sales: Central region leads (~2.7M), while Oceania & SE Asia underperform.
- Product Sub-Categories: Phones, Chairs, and Copiers dominate sales.
- Profitability: North America & Russia are strong; other regions face margin challenges.
- Returns: Technology (~307K) has the highest returns, impacting profitability.

### 🚀 Recommendations

- Inventory Planning: Stock up for end of year demands; run clearance sales in slow months.
- Regional Expansion: Improve distribution & marketing in underperforming regions.
- Product Strategy: Bundle low-performing categories with top sellers.
- Return Management: Enhance product quality checks, descriptions, and offer replacements instead of refunds.

### 📑 Project Files

- Global Superstore_raw and final_superstore → Raw and cleaned datasets.
- python_scripts → Python EDA, cleaning scripts and visualizations.
- Tableau-dashboard-superstore → Tableau Dashboard.
- Analysis Report → Project documentation .

### 🏆 Conclusion

This project demonstrates how Python + Tableau can be combined to generate meaningful business insights from raw sales data. The findings highlight areas for seasonal sales optimization, regional growth, profitability improvement, and return reduction.
