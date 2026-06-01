
# Exercise 02 – Databricks SQL

## Overview
This exercise involved creating and managing tables in the `my_coffee_shop` schema using Databricks SQL.

Tasks Completed
 
Task 1: Created Schema
Created the `my_coffee_shop` schema and confirmed that it was active in Databricks.
 
Task 2: Created dim_customers Table
Created the `dim_customers` table to store customer information.

Task 3: Created dim_products Table
Created the `dim_products` table with product information such as product ID, product code, product name, price, and category.

Task 4: Created fact_orders Table
Created the fact_orders table to store order transaction data. The table was partitioned by order_date to improve query performance and data organization.

Task 5: Renamed a Column
Renamed the `loyalty_points` column to `points` using the ALTER TABLE command.

Task 6: Inserted Data
Inserted at least 5 customer records and 5 product records into the tables.

Task 7: Updated Customer Points
Updated customer points by increasing them by 50.

Task 8: Created Backup Table
Created a backup table named `dim_customers_backup` containing the same records as the original table.

Task 9: Deleted a Customer and Checked History
Deleted one customer record and verified the operation using table history.

Screenshot
A screenshot of the Databricks Catalog showing the `my_coffee_shop` schema and all created tables has been included in this repository.

## Files Included
- Exported Databricks Notebook (`.ipynb`)
- README.md
- Screenshot of Databricks Catalog
