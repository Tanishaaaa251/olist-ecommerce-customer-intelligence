# AI-Assisted E-Commerce Sales & Customer Intelligence

## Project Overview
This project analyses the Brazilian E-Commerce Public Dataset by Olist to understand sales performance and customer behaviour. It combines SQL-based business analysis, customer segmentation using K-means, and Power BI visualisation to derive insights from e-commerce data.

## Objectives
- Analyse sales performance and order trends.
- Understand customer purchasing behaviour.
- Identify customer segments based on behavioural patterns.
- Present key insights through interactive Power BI dashboards.

## Tools & Technologies
- **MySQL:** Data validation, querying, joins, and business analysis.
- **Python:** Customer-level data preparation and analysis.
- **Power BI:** Dashboard development and data visualisation.
- **DAX:** Dynamic measures and KPI calculations.

## Project Workflow
1. **Data Validation:** Examined and validated the relevant dataset tables and fields.
2. **SQL Analysis:** Used joins, aggregations, and analytical queries to explore sales and customer behaviour.
3. **Customer Feature Generation:** Generated customer-level Recency, Frequency, and Monetary features using SQL.
4. **Customer Segmentation:** Applied K-Means clustering in Python to group customers based on their purchasing behaviour.
5. **Dashboard Development:** Built Power BI dashboards to present sales performance and customer insights using DAX measures.

## Dashboard Overview

The dashboard consists of two sections:

### 1. Executive Sales Overview
Presents key performance indicators and visualisations related to sales, orders, order value, and delivery time.

### 2. Customer Intelligence
Presents customer-type distribution and customer segmentation insights.

Dashboard screenshots are available in this repository.

## Key DAX Measures
- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Average Delivery Days

*Note: Total Revenue is calculated using product price and freight value.*

## Dataset
The project uses the **Brazilian E-Commerce Public Dataset by Olist**.

[View Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Conclusion
This project demonstrates an end-to-end analytical workflow, combining SQL, Python, machine learning, and Power BI to explore e-commerce sales performance and customer behaviour.
