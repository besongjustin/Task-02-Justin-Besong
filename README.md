 **Sales Performance & Insights — Data Analytics Project**
 
**Author: Besong Justin | Internship: DecodeLabs Data Analytics Programme**

 **Project 2:** Exploratory Data Analysis (EDA) — Microsoft Excel

**Goal**
Analyse the dataset to understand patterns, trends, and distributions using Excel formulas.

**What Was Done**

**Basic Statistics**
- Calculated Mean, Median and Count for key numeric columns (TotalPrice, UnitPrice, Quantity, ItemsInCart) using `AVERAGE()`, `MEDIAN()`, and `COUNTA()` functions

**Trends Analysis**
The following trends were calculated using `SUMIF()` and `COUNTIF()` formulas on a dedicated **EDA SUMMARY** sheet:

- Orders by Month
- Revenue by Month
- Revenue by Year
- Revenue by Product
- Average Order Value by Product
- Top Selling Products by Order Count
- Revenue by Referral Source
- Order Status Breakdown

**Outlier Detection**
Outliers were identified using the **IQR (Interquartile Range) method**:
- Q1 and Q3 calculated using `QUARTILE()`
- IQR = Q3 − Q1
- Lower Bound = Q1 − (1.5 × IQR)
- Upper Bound = Q3 + (1.5 × IQR)
- Outlier count identified using `COUNTIF()` with boundary conditions
- Products with outlier orders identified using `COUNTIFS()`

**Key Findings**
- June had the highest order volume (147 orders); September the lowest (73)
- 2023 generated the most revenue ($552K)
- Chair and Printer led product revenue (~$196K each)
- Instagram was the top referral source (~$275K revenue)
- **41.42%** of orders were Cancelled or Returned — a critical finding
- 8 outlier orders detected across Laptop, Monitor, Tablet, Chair and Printer

**Author:**
**Besong Justin**
- LinkedIn: [linkedin.com/in/besong-justin](https://www.linkedin.com/in/justinbesong/)
- Twitter/X: [@Justin_analyst](https://twitter.com/Justin_analyst)
