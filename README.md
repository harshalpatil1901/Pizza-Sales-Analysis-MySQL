# 🍕 Pizza Sales Analysis using MySQL

## 📌 Project Overview

The Pizza Sales Analysis project is a structured SQL-based data analysis project designed to extract meaningful business insights from a relational pizza sales database.

This project uses MySQL to analyze order patterns, revenue trends, product performance, and customer purchasing behavior. The database consists of multiple related tables including orders, order details, pizzas, and pizza types.

The objective of this project is to demonstrate strong SQL querying skills by solving business problems using joins, aggregations, subqueries, window functions, and Common Table Expressions (CTEs).

---

## 🗄 Database Schema

The project consists of the following tables:

### 1️⃣ pizza_types
- pizza_type_id (Primary Key)
- name
- category
- ingredients

### 2️⃣ pizzas
- pizza_id (Primary Key)
- pizza_type_id (Foreign Key)
- size
- price

### 3️⃣ orders
- order_id (Primary Key)
- date
- time

### 4️⃣ order_details
- order_details_id (Primary Key)
- order_id (Foreign Key)
- pizza_id (Foreign Key)
- quantity

The schema follows relational database principles using primary and foreign key constraints.

---

## 🎯 Business Objectives

- Calculate total number of orders
- Determine total revenue generated
- Identify highest-priced pizza
- Find most ordered pizza size
- Analyze category-wise performance
- Identify top-selling pizzas
- Evaluate hourly order distribution
- Track cumulative revenue over time
- Calculate revenue contribution percentages

---

## 📊 Key Business Analysis Performed

### 🔹 Basic Analysis
- Total orders placed
- Total revenue generated
- Highest priced pizza
- Most commonly ordered size
- Top 5 most ordered pizza types

### 🔹 Intermediate Analysis
- Category-wise quantity ordered
- Hour-wise order distribution
- Category distribution of pizzas
- Daily average pizzas ordered
- Top 3 pizzas based on revenue

### 🔹 Advanced Analysis
- Percentage contribution of each pizza to total revenue
- Cumulative revenue analysis using window functions
- Top 3 pizzas by revenue within each category using CTE and ROW_NUMBER()

---

## 🛠 SQL Concepts Used

- SELECT statements
- INNER JOIN
- GROUP BY & ORDER BY
- Aggregate Functions (SUM, COUNT, MAX)
- Subqueries
- Window Functions
- Common Table Expressions (CTE)
- ROW_NUMBER()
- OVER() Clause
- Foreign Key Relationships

---

## 📈 Key Insights

- Identified top revenue-generating pizza types
- Determined peak order hours
- Measured revenue contribution percentage per pizza
- Analyzed category performance
- Tracked cumulative revenue growth over time


---

## 🚀 Project Outcome

This project demonstrates strong SQL and relational database skills by solving real-world business problems using structured queries.

It showcases the ability to:
- Work with normalized database schemas
- Perform complex joins and aggregations
- Apply window functions and CTEs
- Translate business questions into SQL queries
- Extract actionable insights from transactional data

---

## 🧑‍💻 Tools Used

- MySQL
- SQL Workbench
- Relational Database Design

---

## 📌 Conclusion

The Pizza Sales Analysis project highlights practical SQL skills and analytical thinking required for data analysis roles. It transforms raw sales data into structured insights that support data-driven business decisions.
