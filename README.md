# AdventureWorks Sales Analysis | Power BI

An interactive Power BI report analysing sales performance, product trends, customer behaviour, and returns.

## Project Overview

This project explores business performance using AdventureWorks sales data. The report combines sales, product, customer, and geographical analysis to provide insights into key business metrics and trends.

The project was completed as part of my Power BI learning journey with Maven Analytics, applying data preparation, data modelling, DAX, and visualisation concepts.

## Business Objectives

- Analyse overall sales and profitability.
- Evaluate product and category performance.
- Explore customer purchasing behaviour.
- Compare sales performance across geographical regions.
- Monitor return rates and sales trends.

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modelling

## Dashboard Pages

### 1. Executive Dashboard

Provides an overview of business performance through revenue, profit, orders, return rate, sales trends, product categories, and top-performing products.

![Executive Dashboard](1.%20Exec%20dashboard.png)

### 2. Geographical Analysis

Explores sales performance across geographical regions. Users can select locations to analyse regional business performance.

![Geographical Analysis](2.%20Map.png)

### 3. Product Performance

Analyses product-level orders, revenue, profit, target performance, and profit trends. Includes dynamic metric selection and a price adjustment parameter.

![Product Performance](3.%20Product%20details.png)

### 4. Customer Analysis

Explores customer metrics, revenue per customer, customer segments by income and occupation, top customers, and customer trends.

![Customer Analysis](4.%20Customer%20details.png)

## Data Model

The report uses a relational data model connecting sales and returns data with supporting lookup tables.

**Tables included:**
- Sales Data
- Returns Data
- Calendar Lookup
- Customer Lookup
- Territory Lookup
- Product Lookup
- Product Subcategories Lookup
- Product Categories Lookup
- Measures Table

The model supports analysis across products, customers, territories, and time.

![Data Model](Data%20model%20diagram.png)

## Key Observations

Based on the default report view:

- Revenue is approximately **$24.9M**, with profit of approximately **$10M**.
- The report displays approximately **25.2K orders** and a **2.2% return rate**.
- Bikes contribute the largest share of revenue among the displayed product categories.
- In June 2022, revenue increased by **3.31%**, while orders decreased by **0.88%** compared with the previous month.

These observations reflect the default report view. The interactive dashboard allows users to explore additional results through filters and selections.

## Interactive Features

- Geographical and product-level filtering
- Dynamic metric selection
- Price adjustment parameter
- Year range selection
- Interactive visuals and cross-filtering

## Skills Practised

- Data cleaning and transformation using Power Query
- Data modelling and relationship management
- Creating DAX measures
- KPI development and performance analysis
- Interactive dashboard design
- Business data visualisation

---

**Project Type:** Power BI Analytics  
**Learning Resource:** Maven Analytics
