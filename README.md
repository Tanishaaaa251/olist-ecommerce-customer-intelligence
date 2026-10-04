# AI-Assisted E-Commerce Sales & Customer Intelligence

## Project Overview
This project analyses the Brazilian E-Commerce Public Dataset by Olist to understand sales performance and customer behaviour. It combines SQL-based business analysis, Python-based customer segmentation, and Power BI visualisation to derive meaningful insights from e-commerce data.

## Objectives
- Analyse sales performance and order trends.
- Understand customer purchasing behaviour.
- Identify customer segments using clustering.
- Present key business insights through Power BI dashboards.

## Tools & Technologies
- **MySQL:** Data validation, joins, aggregations, and business analysis.
- **Python:** Customer-level data preparation and analysis.
- **Scikit-learn:** K-Means clustering.
- **Power BI:** Dashboard development and visualisation.
- **DAX:** Dynamic measures and KPI calculations.

## Project Workflow

1. **Data Validation:** Examined the raw dataset and validated relevant tables and fields.
2. **SQL Analysis:** Used SQL joins, aggregations, and analytical queries to explore sales and customer behaviour.
3. **Customer Feature Generation:** Created customer-level Recency, Frequency, and Monetary features using SQL.
4. **Customer Segmentation:** Applied K-Means clustering in Python to group customers based on their purchasing behaviour.
5. **Dashboard Development:** Created Power BI dashboards to present sales performance and customer insights using DAX measures.

## Dashboard Overview

The Power BI dashboard covers two main areas:

- **Executive Sales Overview:** Key performance indicators and visualisations related to sales, orders, order value, and delivery time.
- **Customer Intelligence:** Customer-type distribution and customer segmentation insights.

Dashboard screenshots are available in the `04_PowerBI` folder.

## Key DAX Measures
- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Average Delivery Days

*Note: Total Revenue is calculated using product price and freight value.*

## Repository Structure

```text
Olist_AI_Project/
│
├── README.md
├── Step1_Cleaned_Data
│   └── Consolidated cleaned and validated dataset
│
├── Step2_SQL
│   └── Final SQL scripts
│
├── Step3_PowerBI
│   └── Dashboard screenshots
│
└── Step4_AI_Analysis
    └── Final Python script for customer segmentation
