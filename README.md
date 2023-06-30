# README

This repository contains a series of SQL scripts to handle and analyze an e-commerce database.

## Overview

The SQL scripts provide functionalities for:

1. Business metrics calculation and analysis.
2. Table creation and modification for parts and manufacturing process management.
3. Adjusting existing database structures.

## Content Breakdown

### Business Metrics Calculation and Analysis

The SQL scripts perform analysis on the ecommerce database to understand business performance, customer behavior, product performance, and other vital aspects. Here are some key operations:

- Counting the total number of orders.
- Calculating total, average prices and quantities for orders.
- Identifying popular items and repeat customers.
- Performing a temporal analysis (yearly, monthly) of orders and ratings.
- Analyzing the effect of coupon codes on purchases.
- Investigating the relationship between listing start date and sales.
- Calculating average delivery times.
- Analyzing revenue and quantity sold by city and over time.
  
These insights can be pivotal for data-driven business decision-making.

### Parts and Manufacturing Process Management

The SQL scripts create and modify tables to manage parts and manufacturing processes, providing functionalities such as:

- Selecting specific rows from the parts table to create new tables based on part_id ranges.
- Performing cross joins to select all combinations of parts from different tables.
- Creating temporary tables to store combinations of part IDs along with new keys.
- Updating the 'manufacturing' table with corresponding values from the temporary table.
- Renaming, adding, and dropping columns to match table structures.
- Removing duplicate rows.
- Joining tables and creating views with row numbers.
- Renaming columns and updating their values.
  
These scripts assist in efficiently managing the manufacturing processes.

### Adjusting Existing Database Structures

The SQL scripts adjust various tables in the 'etsy db' database. The operations include:

- Changing the data type of certain columns in 'orders' and 'reviews' tables.
- Adding new columns with specific properties to 'product_parts' table.
- Adjusting column properties in 'Parts' table and dropping a column.
- Renaming columns and adding new ones to other tables.
- Modifying data types and inserting data from one table to another.
- Adjusting date formatting for specific columns in 'orders' table.
- Modifying the 'reviews' table by adding new columns and adjusting their data types.

These operations allow for better data consistency, integrity and can improve database performance.

## Usage

Each SQL script file is intended to be run in a SQL environment connected to an e-commerce database. Make sure to adjust the database, table, and column names as per your actual database schema. Always remember to back up your database before running any scripts to prevent unwanted data loss.

## Note

These scripts are provided as a base template and might need modifications as per your database schema and requirements. Please adjust and test them accordingly. Be mindful of data privacy regulations when handling real customer data. 

This project is a continuous work in progress, and enhancements will be made based on feedback and requirements. Contributions and suggestions are always welcome.

