# 09 — SQL & Database

## Learn

- Tables, rows, columns
- Primary keys
- Foreign keys
- INSERT/SELECT/UPDATE/DELETE
- WHERE, ORDER BY, GROUP BY
- JOINs
- Aggregation
- Constraints
- Index basics
- Transactions
- Normalization basics

## Real Case: Cafe

Tables:

`users`, `products`, `categories`, `orders`, `order_items`, `payments`.

An order contains many items, and each item references a product. Learn why this is modeled with relationships rather than duplicated product data.

## Practice

Write queries for:

- all active products;
- orders for one customer;
- total sales per day;
- most popular products;
- customer order history;
- unpaid orders;
- products by category.

## Resources

- SQLBolt: https://sqlbolt.com/
- PostgreSQL tutorial: https://www.postgresql.org/docs/current/tutorial.html
- MDN database learning: https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Express_Nodejs/Introduction

## Interview Questions

- Primary key vs foreign key?
- INNER JOIN vs LEFT JOIN?
- Why indexes help?
- What is a transaction?
- What is normalization?
