# MasteringSQLforData

This repository is a structured, self-paced SQL learning roadmap designed to build foundational to advanced SQL skills for data roles including Data Analyst, Data Scientist, and Data Engineer.

The goal is to gain proficiency in querying, manipulating, and analyzing data using SQL, aligned with real-world business use cases and interview expectations. This repository tracks weekly progress with concepts, structured exercises, and hands-on project work.

---

## 🔹 4-Week SQL Learning Plan

### Week 1: SQL Fundamentals (Data Retrieval)

> Objective: Understand databases and learn how to retrieve and summarize data using core SQL operations.

#### Topics:
- Basic SQL syntax
- Understanding tables, rows, columns, primary keys, and foreign keys
- SELECT, FROM, WHERE, ORDER BY
- DISTINCT
- Aggregations: COUNT, SUM, AVG, MIN, MAX
- GROUP BY and HAVING
- Filtering and sorting logic

#### Practice:
- Write and execute basic SQL queries on public platforms such as LeetCode, SQLZoo, or Mode Analytics.

---

### Week 2: Intermediate SQL (Joins & Data Modeling)

> Objective: Learn how to combine and query data from multiple tables and understand relational data models.

#### Topics:
- Relational database concepts
- INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN, CROSS JOIN
- Subqueries (correlated and non-correlated)
- Set operations: UNION, INTERSECT, EXCEPT

#### Practice:
- Multi-table joins and relationship-based queries
- Self joins and conditional joins
- Subquery-based filtering and aggregation

---

### Week 3: Advanced SQL (Window Functions & Logic)

> Objective: Develop advanced querying skills using window functions, conditional logic, and string/date manipulation.

#### Topics:
- Window Functions: ROW_NUMBER(), RANK(), DENSE_RANK(), LAG(), LEAD()
- Partitioning data using PARTITION BY
- CASE statements and IF logic
- String manipulation (e.g., CONCAT, TRIM, LENGTH)
- Date/time functions and arithmetic
- Common Table Expressions (CTEs)
- Query optimization basics (conceptual): indexes, execution plans

#### Practice:
- Real-world scenarios using advanced queries
- Time-based comparisons
- Ranking and lag/lead across partitions

---

### Week 4: Capstone Project – SQL Analysis on Real Dataset

> Objective: Apply all learned concepts to a real-world dataset and simulate an analytics use case.

#### Project:
- Choose dataset (e.g., e-commerce, COVID-19, online retail from Kaggle)
- Perform data exploration, aggregation, and reporting using SQL
- Design and execute complex multi-step queries using JOINs, CTEs, window functions
- Document queries, outputs, and insights in a Jupyter Notebook or markdown file

---

## 🔹 Structured SQL Practice Sections

This section includes categorized SQL problem sets with clear use cases and schemas for direct practice and mastery.

### 1. Window Functions

Functions: ROW_NUMBER, RANK, DENSE_RANK, LAG, LEAD

Example Scenarios:
- Top-N employees per department
- Latest order per customer
- Monthly revenue comparisons
- Stock price next-day analysis

### 2. Partitioning (PARTITION BY)

Use cases:
- Salary ranking within departments
- Rolling average order value per customer
- First purchase flags
- Spend increase detection per customer

### 3. Common Table Expressions (CTE)

Use cases:
- Top customers per month
- Second highest transaction
- Days with sales over thresholds
- High earners by department

### 4. Joins

Join Types: INNER, LEFT, RIGHT, FULL OUTER, CROSS JOIN

Use cases:
- Orders with customer & product info
- Products never sold
- Manager and employee mappings
- Category-wise revenue

### 5. Subqueries

Types: Scalar, Correlated, EXISTS/NOT EXISTS

Use cases:
- Customers with above-average spend
- Second highest salary
- Customers who ordered all products
- Departments with only one employee

### 6. Aggregations & Grouping

Use cases:
- Revenue per product/category
- Orders per customer per year
- Most popular product each month
- Customers with highest order frequency

---

## 🔹 Interview Preparation: Core SQL Theory Questions

- **What types of joins are there?**
- **What is a primary key vs. a foreign key?**
- **What is normalization and why is it important?**
- **What aggregate functions are commonly used?**
- **What's the difference between LEFT JOIN and LEFT OUTER JOIN?**
- **What is a CTE and when should you use it?**

---

## 🔹 Notes

- This repository is built for **personal learning and progression tracking**.
- Weekly folders will contain SQL scripts, query notebooks, and markdown files documenting learnings and practice.
- Final project folder will include data, queries, and insights from the capstone analysis.

---

## 📁 Repo Structure (Planned)

