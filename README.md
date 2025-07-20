# 📊 Jumia Sales Analysis – Excel Project

## Overview

This project explores sales data from Jumia, one of Africa's leading e-commerce platforms, with a specific focus on understanding the relationship between **discounts**, **product ratings**, and **sales performance**. The primary question was:

**Do discounts and ratings influence product sales?**

Using Excel, I performed a full data analysis pipeline — from cleaning and exploration to dashboard creation — to derive actionable insights.

---

## Objectives

- Analyze the impact of **discount percentages** on sales.
- Examine how **customer ratings** relate to product performance.
- Visualize sales patterns across product categories.
- Build an interactive dashboard for stakeholders to explore the results.

---

## Tools Used

- **Microsoft Excel**
  - Pivot Tables & Charts
  - Data Cleaning (Power Query)
  - Conditional Formatting
  - Formulas & Calculated Fields

---

## Dataset

The dataset includes the following key fields:

- `Product Name`
- `Old Price`, `Current Price`, `Discount (%)`
- `Number of Ratings`, `Rating (out of 5)`
- `Number of Reviews`
- `Units Sold`

*Note: Data is assumed to be collected from a snapshot of the Jumia platform or a shared dataset for educational purposes.*

---

## Analysis Workflow

### 1. Data Cleaning

- **Removed duplicates** and irrelevant columns.
- **Handled missing values** in ratings and review counts using Excel formulas (e.g., `IFERROR`, `ISBLANK`).
- **Converted data types**, e.g., prices and discount fields to numerical.
- **Calculated additional columns**:
  - `Discount Amount = Old Price - Current Price`
  - `Revenue = Units Sold × Current Price`

### 2. Exploratory Data Analysis (EDA)

- Used **Pivot Tables** to explore:
  - Sales performance by category and brand.
  - Average ratings and reviews by product group.
- Created **visualizations** for:
  - Distribution of discounts vs units sold.
  - Ratings vs total revenue.
  - Correlation between review count and sales.

### 3. Key Findings

- Products with higher **ratings** consistently had **higher sales volumes**, even with minimal or no discounts.
- **Heavy discounts** did not show a strong correlation with increased sales, especially for low-rated products.
- A positive **perceived quality** (measured by ratings and reviews) seemed to influence customer buying decisions more than price cuts.

### 4. Dashboard Creation

An interactive Excel dashboard was built using:
- Slicers for category, brand, and rating filters.
- Summary metrics (e.g., Total Revenue, Average Rating).
- Bar and line charts to display trends across dimensions.

![Dashboard](https://github.com/EmmanuelKiriinya/Jumia-Sales-Analysis-Excel-/blob/master/image/Jumia%20Sales%20dashboard.PNG)

---

## Conclusion

The analysis suggests that **customer trust** (reflected in product ratings and reviews) is a stronger sales driver than discounts on the Jumia platform. Businesses may benefit more from improving product quality and encouraging feedback than offering steep discounts.

---

## Next Steps

- Extend the analysis with time series data if available.
- Combine with marketing campaign data to understand external influences.
- Replicate analysis using **Power BI** for broader interactivity.

---

## Author

**Emmanuel Kiriinya**  
Data Analyst | Excel • SQL • Power BI • Python  
[GitHub](https://github.com/EmmanuelKiriinya) | [Email](mailto:emmanuelkiriinya1@yahoo.com)

