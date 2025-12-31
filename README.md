# Customer Order Analysis using SQL Joins

## Objective
Analyze customer purchase behavior and identify customers with and without orders using SQL joins.

## Dataset
- Customers
- Products
- Orders

## SQL Concepts Used
- INNER JOIN
- LEFT JOIN
- COALESCE
- Foreign Keys

## Key Analysis
- Identified active customers with orders
- Identified customers with no orders
- Handled NULL values for clean business reporting

## Business Insight
Customers without orders can be targeted for retention campaigns.

## Tools
- PostgreSQL
- pgAdmin 4

- ## Business Questions Answered

1. Which customers have placed orders?
2. Which customers have never placed any order?
3. What products were ordered by each customer?
4. How many items did each customer purchase?
5. How to identify missing data using LEFT JOIN?


## Key Insights

- INNER JOIN returns only customers who have orders.
- LEFT JOIN helps identify customers with no orders.
- Customers without orders show NULL values in product and quantity.
- COALESCE is used to replace NULL values with meaningful defaults.

