# SQL Data Analysis

A compact data-analysis project demonstrating practical SQL and Python skills through a relational dataset.

> **Status:** Planned / Under Development  
> The repository currently defines the intended analytical workflow. Final queries and findings will be added after implementation.

## Overview

The project focuses on practical analytical SQL rather than building a large application.

A relational dataset will be loaded into SQLite and analyzed using progressively more advanced SQL queries.

## Objectives

The project will demonstrate:

- relational data understanding
- filtering and aggregation
- joins
- Common Table Expressions
- window functions
- analytical queries
- ranking
- time-based analysis
- combining SQL with Python/Pandas

## Workflow

```text
Dataset
   |
   v
SQLite Database
   |
   +------------------+
   |        |         |
   v        v         v
 JOINs     CTEs   Window Functions
   |        |         |
   +--------+---------+
            |
            v
       Aggregations
            |
            v
      Analytical Results
            |
            v
        Pandas / Charts
```

## SQL Topics

The project will cover:

### Basic Queries
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- CASE

### Joins
- INNER JOIN
- LEFT JOIN
- Multi-table joins

### Intermediate / Advanced SQL
- subqueries
- Common Table Expressions
- aggregate functions
- window functions
- ranking
- running totals
- partitioning
- time-based analysis

## Python Component

Python and Pandas may be used for:

- loading data
- executing SQL queries
- inspecting query outputs
- basic visualization
- summarizing analytical findings

## Planned Repository Structure

```text
sql-data-analysis/
├── data/
├── sql/
│   ├── basic_queries.sql
│   ├── joins.sql
│   ├── ctes.sql
│   └── window_functions.sql
├── notebooks/
├── src/
├── README.md
└── .gitignore
```

## Development Plan

1. Select a suitable open dataset.
2. Define the relational schema.
3. Load the dataset into SQLite.
4. Write basic analytical queries.
5. Add joins and aggregations.
6. Introduce CTEs.
7. Add window-function analyses.
8. Use Python/Pandas for result exploration.
9. Document the main findings.
10. Add reproducible setup instructions.

## Technology Stack

- SQL
- SQLite
- Python
- Pandas
- Matplotlib

## Expected Learning Outcomes

- SQL fundamentals
- Analytical SQL
- Relational data analysis
- Joins
- CTEs
- Window functions
- Python/SQL integration
- Data interpretation

## Scope

This is intentionally a small supporting project.

The objective is to demonstrate practical SQL ability without overengineering the application.
