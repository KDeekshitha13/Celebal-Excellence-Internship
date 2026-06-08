# SQL Assignments

## Part 1: Sales Data Analysis Using SQL

### Objective

The objective of this assignment was to analyze a sales dataset using SQL in Databricks. The analysis focused on understanding sales performance, customer behavior, product performance, regional trends, and data quality.

### Work Performed

The dataset was first loaded into Databricks and explored to understand its structure and available columns. Basic SQL queries were used to view records, check row counts, and inspect the schema.

Filtering operations were performed using the WHERE clause to analyze data based on region, category, sales amount, and order dates. Aggregation functions such as SUM(), AVG(), and COUNT() were applied with GROUP BY to calculate total sales, profit, quantity sold, and average values across different business dimensions.

The data was further analyzed to identify top-performing products, categories, customers, and regions. Sorting and limiting techniques were used to find the highest sales and profit contributors. Monthly sales and profit trends were also examined to understand business performance over time.

Data quality checks were carried out to identify duplicate records, missing values, and unusual entries such as loss-making transactions.

### Insights

- Certain regions contributed more sales and profit than others.
- Technology-related products generated higher revenue.
- High discounts were often associated with lower profits.
- A small number of customers contributed significantly to overall sales.
- Monthly trend analysis showed variations in sales and profitability across different periods.

This assignment demonstrated how SQL can be used to explore data, perform business analysis, and generate meaningful insights from sales records.

---

## Part 2: E-Commerce Sales Database Using SQL (Queries from Word Document)

### Objective

The objective of this assignment was to design and work with an e-commerce sales database using SQL. The assignment focused on database creation, constraints, relationships, indexing, data retrieval, aggregation, joins, and transaction management.

### Work Performed

A relational database was created consisting of four tables:
- customers
- products
- orders
- order_items

The tables were designed using primary keys, foreign keys, constraints, and indexes to maintain data integrity and improve query performance.

Sample data was inserted into all tables and different SQL queries were executed to answer business-related questions. Basic retrieval queries were used to display customer, product, and order information.

Filtering operations were performed using WHERE conditions to analyze specific products, customers, and orders. Indexes were studied to understand how they improve query performance.

Aggregation functions such as COUNT(), SUM(), AVG(), MIN(), and MAX() were used along with GROUP BY and HAVING clauses to generate summaries and business insights.

Different types of joins were implemented to combine data from multiple tables and analyze relationships between customers, orders, products, and order items.

Advanced SQL concepts such as CASE statements, ACID properties, and transactions using COMMIT and ROLLBACK were also explored.


This assignment helped in understanding both database design and SQL query writing for real-world business scenarios.
