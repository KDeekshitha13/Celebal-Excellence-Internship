# Customer Sales Insights Using SQL

## Project Overview

This project focuses on analyzing the Sample Superstore dataset using SQL to generate meaningful customer sales insights. The dataset contains information related to customers, products, orders, sales, discounts, and profits, providing a realistic business scenario for data analysis.

The project was implemented using Databricks SQL, where the raw dataset was first imported and then structured into normalized tables for customers, products, and orders. This organization improved data consistency and enabled efficient querying across different entities.

Throughout the project, advanced SQL concepts such as **subqueries**, **common table expressions (CTEs)**, **joins**, and **window functions** were applied to perform analytical operations on the dataset. These techniques helped in calculating aggregated sales metrics, ranking customers based on performance, identifying order-level patterns, and deriving useful business insights from transactional data.

The analysis highlights customer purchasing behavior, sales distribution, and overall business performance. By transforming raw sales records into structured insights, this project demonstrates how SQL can be used not only for querying data but also for supporting data-driven decision-making in real-world business environments.

## Dataset Used

Dataset: Sample Superstore Dataset

The dataset includes information related to:

* Customer details
* Product details
* Order transactions

Key columns used in this project include:

* Order ID
* Order Date
* Customer ID
* Customer Name
* Product ID
* Product Name
* Sales

## Database Setup

The original dataset was imported into a raw table named:

`sample_superstore`

From this raw table, three separate tables were created for normalization:

### Customers Table

Stores customer-related information such as customer ID, customer name, segment, city, state, and region.

### Products Table

Stores product-related information such as product ID, product name, category, and sub-category.

### Orders Table

Stores transaction-related information such as order ID, order date, shipping details, customer ID, product ID, and sales.

## SQL Concepts Used

The project makes use of the following SQL concepts:

* **Subqueries** for comparing row values against aggregated results
* **CTEs** for simplifying complex analytical queries
* **Joins** for combining data across multiple tables
* **Window Functions** such as `rank()` and `row_number()` for ranking and row-wise analysis

## Conclusion

This project strengthened practical understanding of SQL by applying core and advanced concepts to a real-world sales dataset. It improved skills in database design, data normalization, analytical querying, and business insight generation. Overall, the project demonstrates the importance of structured data analysis in understanding customer behavior and supporting business decision-making.
