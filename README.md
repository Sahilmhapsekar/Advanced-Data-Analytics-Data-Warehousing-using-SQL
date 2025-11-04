# Advanced Data Analytics & Data Warehousing using SQL Server

A complete end-to-end data warehouse and business intelligence project built using SQL Server.  
This project demonstrates dimensional modeling, analytical SQL techniques, and the generation of actionable business insights through structured data analysis.

---

## Overview

This project simulates a real-world data analytics pipeline, focusing on:
- Designing a star schema data warehouse with fact and dimension tables  
- Performing exploratory, ranking, and time-series analysis  
- Generating customer and product performance reports  
- Delivering business intelligence insights using advanced SQL features

---

## Objectives

- Build a scalable data warehouse for business reporting  
- Implement ETL-like data ingestion using `BULK INSERT`  
- Use window functions, CTEs, and aggregate queries for analytics  
- Perform customer segmentation, revenue ranking, and trend analysis  
- Extract KPIs for decision-making and business strategy

---

## Data Architecture

**Database:** `DataWarehouseAnalytics`  
**Schema:** `gold`

**Fact Table**
- `fact_sales` – transaction-level details (order_number, product_key, customer_key, sales_amount, quantity, price)

**Dimension Tables**
- `dim_customers` – customer demographics  
- `dim_products` – product catalog and cost details  

---

## Key Analytical Components

1. **Exploratory Data Analysis (EDA)**  
   - Data profiling, date range validation, and sales aggregation  
2. **Magnitude & Ranking Analysis**  
   - Top/bottom product and category performance  
3. **Time-Series Analysis**  
   - Sales trends, moving averages, and cumulative revenue  
4. **Customer & Product Reports**  
   - Lifetime value, segmentation, recency, and performance metrics  
5. **Part-to-Whole Analysis**  
   - Market share and category contribution breakdown  

---

## Technical Implementation

### Core SQL Features
- **Window Functions:** `ROW_NUMBER()`, `RANK()`, `LAG()`, `LEAD()`  
- **CTEs & Views:** Reusable analytical queries for reporting  
- **Aggregate Functions:** `SUM()`, `AVG()`, `COUNT()`  
- **Date Functions:** `DATEDIFF()`, `DATETRUNC()`, `FORMAT()`  
- **CASE Statements:** Customer and product segmentation  
- **BULK INSERT:** CSV data loading and validation  

---

## Business Insights

- Bikes category generates the majority of total revenue  
- US region contributes the highest sales volume  
- Clear VIP, Regular, and New customer tiers based on spending  
- Identified top-performing and underperforming products  
- Established seasonal sales trends and growth benchmarks  

---

## Tools & Technologies

- SQL Server – Database and analytics  
- SSMS – Query development environment

---

## Future Enhancements

- Integrate with Power BI for visualization  
- Automate ETL with SSIS packages  
- Implement real-time analytics using streaming data  
- Extend with machine learning models for demand forecasting  

---

## Author

**Sahil Mhapsekar**  
B.Tech in Mechanical Engineering, IIT Ropar  

---

If you found this project insightful, consider starring the repository.
