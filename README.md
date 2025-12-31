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

## Why LEFT JOIN Matters

LEFT JOIN is useful in real business scenarios where:
- Management wants a complete customer list.
- Identifying inactive or churn-risk customers.
- Finding data gaps for follow-up campaigns.



## Conclusion

This project demonstrates practical usage of SQL JOINs to analyze customer orders.
It highlights how INNER JOIN and LEFT JOIN behave differently and how NULL values
can be handled using COALESCE to make data analysis business-friendly.


### Sample Output

Customer Name | Product | Quantity
------------- | ------- | --------
Amit          | Laptop  | 1
Riya          | Phone   | 2
Suresh        | Headphones | 1
Neha          | No Order | 0



