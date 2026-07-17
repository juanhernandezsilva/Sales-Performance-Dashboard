# Sales Performance Dashboard | Power BI

**Business Case:** TodoUno S.A. (Uruguay)


# Project Overview

This project presents an interactive **Sales Performance Dashboard** developed in **Power BI** for **TodoUno S.A.**, a fictional retail company operating in Uruguay.

The company specializes in three main product categories:

- Electronics
- Furniture
- Office Supplies

The objective of this project is to analyze the company's commercial performance between **2021 and 2024** by transforming transactional data into meaningful business insights through interactive visualizations and executive KPIs.

The dashboard was designed to simulate a management reporting solution, helping decision-makers monitor sales performance, identify profitable business segments, evaluate regional results, and support strategic decision-making.


# Business Objectives

The dashboard answers the following business questions:


## Sales Performance

- How much revenue has the company generated?
- What is the total profit?
- What is the company's profit margin?
- How many units have been sold?
- What is the average order value?


## Product Performance

- Which product categories generate the highest sales?
- Which categories generate the highest profit?
- Which subcategories underperform?
- Which products require greater commercial attention?


## Geographic Analysis

- Which departments generate the highest sales?
- How does each department compare with the others?


## Payment Analysis

- Which payment methods are preferred by customers?
- What percentage of total sales belongs to each payment method?


## Time Analysis

- How has revenue evolved between 2021 and 2024?
- What is the year-over-year growth trend?


# Dashboard Features

The dashboard includes:

- Executive KPI cards
- Sales trend analysis
- Department sales comparison
- Product category and subcategory analysis
- Payment method distribution
- Interactive matrix with drill-down capabilities

Dynamic filtering is available by:

- Year
- Category
- Department

All visuals interact dynamically, allowing users to explore the data from different business perspectives.


# Data Model

The dashboard follows a **Star Schema**, improving model performance and simplifying analytical calculations.

| Table | Type | Description |
|-------|------|-------------|
| FactSales | Fact | Sales transactions including revenue, profit, quantity and orders |
| DimCustomer | Dimension | Customer information |
| DimProduct | Dimension | Product categories and subcategories |
| DimGeography | Dimension | Departments and cities |
| DimDate | Dimension | Calendar table used for time intelligence |
| DimPaymentMethod | Dimension | Payment methods |


# Data Preparation

The original dataset was cleaned, transformed and standardized before building the analytical model.

During the preparation stage:

- Column names were translated into English.
- Business terminology was standardized.
- The dataset was adapted to represent a fictional Uruguayan retail company.
- Additional fields were created to support business analysis and KPI calculations.

The final analytical model was implemented using a Star Schema structure in Power BI.


# Key Performance Indicators (KPIs)

The dashboard monitors the company's main business metrics:

- Total Sales
- Total Profit
- Profit Margin
- Units Sold
- Average Order Value

Additional DAX measures were developed to analyze:

- Category contribution
- Department contribution
- Payment method contribution
- Product ranking
- Subcategory ranking
- Year-over-Year Growth


# Key Business Insights

The analysis reveals several valuable business findings:

- **Electronics** generated the highest sales revenue but achieved the lowest profit margin among the three categories.

- **Furniture** combined high revenue with strong profitability, making it one of the company's most valuable business segments.

- **Office Supplies** represented the smallest share of total revenue while delivering the highest profit margin, suggesting an opportunity for future expansion.

- Geographic analysis allows management to identify the highest-performing departments and compare regional performance.

- Payment method analysis helps understand customer purchasing preferences and sales distribution.


# Skills Demonstrated

This project demonstrates practical experience in:

- Power BI Dashboard Development
- Data Modeling (Star Schema)
- Data Cleaning
- Power Query
- DAX Calculations
- KPI Design
- Business Analysis
- Executive Reporting
- Data Visualization
- Time Intelligence
- Interactive Dashboard Design


# Tools & Technologies

## Power BI Desktop

- Data Modeling
- Power Query
- DAX
- Interactive Dashboards


## Microsoft Excel

- Initial data source review
- Data validation


# Dataset

The dataset was adapted from the **Sample Superstore** dataset and redesigned to simulate a retail company operating in Uruguay.

The model includes information related to:

- Sales transactions
- Products
- Customers
- Departments
- Payment methods
- Calendar

All monetary values are expressed in **Uruguayan Pesos (UYU)**.


# About the Project

This project showcases my ability to transform raw business data into an interactive analytical solution using Power BI.

The focus was not only on building visualizations but also on creating a business-oriented dashboard capable of supporting commercial decision-making through data.


# Author

**Juan Hernández Silva**

Junior Data Analyst

**LinkedIn:** www.linkedin.com/in/juanhernandezsilva

**GitHub:** github.com/juanhernandezsilva
