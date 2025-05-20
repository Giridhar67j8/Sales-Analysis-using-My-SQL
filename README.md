# Sales Analysis using MySQL
# ${\color{Red} Sales\ Analysis\ using\ MySQL}$
## Objective
The objective of the SQL script is to practice foundational and intermediate SQL operations on a custom database named yisu. It demonstrates how to create tables, insert data, retrieve and filter records, perform aggregations, ranking, and joins using SQL queries.

## Tools Used
MySQL or any relational database management system (RDBMS) that supports standard SQL syntax.

## Key Concepts
- Database and Table Creation

  CREATE DATABASE yisu; and multiple CREATE TABLE statements for BFSI, Sales, students, and Stud_info.

- Data Insertion

   Populates the tables with sample data using INSERT INTO.

- Data Retrieval

  SELECT queries to fetch and filter data using clauses like WHERE, ORDER BY, GROUP BY, HAVING, and LIMIT.

- String Matching

  Use of LIKE to search substrings within data.

- Aggregations

  Use of SUM(), AVG() functions, grouped by specific fields like country and ship_mode.

- Window Functions

  Demonstrates DENSE_RANK() with OVER(ORDER BY ...) in a Common Table Expression (CTE).

- Joins

  INNER JOIN and LEFT JOIN to combine data from students and Stud_info tables based on student_id.

## Conclusion
This script provides hands-on practice with core SQL concepts essential for data analysis and manipulation. It covers real-world scenarios such as identifying top performers, analyzing shipping modes, and combining datasets using joins—foundational skills for database management and analytics tasks.

