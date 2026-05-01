# Business Intelligence Sales Dashboard

End-to-end data analysis project using SQL, Python, and Power BI.

---

## Overview

This project demonstrates a complete data analysis workflow, transforming raw sales data into actionable business insights.

It covers the full lifecycle of a data analysis project — from data cleaning and transformation to visualization and business reporting. SQL queries were written and executed within a Python notebook as part of the data preparation process.

This project simulates a real-world business intelligence workflow used by analysts to support decision-making.

---

## Tech Stack

* SQL (executed within Python notebook using Pandas workflow)
* Python (Pandas for data cleaning and feature engineering)
* Power BI (dashboard development and visualization)

---

## Project Structure

* data/ → raw and cleaned datasets
* notebooks/ → data cleaning, transformation, and SQL queries
* dashboards/ → Power BI dashboard file (.pbix)
* images/ → dashboard screenshots

---

## Dashboard Features

* KPI tracking:

  * Revenue: $2.3M
  * Profit: $286K
  * Profit Margin: 12.03%
  * Total Orders: 5,009

* Monthly sales trend analysis

* Sales comparison by category

* Top-performing products using Top N filtering

* Region-based filtering using slicers

---

## Key Insights

* Sales increase toward the end of the year
* Technology category generates the highest revenue
* A small group of products contributes a large portion of total sales
* Profit margin remains stable at around 12%

---

## Dashboard Preview

![Sales Dashboard](images/dashboard.png)

---

## Business Use Case

This dashboard enables stakeholders to:

* Monitor business performance in real time
* Identify high-performing products and categories
* Analyze seasonal trends
* Make data-driven decisions efficiently

---

## Notes

All SQL queries used in this project are included within the Jupyter notebook:
notebooks/sales_analysis.ipynb
