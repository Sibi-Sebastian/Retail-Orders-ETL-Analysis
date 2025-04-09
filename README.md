# Retail-Orders-ETL-Analysis
Built an ETL pipeline to extract, clean, store, and analyze retail sales data using Python and SQL Server.

This project is an ETL (Extract, Transform, Load) pipeline project where I:

Extracted retail order data from Kaggle (the orders.csv dataset).

Transformed the data by:

Handling missing values,

Cleaning column names by converting them to lowercase and replacing spaces with underscores,

Creating new columns such as discount, sale_price, and profit.

Loaded the cleaned data into a SQL Server database in a table named df_orders.

Analyzed the data by writing SQL queries to:

Identify the top 10 highest revenue-generating products,

Identify the top 5 best-selling products in each region,

Conduct a month-over-month sales growth comparison for the years 2022 and 2023.

Through this project, I covered the complete data lifecycle from extraction, transformation, and loading, to performing analysis.