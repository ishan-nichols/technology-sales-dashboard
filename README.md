# Technology Sales Dashboard

A Power BI dashboard built for executive leadership to monitor company-wide sales performance in one centralized, interactive view. The dashboard replaces fragmented Excel reports with a standardized, scalable analytics solution powered by SQL and Power BI.

---

## Project Overview

Senior leadership at a large technology company struggled to make timely, data-driven decisions because sales data was delivered in inconsistent, messy Excel files from multiple regions. The CEO requested:

1. A standardized SQL database to centralize all sales data.
2. A dynamic dashboard that enables fast filtering, trend analysis, and mobile accessibility.

This project delivers a clean data model and a polished Power BI dashboard that allows executives to instantly explore revenue, sales volume, top products, and top customers across markets and time periods.

---

##  Business Objectives

* Eliminate manual Excel reporting and inconsistencies
* Provide a single source of truth for company sales data
* Enable leadership to:

  * Track revenue and sales quantity
  * Identify top-performing markets, products, and customers
  * Analyze revenue trends over time
  * Access insights from both desktop and mobile devices

---

##  Data Architecture

* **Source:** Company SQL Server
* **Ingestion:** Power BI connected directly to SQL tables
* **Modeling:**

  * Relationships established across fact and dimension tables
  * Proper keys enforced for accurate joins
  * Star-schema style modeling where applicable

---

## Data Cleaning & Transformation

Data preparation was performed inside Power BI to ensure accuracy and usability:

* ✅ Removed duplicate records
* ✅ Filtered out null and invalid values
* ✅ Standardized all currency values into USD
* ✅ Removed one-time / non-recurring markets
* ✅ Verified data types and formatting
* ✅ Validated referential integrity across tables

These steps ensured reliable metrics and consistent reporting across all visuals.

---

## 📈 Dashboard Features

The dashboard provides both high-level KPIs and detailed drill-down capabilities:

### Key Metrics

* Total Revenue
* Sales Quantity
* Revenue Growth Over Time

### Interactive Filters

* Market / Region
* Date Range
* Top 5 Products
* Top 5 Customers

### Visualizations

* Time-series revenue trend chart
* Product and customer performance comparisons
* Market-level breakdowns

### Mobile View

* Optimized layout for mobile devices
* Enables executives to review performance on-the-go

---

## Tools & Technologies

* **SQL Server** – Data storage and relational modeling
* **Power BI** – Data transformation, modeling, and visualization
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculated metrics

---

## How to Use

1. Open the Power BI file.
2. Refresh data to pull the latest records from SQL Server.
3. Use slicers to filter by market, date, product, or customer.
4. Explore trends and KPIs to support executive decision-making.

---

## Future Improvements

* Add forecasting and predictive analytics
* Implement role-based security for regional managers
* Automate refresh scheduling
* Add profitability and margin analysis
* Integrate external market benchmarks

---

## 👤 Author

**Ishan Nichols**
Data Science Student | Analytics & Visualization | SQL | Power BI
