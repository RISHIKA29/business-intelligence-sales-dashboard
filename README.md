# Business Intelligence Sales Dashboard

End-to-end data analysis project using SQL, Python, and Power BI.

---

## Overview
This project analyzes retail sales data to identify revenue drivers, evaluate profitability, and support business decision-making.

The workflow includes data cleaning, transformation, and analysis using Python and SQL, followed by building an interactive Power BI dashboard to track key performance metrics.

---

## Tech Stack

* SQL (executed within Python notebook using Pandas/SQLite workflow)
* Python (Pandas for data cleaning and feature engineering)
* Power BI (dashboard development and visualization)
* Data processing involved handling missing values, removing duplicates, and creating derived features such as profit margin and time-based attributes.

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
- Sales show a consistent upward trend in the final quarter, indicating strong seasonal demand  
- The Technology category contributes the highest share of total revenue  
- A small subset of products generates a disproportionate amount of total sales  
- Higher discount levels are associated with reduced profitability

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
