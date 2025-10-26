# Plant Sales Performance Dashboard (Power BI)

# Dashboard Preview:

<img width="1462" height="816" alt="image" src="https://github.com/user-attachments/assets/770de3ad-201e-4345-ba58-673a5ba4937b" />

<img width="537" height="655" alt="image" src="https://github.com/user-attachments/assets/d44f343e-c46f-4b35-a3a0-e9bb658015bf" />

# Project Overview:

This project involves building an interactive sales dashboard in Power BI for a plant nursery. The goal is to analyze sales performance, track key metrics, and find insights into product, customer, and regional sales.

This dashboard answers key business questions such as:

1) What are our total sales, profit, and quantity sold over time?

2) Which products and product families are the top performers?

3) Which countries and accounts are our most valuable customers?

4) How does sales performance change year-over-year?

# Data Source:

The dataset was provided as three separate CSV files (originally from Plant_DTS.xls):

Plant_FACT.csv: A fact table containing all sales transactions (Sales, Quantity, COGS, Date, etc.).

Accounts.csv: A dimension table with information about customers/accounts.

Plant_Hierarchy.csv: A dimension table with information about the products (family, group, size, etc.).

# My Workflow (The Process):

1) Data Loading & Transformation (Power Query):

Connected Power BI to the three CSV files.

Performed data cleaning steps: checked data types, renamed columns for clarity, and handled missing or error values.

Merged the Accounts and Plant_Hierarchy tables into the Plant_FACT table to create a clean, denormalized table for analysis.

2) Data Modeling:

I built a relational star schema data model. I created relationships between the central Plant_FACT table and the Accounts and Plant_Hierarchy dimension tables. This is the best practice for efficient and accurate analysis.

3) DAX Calculations (Data Analysis Expressions):

Wrote several new measures using DAX to create key performance indicators (KPIs) that were not in the original data.



DAX: For creating custom measures and calculations.

Power View: For building the dashboard visuals and report layout.
