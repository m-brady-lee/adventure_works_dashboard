ADVENTUREWORKS KPI & QA DASHBOARD

An interactive Power BI dashboard built on the AdventureWorks dataset to analyze sales performance, customer behavior, product trends, and return metrics. Designed to support KPI monitoring, quality assurance analysis, and operational audit workflows using a clean dimensional data model and advanced DAX calculations.

OBJECTIVE

To design a business-ready analytics dashboard that enables stakeholders to monitor revenue, profit, orders, returns, and customer performance while supporting quality assurance, trend analysis, and data-driven decision-making.

KEY QUESTIONS ANSWERED

How are revenue, profit, orders, and returns trending over time?

Which regions and countries generate the highest order volume?

Which product categories and subcategories drive the most sales?

Which customers contribute the most revenue?

Where are return rates highest, and how do they impact profitability?

How do pricing adjustments affect profit performance?

DATA MODEL

A star-schema–based dimensional model built for performance, clarity, and auditability.

Fact Tables

Sales Data

Returns Data

Dimension Tables

Calendar Lookup

Customer Lookup

Product Lookup

Product Subcategories Lookup

Product Categories Lookup

Territory Lookup

Relationships were designed to support accurate aggregation, drill-down analysis, and consistent KPI calculation across all visuals.

DATA PREPARATION

Imported and validated structured sales and returns data

Standardized date fields using a dedicated calendar table

Ensured referential integrity across fact and dimension tables

Modeled territory, customer, and product hierarchies to enable multi-level analysis

Verified grain consistency to prevent double-counting in KPIs

ANALYSIS & ENGINEERING

Authored complex DAX measures to calculate:

Total Revenue

Profit and Adjusted Profit

Orders and Return Rates

Revenue per Customer

Month-over-Month and Year-over-Year trends

Implemented KPI targets and variance indicators

Built logic to support interactive pricing adjustment scenarios

Designed calculations to support QA checks and operational review use cases

DASHBOARD FEATURES
Executive Dashboard

High-level KPIs: Revenue, Profit, Orders, Return Rate

Revenue and order trends with contextual tooltips

Top products by revenue and return percentage

Monthly performance snapshots with comparisons

Geographic Analysis

Interactive world map showing orders by country and region

Region-level filtering (North America, Europe, Pacific)

Visual emphasis on volume concentration and regional performance

Product Performance

Product-level KPIs with target comparisons

Monthly orders, revenue, and profit vs. targets

Interactive price adjustment control to simulate margin impact

Return rate monitoring by product

Customer Analysis

Total and unique customer tracking

Revenue per customer trends

Top 100 customers ranked by revenue

Customer segmentation by income level and occupation

Advanced Analytics

Decomposition Tree for root-cause analysis of total orders

Key Influencers to identify drivers of performance

Dynamic tooltips and calculation groups for flexible metric selection

KEY INSIGHTS

Revenue and profit showed sustained upward trends with seasonal variability

A small number of product categories accounted for a large share of total orders

Certain high-revenue products also exhibited elevated return rates, signaling QA risk

Revenue per customer increased steadily over time, indicating improved customer value

Geographic concentration revealed regional dependencies that could impact risk exposure

TOOLS & TECHNOLOGY

BI Tool: Power BI

Database: SQL Server

Modeling: Star schema (fact/dimension design)

Analysis: DAX, calculated measures, calculation groups

Visualization: KPI cards, maps, decomposition tree, key influencers

SKILLS DEMONSTRATED

KPI design and performance tracking

Data modeling and dimensional schema design

DAX-based analytical logic

QA and audit-support analytics

Business storytelling through dashboards

Translating raw data into actionable insights

SCREENSHOTS
Executive Dashboard

Geographic Analysis

Data Model

Decomposition Tree

Customer Detail

Product Detail

NOTES ON DATA USAGE

This project uses sample AdventureWorks data. No proprietary, sensitive, or personally identifiable information is included.

FUTURE IMPROVEMENTS

Add automated data quality checks and anomaly detection

Incorporate forecasted KPIs and scenario modeling

Expand QA metrics for returns and fulfillment accuracy

Add role-based dashboard views for executives vs. analysts

AUTHOR

Michael Lee
📧 m.brady.lee@gmail.com

Project Date: 12/2024
