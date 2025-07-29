# Retails-Sales-Analysis-project-using-Power-BI
Retail Sales Analysis project in Power BI using star schema with dimension tables (Categories, Sub-Categories, Geography, Product, SalesRep) and fact tables (Sales 2014–2017). Product data was imported from MySQL Workbench. Includes DAX metrics and interactive dashboards for business insights.

📌 Project Overview

The goal of this project is to transform raw sales data into meaningful insights using Power BI by:

- Gathering data from multiple sources (Excel, CSV, MySQL)
- Performing data cleaning and transformation
- Creating data models using star schema
- Developing calculated columns and measures with DAX
- Building interactive reports and dashboards
- Publishing reports with Row-Level Security (RLS), auto-refresh, and subscription features


🗂️ Data Modeling

Dimension Tables:
- `Categories`
- `SubCategories`
- `Geography`
- `Product` *(imported from MySQL Workbench for real-world experience)*
- `SalesRep`

Fact Tables:
- `Sales_2014.csv`
- `Sales_2015.csv`
- `Sales_2016.csv`
- `Sales_2017.csv`  
  (Combined into one Sales table using Power BI folder connector with auto-refresh)
Steps Followed

1. Requirement Gathering
   - Business Requirement Document (BRD)
   - Functional Requirement Document (FRD)
2. Data Collection
   - MySQL, Excel, and CSV files
3. Data Cleaning
   - Using Power Query to fix headers, duplicates, splits, and formats
4. Data Modeling
   - Star schema relationships
   - Custom `DateMaster` table for time intelligence
5. DAX Calculations
   - Total Revenue, Cost, Gross Profit
   - QoQ and MoM Growth using time functions
6. Report Building
   - Cards, Slicers, Pie Charts, Bar Charts, Line Graphs
   - Top 5 SalesReps, SubCategory analysis, Date filters
7. Dashboard Creation
   - Pin visuals to a dashboard (single-page summary)
8. Publishing and Access
   - Publish to Power BI Service
   - Row-Level Security (RLS) by country using dynamic roles
   - Setup gateway, schedule refresh, subscriptions, alerts
   - Share reports securely via workspace and Power BI App


🔐 Key Features

1.Dynamic filtering by Country, Date, and Product
2.Clean and professional UI
3.Real-world experience with MySQL + Power BI integration
4.Automated folder refresh for new Sales data
5.Implemented dynamic Row-Level Security (RLS)

📊 Outcome

This project provides valuable experience in designing business-focused dashboards and working with real-world data integration scenarios. It’s ideal for anyone looking to build a strong portfolio in data analytics using Power BI.
