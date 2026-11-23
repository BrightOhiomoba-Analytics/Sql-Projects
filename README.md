# SQL-Projects
A collection of SQL queries demonstrating database querying, data retrieval, joins, and data analysis skills.

**Author:** Ohiomoba Bright Ehichoya  
**Tool:** MySQL / MySQL Workbench  
**Project type:** SQL querying and employee-data analysis

## Project overview

This project contains five SQL exercises using employee, salary, occupation, and department data. The queries demonstrate how SQL can combine related tables, summarise salary information, compare values against an overall average, handle missing records, and apply business rules with conditional logic.

## Questions and SQL concepts

1. **Employee and department details** — uses `INNER JOIN` and `CONCAT()` to return employees with a matching department.
2. **Department salary summary** — uses `AVG()`, `MIN()`, `MAX()`, and `GROUP BY`.
3. **Above-average salaries** — uses a scalar subquery with `AVG()`.
4. **All employees and occupations** — uses `LEFT JOIN` and `COALESCE()` OR `IFNULL()` to display `Not Assigned` when an occupation record is missing.
5. **Bonus eligibility categories** — uses `INNER JOIN` and `CASE` to assign a bonus category based on department.

## Files

- `database.sql` — the raw SQL queries.
- `sql-assignment.docx` — the original assignment document, including screenshots of the work in MySQL Workbench.

## How to run

1. Open the `.sql` file in MySQL Workbench
2. Connect to the database that contains the assignment tables.
3. Confirm that the tables and column names match those used in the queries: `employee_salary`, `employee_demographics`, and `parks_departments`.
4. Execute each query separately and inspect the result set.

## Skills demonstrated

- Retrieving and combining data with SQL joins
- Aggregating and grouping data
- Using subqueries to compare records with an overall average
- Handling missing values with a left join and `COALESCE()` or `IFNULL()`
- Applying conditional business logic with `CASE`
- Writing readable, commented SQL queries













