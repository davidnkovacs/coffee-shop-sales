# Coffee Shop Sales Analysis Dashboard

## Project Overview

This project involves analyzing sales data for a fictional coffee shop located in New York City. The goal was to transform raw transaction data into an interactive dashboard that provides actionable insights into sales performance, customer behavior, and product trends.

## Key Insights & Objectives

The primary objective was to answer critical business questions:

* **Revenue Trends:** How do sales fluctuate by month, day, and hour?
* **Product Performance:** Which product categories and specific items drive the most revenue?
* **Operational Efficiency:** What are the peak hours of operation, and how does foot traffic vary across different store locations?

---

## Tools Used

* **Microsoft Excel**
* **Power Query:** For data cleaning, transformation, and ETL processes.
* **DAX (Data Analysis Expressions):** To create calculated measures for Year-to-Date (YTD) sales and month-over-month growth.
* **Data Visualization:** Utilizing pivot tables, slicers, and advanced charting techniques.

---

## Data Dictionary

The dataset contains over 149,000 rows of transaction data, including:

* **Transaction Date/Time:** Used to analyze temporal patterns.
* **Transaction Qty:** To calculate total volume.
* **Store Location:** Lower Manhattan, Hell's Kitchen, and Astoria.
* **Product Details:** Category (Coffee, Tea, Bakery, etc.), Type, and Unit Price.

---

## Step-by-Step Process

### 1. Data Cleaning & Transformation

* Connected to the raw CSV data using **Power Query**.
* Standardized date and time formats.
* Added custom columns for **Revenue** () and extracted Date features (Month, Day of Week, Hour).

### 2. Data Modeling

* Created a calendar table to allow for seamless time-series analysis.
* Established relationships between transaction tables and product lookup tables.

### 3. Dashboard Development

* **Dynamic Slicers:** Allowed users to filter by month and location.
* **Heatmaps:** Created a "Sales by Day and Hour" matrix to identify peak staffing needs.
* **Top 10 Analysis:** Visualized the highest-performing products to optimize inventory.

---

## Final Conclusions

* **Peak Performance:** Sales peaked during the morning rush (7:00 AM – 10:00 AM), suggesting a need for maximum staffing during these hours.
* **Top Category:** Coffee and Tea account for the majority of transactions, but Bakery items have a higher attachment rate during weekends.
* **Growth Opportunity:** Identifying low-performing hours in specific locations to implement "Happy Hour" promotions.

---

## How to View

1. Download the `.xlsx` file from this repository.
2. Open using **Microsoft Excel**.
3. Use the interactive slicers on the left-hand panel to explore the data.
