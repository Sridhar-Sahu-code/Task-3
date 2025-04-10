# SQL Practice Exercises

This repository contains a series of SQL practice problems focusing on:

- SELECT, WHERE, ORDER BY, GROUP BY
- JOINS (INNER, LEFT, RIGHT)
- Subqueries
- Aggregate Functions (SUM, AVG)
- Creating Views for Analysis
- Query Optimization with Indexes

## 📁 Tables

We assume a basic schema based on customer and order data.

### `customers`

| Column       | Type        |
|--------------|-------------|
| customer_id  | INT (PK)    |
| name         | VARCHAR     |
| email        | VARCHAR     |
| city         | VARCHAR     |
| signup_date  | DATE        |

### `orders`

| Column       | Type        |
|--------------|-------------|
| order_id     | INT (PK)    |
| customer_id  | INT (FK)    |
| order_date   | DATE        |
| amount       | DECIMAL     |

## ✅ SQL Topics Covered

1. Basic SELECTs and Filtering
2. Sorting and Grouping
3. JOINS (INNER, LEFT, RIGHT)
4. Subqueries
5. Aggregates
6. Views
7. Indexes

## 🚀 How to Use

You can use these SQL snippets with:

- PostgreSQL
- MySQL
- SQLite
- Any RDBMS that supports standard SQL

You can also adapt the queries based on the data format in `customers.csv`.

---

Happy querying! 🧠💻
