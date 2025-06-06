
# 📊 SQL Data Warehouse Analytics Project — Advanced Analytics Extension

This repository continues from the foundational SQL Data Warehouse project and introduces advanced analytical modules designed to extract deeper business insights from the existing data warehouse. This phase focuses on time-based trends, cumulative KPIs, segmentation logic, and comprehensive reporting views for both customers and products.

---

## 🏗️ 1. Change Over Time Analysis – 01_change_over_time_analysis.sql

Tracks sales trends, growth, and seasonality using multiple time-based aggregation techniques:

- Year-Month aggregation
- `DATETRUNC()` for monthly groupings
- `FORMAT()` for custom date formatting
- Calculates total sales, total customers, and total quantity by period

---

## 📈 2. Cumulative Analysis – 02_cumulative_analysis.sql

Calculates cumulative business performance over time to visualize long-term trends:

- Running totals (`SUM() OVER`)
- Moving averages (`AVG() OVER`)
- Yearly aggregation for sales and pricing trends

---

## 📊 3. Performance Analysis – 03_performance_analysis.sql

Performs detailed benchmarking and year-over-year performance comparison:

- Product sales vs. average sales (above/below average logic)
- Year-over-year (YoY) growth using `LAG()`
- Categorizes performance change as 'Increase', 'Decrease', or 'No Change'

---

## 📂 4. Data Segmentation – 04_data_segmentation.sql

Segments data into meaningful customer and product groups:

- **Product Segmentation:** Based on product cost into 4 brackets
- **Customer Segmentation:** VIP, Regular, and New customers based on spending and customer lifespan

---

## 🍰 5. Part-to-Whole Analysis – 05_part_to_whole_analysis.sql

Evaluates category contribution to overall sales:

- Calculates percentage share of each product category
- Highlights dominant revenue-generating segments

---

## 👥 6. Customer Report – 06_report_customers.sql

Generates a consolidated customer report view with detailed metrics:

- Customer demographics (age groups)
- Purchase behavior (total orders, sales, quantity)
- Customer segmentation logic (VIP, Regular, New)
- Key KPIs: recency, lifespan, average order value, and average monthly spend

---

## 📦 7. Product Report – 07_report_products.sql

Generates a comprehensive product-level report view:

- Product details with category and subcategory
- Performance segmentation: High-Performer, Mid-Range, Low-Performer
- KPIs: total sales, orders, customers, average selling price, recency, AOR, and monthly revenue

---

## 💡 Topics Covered

- Advanced Time-Series Analysis
- Cumulative Metrics & Moving Averages
- Year-over-Year Performance Benchmarking
- Customer and Product Segmentation Logic
- Part-to-Whole Contribution Analysis
- Business-Oriented Reporting Views

---

## 🔧 Requirements

- Microsoft SQL Server
- Management Tool (SQL Server Management Studio — SSMS)
- Phase 1 Database Setup Required (Fact & Dimension tables)

---

## 🧠 Author Notes

This project demonstrates advanced SQL techniques commonly used in business intelligence and analytics. These scripts are ideal for enhancing operational dashboards, executive reporting, or preparing data for BI tools.

---

📌 **Note:** Run scripts sequentially to ensure all reports are created successfully.
