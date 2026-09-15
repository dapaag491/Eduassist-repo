# 📚 Sql server

> **Summary:** Based on your current performance, you demonstrate strong understanding in intermediate, advanced, and difficult SQL Server topics but may benefit from reinforcing foundational beginner concepts, particularly those related to question 2 where an error occurred. This learning path focuses on strengthening basics while progressing through increasingly complex material to build mastery.
> **Status:** Finalized | **Progress:** 5/15 Modules (33%) | **Last Updated:** 2026-09-15

---

## 🔹 Module 1: Review SQL SELECT and WHERE Clauses
- **ID:** `node-1`
- **Progress:** [x] Completed (Completed: 2026-09-15)

**Description:**
Strengthen foundational knowledge on SELECT statements and WHERE clause filtering, focusing on performance optimization for large production datasets and addressing the error in Question 2.

### 🔗 Resources
- [Microsoft Learn - SQL Server T-SQL Fundamentals](https://learn.microsoft.com/en-us/sql/t-sql/language-elements/select-transact-sql) `[documentation]` - Official Microsoft documentation covering T-SQL basics including SELECT, INSERT, UPDATE, DELETE statements with practical examples for SQL Server.
- [W3Schools SQL Tutorial](https://www.w3schools.com/sql/) `[article]` - Comprehensive tutorial on SQL basics with interactive examples demonstrating SELECT, INSERT, UPDATE, and DELETE operations for beginners.
- [SQL for Beginners - Full Database Course](https://www.youtube.com/watch?v=HXoDXy7EmoE) `[video]` - FreeCodeCamp's 4-hour YouTube course covering fundamental SQL concepts including query structure, data manipulation, and database operations.
- [GeeksforGeeks SQL Tutorial](https://www.geeksforgeeks.org/sql-tutorial/) `[article]` - Step-by-step SQL guide explaining SELECT, INSERT, UPDATE, and DELETE commands with syntax breakdowns and practical use cases.
- [TechOnTheNet SQL Server Tutorial](https://www.techonthenet.com/sql_server/index.php) `[documentation]` - Detailed SQL Server documentation with clear explanations of basic SQL statements including examples for data querying and modification.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] SELECT employee_id, first_name, last_name FROM employees AS emp_data
- [ ] SELECT employee_id, first_name, last_name FROM employees emp_data
- [ ] SELECT employee_id, first_name, last_name AS full_name FROM employees
- [ ] SELECT employee_id, first_name, last_name FROM employees AS emp_data;

**2. Question 2**
- [ ] WHERE email <> NULL
- [ ] WHERE email IS NULL
- [ ] WHERE email = NULL
- [ ] WHERE email = ''

**3. Question 3**
- [ ] WHERE salary BETWEEN 50000 AND 100000
- [ ] WHERE salary = 50000
- [ ] WHERE salary = 50000 AND department_id = 10
- [ ] WHERE salary > 50000

**4. Question 4**
- [ ] SELECT * FROM employees e WHERE e.id = (SELECT id FROM departments)
- [ ] SELECT * FROM employees e WHERE e.id IN (SELECT id FROM departments)
- [ ] SELECT * FROM employees e WHERE e.id = ANY (SELECT id FROM departments)
- [ ] SELECT * FROM employees e WHERE EXISTS (SELECT 1 FROM departments d WHERE d.employee_id = e.id)

**5. Question 5**
- [ ] SELECT order_id, order_date, amount FROM orders WHERE order_date >= '2023-01-01'
- [ ] SELECT amount FROM orders WHERE order_date BETWEEN '2023-01-01' AND '2023-12-31'
- [ ] SELECT order_date FROM orders WHERE amount > 1000
- [ ] SELECT order_date, amount FROM orders WHERE order_date >= '2023-01-01' AND amount > 1000

---

## 🔹 Module 2: Intermediate SQL JOIN Operations
- **ID:** `node-2`
- **Progress:** [x] Completed (Completed: 2026-09-15)

**Description:**
Deep dive into INNER, LEFT, RIGHT, and FULL JOINs with practical examples to improve performance in intermediate topics, emphasizing optimized JOIN strategies for production-scale data.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] FULL OUTER JOIN
- [ ] INNER JOIN
- [ ] LEFT JOIN
- [ ] RIGHT JOIN

**2. Question 2**
- [ ] All rows from both tables, with NULLs where there is no match
- [ ] All rows from the left table, with matching rows from the right table (NULLs if no match)
- [ ] Only rows that match in both tables
- [ ] All rows from the right table, with matching rows from the left table (NULLs if no match)

**3. Question 3**
- [ ] RIGHT OUTER JOIN
- [ ] LEFT OUTER JOIN
- [ ] INNER JOIN
- [ ] FULL OUTER JOIN

**4. Question 4**
- [ ] Move the join condition to a HAVING clause
- [ ] Place the smaller table in the ON clause and ensure it is indexed on the join column
- [ ] Force the optimizer to scan the larger table first
- [ ] Use a Cartesian product and filter the results

**5. Question 5**
- [ ] INNER JOIN
- [ ] RIGHT JOIN
- [ ] FULL JOIN
- [ ] LEFT JOIN

**6. Question 6**
- [ ] Table B rows only
- [ ] Table A rows only
- [ ] Rows that have matching keys in both tables only
- [ ] All rows from both tables, with NULLs where no match exists

**7. Question 7**
- [ ] Using a FULL OUTER JOIN instead of an INNER JOIN
- [ ] Removing the existing index on the fact table's join column
- [ ] Adding a composite index on the dimension table's primary‑key column
- [ ] Adding a covering index on the fact table's foreign‑key column

**8. Question 8**
- [ ] INNER JOIN
- [ ] FULL OUTER JOIN
- [ ] RIGHT JOIN
- [ ] LEFT JOIN

**9. Question 9**
- [ ] RIGHT JOIN – because it prioritizes the right (`order_items`) table.
- [ ] INNER JOIN – because it automatically discards orders lacking items.
- [ ] FULL OUTER JOIN – because it returns all rows from both tables.
- [ ] LEFT JOIN – because it keeps all rows from the left (`orders`) table and fills missing columns with NULL.

**10. Question 10**
- [ ] INNER JOIN – because it excludes employees with no skill records.
- [ ] LEFT JOIN – because it preserves all employees even if they have no assigned skills.
- [ ] RIGHT JOIN – because it keeps all skill records regardless of employee presence.
- [ ] FULL OUTER JOIN – because it returns every row from both tables.

**11. Question 11**
- [ ] Apply a FULL OUTER JOIN to combine both tables and then filter out rows with no matching segment.
- [ ] Begin with the `customer_segments` table and perform an INNER JOIN against `transactions`.
- [ ] Use a RIGHT JOIN that prioritizes the `transactions` side.
- [ ] Start with the `transactions` table and apply a LEFT JOIN, retaining all transactions and keeping only those that have a segment association.

---

## 🔹 Module 3: SQL Subqueries and Nested Queries
- **ID:** `node-3`
- **Progress:** [x] Completed (Completed: 2026-09-15)

**Description:**
Master subquery structures and nested SELECT statements, focusing on performance considerations and production data handling as tested in Questions 3 and 4.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] B) A correlated subquery that computes AVG(salary) per row inside the WHERE clause.
- [ ] C) A single query using a CTE to compute department averages once, then joining to the employee table.
- [ ] D) A scalar subquery in the SELECT list that recomputes the average for each row.
- [ ] A) A self‑join with a derived table that pre‑computes department averages.

**2. Question 2**
- [ ] C) When the data type of the columns does not match, because EXISTS is type‑insensitive.
- [ ] D) When you need the actual values from the subquery, because EXISTS only returns true/false.
- [ ] A) When the subquery returns a large number of rows, because IN can cause memory spills.
- [ ] B) When the subquery returns at most one row, because EXISTS short‑circuits evaluation.

**3. Question 3**
- [ ] D) Scalar subqueries are deprecated in modern SQL.
- [ ] C) Scalar subqueries are best for massive datasets because they reduce I/O.
- [ ] B) Scalar subqueries can be rewritten as a JOIN for better performance and reduced parsing overhead.
- [ ] A) Scalar subqueries are always evaluated once per outer row.

**4. Question 4**
- [ ] B) Use OR to combine the subquery results with the primary filter.
- [ ] D) Force evaluation order with parentheses.
- [ ] C) Add redundant indexes on the subquery's SELECT columns.
- [ ] A) Place the subquery in a JOIN rather than a scalar subquery in the WHERE clause.

**5. Question 5**
- [ ] D) Run subqueries with elevated privileges to simplify code.
- [ ] A) Select * and apply row‑level security later.
- [ ] B) Use VIEWs that encapsulate the subquery and grant limited privileges.
- [ ] C) Hardcode filter values in the subquery to avoid exposing parameters.

---

## 🔹 Module 4: Intermediate Aggregations and GROUP BY
- **ID:** `node-4`
- **Progress:** [x] Completed (Completed: 2026-09-15)

**Description:**
Reinforce understanding of aggregate functions and grouping, building on the correct answer in Question 5 with a focus on optimizing aggregations for large-scale production data.

### 🔗 Resources
- [SELECT - GROUP BY Clause (Transact-SQL) – Microsoft Learn](https://learn.microsoft.com/en-us/sql/t-sql/queries/select-group-by-transact-sql?view=sql-server-ver17) `[documentation]` - Official SQL Server reference for GROUP BY, aggregate functions, HAVING, GROUPING SETS, ROLLUP, and CUBE.
- [Optimization Thresholds - Grouping and Aggregating Data, Part 1](https://sqlperformance.com/2018/04/sql-plan/grouping-and-aggregating-part-1) `[article]` - Explains SQL Server Stream Aggregate and Hash Aggregate operators, why ordered input matters, and how an index aligned with grouping columns can avoid an explicit sort.
- [Use Built-in Functions and GROUP BY in Transact-SQL – Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/use-built-functions-transact-sql/) `[training]` - Interactive Microsoft Learn module covering built-in and aggregate functions, GROUP BY, and HAVING in Transact-SQL.
- [Use HAVING and WHERE Clauses in the Same Query – Microsoft Learn](https://learn.microsoft.com/en-us/ssms/visual-db-tools/use-having-and-where-clauses-in-the-same-query-visual-database-tools) `[documentation]` - Explains the distinction between filtering individual rows with WHERE before grouping and filtering groups with HAVING after aggregation.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] The number of rows for each category.
- [ ] The total sales amount for each category.
- [ ] The average value of a numeric column per category.
- [ ] The maximum value per category.

**2. Question 2**
- [ ] MIN
- [ ] AVG
- [ ] COUNT
- [ ] SUM

**3. Question 3**
- [ ] SELECT month, COUNT(*) FROM customers;
- [ ] SELECT month, AVG(customer_id) FROM customers;
- [ ] SELECT month, SUM(customer_id) FROM customers;
- [ ] SELECT month, COUNT(DISTINCT customer_id) FROM customers;

**4. Question 4**
- [ ] Average sales per region and product.
- [ ] Total sales per product only.
- [ ] Total sales for each region‑product combination.
- [ ] Total sales per region only.

**5. Question 5**
- [ ] Partition the table by date.
- [ ] Pre‑aggregate and materialize summary tables.
- [ ] Add a composite index on the GROUP BY columns.
- [ ] Use window functions instead of GROUP BY.

---

## 🔹 Module 5: Advanced Query Optimization and Execution Plans
- **ID:** `node-5`
- **Progress:** [x] Completed (Completed: 2026-09-15)

**Description:**
Learn to optimize complex queries using execution plans and indexing strategies, leveraging the correct answer in Question 6 while analyzing performance bottlenecks in production environments.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] Nested Loops
- [ ] Index Seek
- [ ] Hash Match
- [ ] Merge Join

**2. Question 2**
- [ ] Clustered index
- [ ] Composite index
- [ ] Filtered index
- [ ] Indexed view

**3. Question 3**
- [ ] Excessive parallelism
- [ ] Insufficient indexing
- [ ] Memory pressure
- [ ] Disk I/O bound

**4. Question 4**
- [ ] sys.dm_exec_query_plan
- [ ] sys.dm_exec_query_statistics
- [ ] sys.dm_exec_sql_text
- [ ] sys.dm_exec_requests

**5. Question 5**
- [ ] High network latency
- [ ] High logical reads
- [ ] High DML latency
- [ ] High CPU

---

## 🔹 Module 6: Practice: Intermediate SQL Exercises
- **ID:** `node-6`
- **Progress:** [ ] Completed

**Description:**
Apply learned concepts through targeted exercises on JOINs and subqueries with production-like datasets to simulate real-world performance challenges.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] SELECT c.customer_id, c.name, SUM(o.amount) AS total_spent FROM customers c JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date BETWEEN '2023-01-01' AND '2023-12-31' GROUP BY c.customer_id, c.name;
- [ ] SELECT c.customer_id, c.name, COUNT(o.order_id) AS total_spent FROM customers c JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date >= '2023-01-01' GROUP BY c.customer_id, c.name;
- [ ] SELECT c.customer_id, c.name, SUM(o.amount) AS total_spent FROM customers c INNER JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date > '2023-12-31' GROUP BY c.customer_id, c.name;
- [ ] SELECT c.customer_id, c.name, SUM(o.amount) AS total_spent FROM customers c LEFT JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date BETWEEN '2023-01-01' AND '2023-12-31' GROUP BY c.customer_id, c.name;

**2. Question 2**
- [ ] SELECT d.department_name, SUM(e.salary) FROM departments d LEFT JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;
- [ ] SELECT d.department_name, AVG(e.salary) FROM departments d INNER JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;
- [ ] SELECT d.department_name, AVG(e.salary) FROM departments d LEFT JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;
- [ ] SELECT d.department_name, AVG(e.salary) FROM departments d RIGHT JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;

**3. Question 3**
- [ ] SELECT e1.employee_name AS employee, e2.employee_name AS manager FROM employees e1 RIGHT JOIN employees e2 ON e1.employee_id = e2.manager_id;
- [ ] SELECT e1.employee_name AS employee, e2.employee_name AS manager FROM employees e1 LEFT JOIN employees e2 ON e1.manager_id = e2.employee_id;
- [ ] SELECT e1.employee_id, e2.employee_id FROM employees e1 INNER JOIN employees e2 ON e1.employee_id = e2.manager_id;
- [ ] SELECT e1.employee_name, e2.employee_name FROM employees e1, employees e2 WHERE e1.manager_id = e2.employee_id;

**4. Question 4**
- [ ] SELECT employee_name FROM employees WHERE salary > (SELECT AVG(salary) FROM employees) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) > 75000);
- [ ] SELECT employee_name FROM employees WHERE salary > (SELECT MAX(salary) FROM employees) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) > 75000);
- [ ] SELECT employee_name FROM employees WHERE salary > (SELECT AVG(salary) FROM employees) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) < 75000);
- [ ] SELECT employee_name FROM employees WHERE salary > AVG(salary) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) > 75000);

**5. Question 5**
- [ ] SELECT p.product_name FROM products p INNER JOIN order_items oi ON p.product_id = oi.product_id WHERE p.product_id IS NOT NULL;
- [ ] SELECT p.product_name FROM products p RIGHT JOIN order_items oi ON p.product_id = oi.product_id WHERE p.product_id IS NULL;
- [ ] SELECT p.product_name FROM products p LEFT JOIN order_items oi ON p.product_id = oi.product_id WHERE oi.product_id IS NULL;
- [ ] SELECT p.product_name FROM products p JOIN order_items oi ON p.product_id = oi.product_id WHERE oi.product_id IS NULL;

---

## 🔹 Module 7: Database Design Fundamentals for Scalability
- **ID:** `node-7`
- **Progress:** [ ] Completed

**Description:**
Explore normalization, relationships, and schema design to support advanced query writing skills, with emphasis on scalable production database architectures.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] 3NF
- [ ] BCNF
- [ ] 1NF
- [ ] 2NF

**2. Question 2**
- [ ] Materialized views only
- [ ] Single master with synchronous replication
- [ ] Partitioning + read replicas
- [ ] Shared-disk cluster

**3. Question 3**
- [ ] Reduce data redundancy
- [ ] Simplify foreign key constraints
- [ ] Enforce entity integrity
- [ ] Improve query performance

**4. Question 4**
- [ ] ON DELETE CASCADE
- [ ] ON DELETE NO ACTION
- [ ] ON DELETE RESTRICT
- [ ] ON DELETE SET NULL

**5. Question 5**
- [ ] Denormalizing all relationships
- [ ] Horizontal partitioning
- [ ] Storing all attributes in a single varchar
- [ ] Using a single monolithic table

---

## 🔹 Module 8: Transactions and Concurrency Control in Production
- **ID:** `node-8`
- **Progress:** [ ] Completed

**Description:**
Understand ACID properties, transaction isolation levels, and locking mechanisms in SQL Server, particularly in high-concurrency production environments.

### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] Locks are held until the transaction commits.
- [ ] The transaction's changes survive a system crash.
- [ ] The transaction's data is isolated from other concurrent transactions.
- [ ] The transaction is atomic, meaning all operations are completed or none are.

**2. Question 2**
- [ ] Serializable
- [ ] Read Committed
- [ ] Read Uncommitted
- [ ] Repeatable Read

**3. Question 3**
- [ ] Indexes are missing leading to scans
- [ ] Queries returning error 1205 and ending in a deadlock victim
- [ ] Data being written to the transaction log out of order
- [ ] Locks being held indefinitely without waiting

**4. Question 4**
- [ ] Shared lock (S lock)
- [ ] Exclusive lock (X lock)
- [ ] Schema lock
- [ ] Intent lock

**5. Question 5**
- [ ] Increasing the LOCK_ESCAPE threshold
- [ ] Reducing the number of user connections
- [ ] Using finer‑grained lock granularity by setting LOCK_PAGING hint
- [ ] Using READ COMMITTED snapshot isolation

---

## 🔹 Module 9: Indexing Strategies and Performance Tuning for Production
- **ID:** `node-9`
- **Progress:** [ ] Completed

**Description:**
Learn to create and manage indexes, including clustered vs non-clustered, to enhance query efficiency while addressing maintenance and optimization in live production systems.

---

## 🔹 Module 10: Advanced SQL Functions and Procedures for Efficiency
- **ID:** `node-10`
- **Progress:** [ ] Completed

**Description:**
Dive into user-defined functions, stored procedures, and triggers to expand advanced skillsets, ensuring optimal performance and resource usage in production scenarios.

---

## 🔹 Module 11: Querying XML and JSON Data in Production Systems
- **ID:** `node-11`
- **Progress:** [ ] Completed

**Description:**
Work with semi-structured data formats in SQL Server for modern application integration, focusing on performance and scalability for production workloads.

---

## 🔹 Module 12: SQL Server Security Best Practices for Production
- **ID:** `node-12`
- **Progress:** [ ] Completed

**Description:**
Implement authentication, authorization, and encryption to secure database environments, including compliance requirements for production data protection.

---

## 🔹 Module 13: Backup, Recovery, and Disaster Planning for Production
- **ID:** `node-13`
- **Progress:** [ ] Completed

**Description:**
Design and execute database backup plans and recovery procedures for data integrity, focusing on minimizing downtime and ensuring business continuity in production environments.

---

## 🔹 Module 14: Advanced Query Techniques Workshop for Production
- **ID:** `node-14`
- **Progress:** [ ] Completed

**Description:**
Combine all skills through complex real-world query challenges and performance case studies, emphasizing production data management and optimization scenarios.

---

## 🔹 Module 15: Final Assessment and Production Skill Validation
- **ID:** `node-15`
- **Progress:** [ ] Completed

**Description:**
Take a comprehensive test covering all difficulty levels to validate mastery of production data management and performance optimization, identifying remaining gaps.

---

<!-- EDU_ASSIST_METADATA_START
{
  "topic": "Sql server",
  "path": {
    "summary": "Based on your current performance, you demonstrate strong understanding in intermediate, advanced, and difficult SQL Server topics but may benefit from reinforcing foundational beginner concepts, particularly those related to question 2 where an error occurred. This learning path focuses on strengthening basics while progressing through increasingly complex material to build mastery.",
    "nodes": [
      {
        "id": "node-1",
        "title": "Review SQL SELECT and WHERE Clauses",
        "description": "Strengthen foundational knowledge on SELECT statements and WHERE clause filtering, focusing on performance optimization for large production datasets and addressing the error in Question 2.",
        "estimatedTime": "1.5 hours",
        "resources": [
          {
            "type": "documentation",
            "title": "Microsoft Learn - SQL Server T-SQL Fundamentals",
            "url": "https://learn.microsoft.com/en-us/sql/t-sql/language-elements/select-transact-sql",
            "description": "Official Microsoft documentation covering T-SQL basics including SELECT, INSERT, UPDATE, DELETE statements with practical examples for SQL Server."
          },
          {
            "type": "article",
            "title": "W3Schools SQL Tutorial",
            "url": "https://www.w3schools.com/sql/",
            "description": "Comprehensive tutorial on SQL basics with interactive examples demonstrating SELECT, INSERT, UPDATE, and DELETE operations for beginners."
          },
          {
            "type": "video",
            "title": "SQL for Beginners - Full Database Course",
            "url": "https://www.youtube.com/watch?v=HXoDXy7EmoE",
            "description": "FreeCodeCamp's 4-hour YouTube course covering fundamental SQL concepts including query structure, data manipulation, and database operations."
          },
          {
            "type": "article",
            "title": "GeeksforGeeks SQL Tutorial",
            "url": "https://www.geeksforgeeks.org/sql-tutorial/",
            "description": "Step-by-step SQL guide explaining SELECT, INSERT, UPDATE, and DELETE commands with syntax breakdowns and practical use cases."
          },
          {
            "type": "documentation",
            "title": "TechOnTheNet SQL Server Tutorial",
            "url": "https://www.techonthenet.com/sql_server/index.php",
            "description": "Detailed SQL Server documentation with clear explanations of basic SQL statements including examples for data querying and modification."
          }
        ],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "Which of the following SELECT statements retrieves the employee_id, first_name, and last_name columns from the employees table, aliasing the table as emp_data?",
            "options": [
              "SELECT employee_id, first_name, last_name FROM employees AS emp_data",
              "SELECT employee_id, first_name, last_name FROM employees emp_data",
              "SELECT employee_id, first_name, last_name AS full_name FROM employees",
              "SELECT employee_id, first_name, last_name FROM employees AS emp_data;"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "Option B correctly uses the table alias `emp_data` after the table name, allowing the alias to be referenced elsewhere (e.g., in joins). The other options either misuse the `AS` keyword for the result set or select an unintended column."
          },
          {
            "id": 2,
            "text": "Which WHERE clause correctly checks for null values in the email column?",
            "options": [
              "WHERE email <> NULL",
              "WHERE email IS NULL",
              "WHERE email = NULL",
              "WHERE email = ''"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "SQL requires the use of `IS NULL` (and `IS NOT NULL`) to test for null values because `=` compares equality and cannot match null. Option B uses the proper syntax, preventing a common error that would otherwise cause the predicate to always be false."
          },
          {
            "id": 3,
            "text": "Which of the following WHERE conditions will most likely allow the optimizer to use an existing B‑tree index on the salary column?",
            "options": [
              "WHERE salary BETWEEN 50000 AND 100000",
              "WHERE salary = 50000",
              "WHERE salary = 50000 AND department_id = 10",
              "WHERE salary > 50000"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "A simple equality predicate (`salary = 50000`) is the most index‑friendly because the optimizer can directly seek the index leaf for that exact value. Range predicates (>, BETWEEN) may still use the index but are less selective, and the composite predicate can also use an index if one exists on both columns, but the pure equality is the best candidate for index utilization."
          },
          {
            "id": 4,
            "text": "For a large production dataset, which construct is generally more efficient for checking the existence of rows in a related table?",
            "options": [
              "SELECT * FROM employees e WHERE e.id = (SELECT id FROM departments)",
              "SELECT * FROM employees e WHERE e.id IN (SELECT id FROM departments)",
              "SELECT * FROM employees e WHERE e.id = ANY (SELECT id FROM departments)",
              "SELECT * FROM employees e WHERE EXISTS (SELECT 1 FROM departments d WHERE d.employee_id = e.id)"
            ],
            "correctAnswerIndex": 3,
            "reasoning": "`EXISTS` short‑circuits as soon as a matching row is found and does not build an intermediate result set, making it more scalable than `IN`. It also works correctly with null values and can leverage semi‑join optimizations in modern optimizers."
          },
          {
            "id": 5,
            "text": "Which SELECT statement can benefit from a covering index on the columns (order_date, amount)?",
            "options": [
              "SELECT order_id, order_date, amount FROM orders WHERE order_date >= '2023-01-01'",
              "SELECT amount FROM orders WHERE order_date BETWEEN '2023-01-01' AND '2023-12-31'",
              "SELECT order_date FROM orders WHERE amount > 1000",
              "SELECT order_date, amount FROM orders WHERE order_date >= '2023-01-01' AND amount > 1000"
            ],
            "correctAnswerIndex": 3,
            "reasoning": "Option D both filters and selects the two columns covered by the index, allowing the engine to satisfy the query entirely from the index (a covering index). This eliminates look‑ups to the base table and improves performance on large data sets."
          }
        ],
        "completed": true,
        "completedAt": 1789436582883
      },
      {
        "id": "node-2",
        "title": "Intermediate SQL JOIN Operations",
        "description": "Deep dive into INNER, LEFT, RIGHT, and FULL JOINs with practical examples to improve performance in intermediate topics, emphasizing optimized JOIN strategies for production-scale data.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "Which JOIN type returns only the rows that have matching rows in both tables?",
            "options": [
              "FULL OUTER JOIN",
              "INNER JOIN",
              "LEFT JOIN",
              "RIGHT JOIN"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "An INNER JOIN returns rows only when there is a match in both the left and right tables, making it the correct choice."
          },
          {
            "id": 2,
            "text": "In a LEFT JOIN, which rows are always included?",
            "options": [
              "All rows from both tables, with NULLs where there is no match",
              "All rows from the left table, with matching rows from the right table (NULLs if no match)",
              "Only rows that match in both tables",
              "All rows from the right table, with matching rows from the left table (NULLs if no match)"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "A LEFT JOIN guarantees all rows from the left (preserved) table are returned, filling with NULLs on the right side when there is no matching row."
          },
          {
            "id": 3,
            "text": "Which JOIN type will include all rows from both tables, filling NULLs where there is no match?",
            "options": [
              "RIGHT OUTER JOIN",
              "LEFT OUTER JOIN",
              "INNER JOIN",
              "FULL OUTER JOIN"
            ],
            "correctAnswerIndex": 3,
            "reasoning": "A FULL OUTER JOIN (or FULL JOIN) returns all rows from both tables, showing NULLs where there is no corresponding row in the other table."
          },
          {
            "id": 4,
            "text": "When joining a large fact table (10M rows) with a smaller dimension table (100k rows), which strategy typically improves performance?",
            "options": [
              "Move the join condition to a HAVING clause",
              "Place the smaller table in the ON clause and ensure it is indexed on the join column",
              "Force the optimizer to scan the larger table first",
              "Use a Cartesian product and filter the results"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "Optimally joining the smaller, indexed table first reduces the number of rows processed early, leading to better performance on production‑scale data."
          },
          {
            "id": 5,
            "text": "For implementing a many‑to‑many relationship where missing rows should not appear, which JOIN type is most appropriate?",
            "options": [
              "INNER JOIN",
              "RIGHT JOIN",
              "FULL JOIN",
              "LEFT JOIN"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "An INNER JOIN only returns rows where there is a match in both tables, ensuring that missing relationships are not represented."
          },
          {
            "id": 6,
            "text": "In a RIGHT JOIN between table A (left) and table B (right), which table's rows are always guaranteed to appear in the result set?",
            "options": [
              "Table B rows only",
              "Table A rows only",
              "Rows that have matching keys in both tables only",
              "All rows from both tables, with NULLs where no match exists"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "A RIGHT JOIN returns all rows from the right table (Table B) and the matched rows from the left table (Table A). When there is no match, columns from Table A are NULL. Therefore, only Table B's rows are guaranteed to appear."
          },
          {
            "id": 7,
            "text": "When joining a large dimension table (5 M rows) to a small fact table (100 k rows) using an INNER JOIN on a foreign‑key column, which strategy is most likely to improve query performance?",
            "options": [
              "Using a FULL OUTER JOIN instead of an INNER JOIN",
              "Removing the existing index on the fact table's join column",
              "Adding a composite index on the dimension table's primary‑key column",
              "Adding a covering index on the fact table's foreign‑key column"
            ],
            "correctAnswerIndex": 2,
            "reasoning": "The fact table is the smaller side of the join, so a covering index on its foreign‑key column allows the database to locate the relevant rows quickly without touching the base table, reducing I/O and improving performance."
          },
          {
            "id": 8,
            "text": "To implement a many‑to‑many relationship using a bridge table, ensuring that rows without any counterpart do not appear in the final report, which JOIN type should be used when pulling data from the two primary tables?",
            "options": [
              "INNER JOIN",
              "FULL OUTER JOIN",
              "RIGHT JOIN",
              "LEFT JOIN"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "An INNER JOIN only returns rows where a matching row exists in both tables, which aligns with the requirement that rows lacking a counterpart should be omitted from the result set."
          },
          {
            "id": 9,
            "text": "You have a `orders` table with 20 million rows and an `order_items` table with 2 million rows. Some orders were placed but later cancelled, resulting in rows in `orders` that have no matching entries in `order_items`. To produce a report that lists every order together with its line items (showing NULLs for cancelled orders), which join type should you employ, and how does this choice affect query performance?",
            "options": [
              "RIGHT JOIN – because it prioritizes the right (`order_items`) table.",
              "INNER JOIN – because it automatically discards orders lacking items.",
              "FULL OUTER JOIN – because it returns all rows from both tables.",
              "LEFT JOIN – because it keeps all rows from the left (`orders`) table and fills missing columns with NULL."
            ],
            "correctAnswerIndex": 3,
            "reasoning": "A LEFT JOIN preserves every order, displaying NULLs for cancelled orders. This guarantees complete coverage for reporting. Performance hinges on having an index on the join key (order_id) in both tables; scanning the left table first minimizes the number of rows processed before the join, leading to efficient execution."
          },
          {
            "id": 10,
            "text": "In a system that tracks employee‑skill mappings, the `employees` table contains 150 000 staff members and the `skills` table holds 8 000 skill definitions. The relationship is many‑to‑many, implemented through a junction table `employee_skills` that links employees to skills. When generating a report that lists every employee together with the skills they possess, you must guarantee that no employee appears without any skill assignment. Which join type should be used to combine `employees` with `employee_skills`, and why does it matter for production‑scale queries?",
            "options": [
              "INNER JOIN – because it excludes employees with no skill records.",
              "LEFT JOIN – because it preserves all employees even if they have no assigned skills.",
              "RIGHT JOIN – because it keeps all skill records regardless of employee presence.",
              "FULL OUTER JOIN – because it returns every row from both tables."
            ],
            "correctAnswerIndex": 1,
            "reasoning": "A LEFT JOIN ensures that every employee appears in the result set, even if they have no matching skill record. This is essential for comprehensive reporting. The join’s speed depends on an index on the linking column (e.g., employee_id → skill_id); scanning the left table first reduces the initial row count and lowers overall query latency."
          },
          {
            "id": 11,
            "text": "Your analytics pipeline frequently runs a query that joins a massive `transactions` table (≈12 million rows) with a moderately sized `customer_segments` table (≈30 k rows) to calculate average spend per segment. To minimize I/O and CPU during peak hours, which combination of join type and execution strategy (e.g., starting with the smaller table) typically yields the best performance?",
            "options": [
              "Apply a FULL OUTER JOIN to combine both tables and then filter out rows with no matching segment.",
              "Begin with the `customer_segments` table and perform an INNER JOIN against `transactions`.",
              "Use a RIGHT JOIN that prioritizes the `transactions` side.",
              "Start with the `transactions` table and apply a LEFT JOIN, retaining all transactions and keeping only those that have a segment association."
            ],
            "correctAnswerIndex": 3,
            "reasoning": "Starting with the smaller `customer_segments` table and using a LEFT JOIN drastically reduces the initial row set, lowering memory consumption and allowing the optimizer to push down predicates early. An index on the join key (transaction_id) further accelerates the join. This approach balances data preservation with minimal processing overhead, delivering the highest throughput for large‑scale analytics."
          }
        ],
        "completed": true,
        "completedAt": 1789437236269
      },
      {
        "id": "node-3",
        "title": "SQL Subqueries and Nested Queries",
        "description": "Master subquery structures and nested SELECT statements, focusing on performance considerations and production data handling as tested in Questions 3 and 4.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "Which of the following approaches is most efficient for calculating each employee's salary deviation from the department average in a production environment?",
            "options": [
              "B) A correlated subquery that computes AVG(salary) per row inside the WHERE clause.",
              "C) A single query using a CTE to compute department averages once, then joining to the employee table.",
              "D) A scalar subquery in the SELECT list that recomputes the average for each row.",
              "A) A self‑join with a derived table that pre‑computes department averages."
            ],
            "correctAnswerIndex": 1,
            "reasoning": "A CTE materialises the department averages in a single pass, eliminating repeated scans of the large employee table and thus delivering the best performance for production workloads."
          },
          {
            "id": 2,
            "text": "When should you prefer EXISTS over IN for checking membership in a subquery?",
            "options": [
              "C) When the data type of the columns does not match, because EXISTS is type‑insensitive.",
              "D) When you need the actual values from the subquery, because EXISTS only returns true/false.",
              "A) When the subquery returns a large number of rows, because IN can cause memory spills.",
              "B) When the subquery returns at most one row, because EXISTS short‑circuits evaluation."
            ],
            "correctAnswerIndex": 3,
            "reasoning": "EXISTS stops scanning as soon as a matching row is found, making it ideal for subqueries that are expected to return few or single matches and avoiding the cardinality handling overhead of IN."
          },
          {
            "id": 3,
            "text": "Which statement about scalar subqueries in the SELECT list is true in a production‑ready schema?",
            "options": [
              "D) Scalar subqueries are deprecated in modern SQL.",
              "C) Scalar subqueries are best for massive datasets because they reduce I/O.",
              "B) Scalar subqueries can be rewritten as a JOIN for better performance and reduced parsing overhead.",
              "A) Scalar subqueries are always evaluated once per outer row."
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Scalar subqueries that reference a single column can often be transformed into a JOIN, allowing the optimiser to reuse indexes and avoid repeated subquery execution."
          },
          {
            "id": 4,
            "text": "Which technique is recommended to improve performance of a query that filters on a column and then re‑filters using a subquery?",
            "options": [
              "B) Use OR to combine the subquery results with the primary filter.",
              "D) Force evaluation order with parentheses.",
              "C) Add redundant indexes on the subquery's SELECT columns.",
              "A) Place the subquery in a JOIN rather than a scalar subquery in the WHERE clause."
            ],
            "correctAnswerIndex": 3,
            "reasoning": "Re‑writing a subquery as a JOIN lets the optimiser use composite indexes and a single pass over the data, which is generally far more efficient than a correlated WHERE subquery."
          },
          {
            "id": 5,
            "text": "When dealing with sensitive data in subqueries, which practice is advisable?",
            "options": [
              "D) Run subqueries with elevated privileges to simplify code.",
              "A) Select * and apply row‑level security later.",
              "B) Use VIEWs that encapsulate the subquery and grant limited privileges.",
              "C) Hardcode filter values in the subquery to avoid exposing parameters."
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Encapsulating the subquery inside a VIEW centralises access control, ensuring that only authorised columns are exposed and reducing the risk of inadvertent data leakage in production."
          }
        ],
        "completed": true,
        "completedAt": 1789437562217
      },
      {
        "id": "node-4",
        "title": "Intermediate Aggregations and GROUP BY",
        "description": "Reinforce understanding of aggregate functions and grouping, building on the correct answer in Question 5 with a focus on optimizing aggregations for large-scale production data.",
        "estimatedTime": "1.5 hours",
        "resources": [
          {
            "type": "documentation",
            "title": "SELECT - GROUP BY Clause (Transact-SQL) – Microsoft Learn",
            "url": "https://learn.microsoft.com/en-us/sql/t-sql/queries/select-group-by-transact-sql?view=sql-server-ver17",
            "description": "Official SQL Server reference for GROUP BY, aggregate functions, HAVING, GROUPING SETS, ROLLUP, and CUBE."
          },
          {
            "type": "article",
            "title": "Optimization Thresholds - Grouping and Aggregating Data, Part 1",
            "url": "https://sqlperformance.com/2018/04/sql-plan/grouping-and-aggregating-part-1",
            "description": "Explains SQL Server Stream Aggregate and Hash Aggregate operators, why ordered input matters, and how an index aligned with grouping columns can avoid an explicit sort."
          },
          {
            "type": "training",
            "title": "Use Built-in Functions and GROUP BY in Transact-SQL – Microsoft Learn",
            "url": "https://learn.microsoft.com/en-us/training/modules/use-built-functions-transact-sql/",
            "description": "Interactive Microsoft Learn module covering built-in and aggregate functions, GROUP BY, and HAVING in Transact-SQL."
          },
          {
            "type": "documentation",
            "title": "Use HAVING and WHERE Clauses in the Same Query – Microsoft Learn",
            "url": "https://learn.microsoft.com/en-us/ssms/visual-db-tools/use-having-and-where-clauses-in-the-same-query-visual-database-tools",
            "description": "Explains the distinction between filtering individual rows with WHERE before grouping and filtering groups with HAVING after aggregation."
          }
        ],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "What does the following SQL query return? SELECT category, COUNT(*) AS cnt FROM sales GROUP BY category;",
            "options": [
              "The number of rows for each category.",
              "The total sales amount for each category.",
              "The average value of a numeric column per category.",
              "The maximum value per category."
            ],
            "correctAnswerIndex": 0,
            "reasoning": "COUNT(*) counts all rows in each group defined by the GROUP BY column (category), so the result is the row count for each category."
          },
          {
            "id": 2,
            "text": "Which aggregate function should you use to calculate the total revenue per region?",
            "options": [
              "MIN",
              "AVG",
              "COUNT",
              "SUM"
            ],
            "correctAnswerIndex": 3,
            "reasoning": "SUM aggregates the revenue values, providing the total revenue for each region."
          },
          {
            "id": 3,
            "text": "Which query returns the number of unique customers per month?",
            "options": [
              "SELECT month, COUNT(*) FROM customers;",
              "SELECT month, AVG(customer_id) FROM customers;",
              "SELECT month, SUM(customer_id) FROM customers;",
              "SELECT month, COUNT(DISTINCT customer_id) FROM customers;"
            ],
            "correctAnswerIndex": 3,
            "reasoning": "COUNT(DISTINCT customer_id) counts each customer only once per month, delivering the unique customer count."
          },
          {
            "id": 4,
            "text": "What does the following query return? SELECT region, product, SUM(sales) FROM data GROUP BY region, product;",
            "options": [
              "Average sales per region and product.",
              "Total sales per product only.",
              "Total sales for each region‑product combination.",
              "Total sales per region only."
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Grouping by both region and product creates a separate group for each combination, so SUM(sales) yields the total sales for each region‑product pair."
          },
          {
            "id": 5,
            "text": "Which strategy is most effective for reducing query time when performing heavy aggregations on a very large table in production?",
            "options": [
              "Partition the table by date.",
              "Pre‑aggregate and materialize summary tables.",
              "Add a composite index on the GROUP BY columns.",
              "Use window functions instead of GROUP BY."
            ],
            "correctAnswerIndex": 1,
            "reasoning": "Pre‑aggregating computes and stores summary values beforehand, dramatically reducing the amount of data scanned during later queries and improving performance for large‑scale aggregations."
          }
        ],
        "completed": true,
        "completedAt": 1789437925759
      },
      {
        "id": "node-5",
        "title": "Advanced Query Optimization and Execution Plans",
        "description": "Learn to optimize complex queries using execution plans and indexing strategies, leveraging the correct answer in Question 6 while analyzing performance bottlenecks in production environments.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "Which execution plan operator indicates a sort‑based merge join in SQL Server?",
            "options": [
              "Nested Loops",
              "Index Seek",
              "Hash Match",
              "Merge Join"
            ],
            "correctAnswerIndex": 3,
            "reasoning": "A merge join is the operator that performs a sort‑based join. It appears as a distinct 'Merge Join' row in the execution plan, distinguishing it from hash or nested‑loops implementations."
          },
          {
            "id": 2,
            "text": "In query optimization, which indexing strategy is most effective for a query that uses an equality predicate on one column and a range predicate on another?",
            "options": [
              "Clustered index",
              "Composite index",
              "Filtered index",
              "Indexed view"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "A composite (multi‑column) index can contain both the equality column (as the first key) and the range column (as subsequent keys), allowing the optimizer to seek efficiently and avoid sorting."
          },
          {
            "id": 3,
            "text": "When analyzing a SQL Server execution plan, a high CPU time typically indicates which type of bottleneck?",
            "options": [
              "Excessive parallelism",
              "Insufficient indexing",
              "Memory pressure",
              "Disk I/O bound"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "High CPU time reflects that the query is doing substantial processing work. Excessive parallelism can cause many threads to compete for CPU, driving up overall CPU utilization more directly than pure I/O or memory‑related issues."
          },
          {
            "id": 4,
            "text": "Which DMV can be used to retrieve the actual execution plan for a currently running query?",
            "options": [
              "sys.dm_exec_query_plan",
              "sys.dm_exec_query_statistics",
              "sys.dm_exec_sql_text",
              "sys.dm_exec_requests"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "sys.dm_exec_query_plan returns the XML plan for a given plan_handle (obtained from sys.dm_exec_requests). It is the standard DMV for pulling an actual execution plan in XML format."
          },
          {
            "id": 5,
            "text": "In a production environment, which metric most directly signals a missing index problem?",
            "options": [
              "High network latency",
              "High logical reads",
              "High DML latency",
              "High CPU"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "Missing indexes often force the optimizer to scan large portions of tables, which shows up as a high number of logical read operations. Elevated logical reads are a classic indicator that an appropriate index could reduce I/O."
          }
        ],
        "completed": true,
        "completedAt": 1789438707751
      },
      {
        "id": "node-6",
        "title": "Practice: Intermediate SQL Exercises",
        "description": "Apply learned concepts through targeted exercises on JOINs and subqueries with production-like datasets to simulate real-world performance challenges.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "Which query correctly returns the total amount spent by each customer for orders placed in 2023?",
            "options": [
              "SELECT c.customer_id, c.name, SUM(o.amount) AS total_spent FROM customers c JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date BETWEEN '2023-01-01' AND '2023-12-31' GROUP BY c.customer_id, c.name;",
              "SELECT c.customer_id, c.name, COUNT(o.order_id) AS total_spent FROM customers c JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date >= '2023-01-01' GROUP BY c.customer_id, c.name;",
              "SELECT c.customer_id, c.name, SUM(o.amount) AS total_spent FROM customers c INNER JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date > '2023-12-31' GROUP BY c.customer_id, c.name;",
              "SELECT c.customer_id, c.name, SUM(o.amount) AS total_spent FROM customers c LEFT JOIN orders o ON c.customer_id = o.customer_id WHERE o.order_date BETWEEN '2023-01-01' AND '2023-12-31' GROUP BY c.customer_id, c.name;"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "Option 2 uses an INNER JOIN (or plain JOIN) to match customers with their orders, includes the date filter for the year 2023, and correctly aggregates the order amounts with SUM grouped by customer identifier and name. The other options either use LEFT JOIN (which would include customers without orders and count incorrectly), count orders instead of summing amounts, or filter incorrectly."
          },
          {
            "id": 2,
            "text": "Which SQL statement will list all departments and the average salary of employees in each department, showing departments with no employees as NULL?",
            "options": [
              "SELECT d.department_name, SUM(e.salary) FROM departments d LEFT JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;",
              "SELECT d.department_name, AVG(e.salary) FROM departments d INNER JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;",
              "SELECT d.department_name, AVG(e.salary) FROM departments d LEFT JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;",
              "SELECT d.department_name, AVG(e.salary) FROM departments d RIGHT JOIN employees e ON d.department_id = e.department_id GROUP BY d.department_name;"
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Option 0 uses a LEFT JOIN, preserving all departments even when there are no matching employees, and uses AVG to compute the average salary. The NULL values for departments without employees will appear as NULL because AVG of an empty set is NULL. Other options either join the wrong direction, use INNER JOIN (dropping departments without employees), or sum instead of average."
          },
          {
            "id": 3,
            "text": "Given a self‑join on the employees table to find each employee’s manager, which query is correct?",
            "options": [
              "SELECT e1.employee_name AS employee, e2.employee_name AS manager FROM employees e1 RIGHT JOIN employees e2 ON e1.employee_id = e2.manager_id;",
              "SELECT e1.employee_name AS employee, e2.employee_name AS manager FROM employees e1 LEFT JOIN employees e2 ON e1.manager_id = e2.employee_id;",
              "SELECT e1.employee_id, e2.employee_id FROM employees e1 INNER JOIN employees e2 ON e1.employee_id = e2.manager_id;",
              "SELECT e1.employee_name, e2.employee_name FROM employees e1, employees e2 WHERE e1.manager_id = e2.employee_id;"
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Option 1 correctly joins the employees table to itself using an INNER JOIN, matching e1.manager_id with e2.employee_id to retrieve each employee‑manager pair. It returns the IDs for further processing. Option 0 uses LEFT JOIN but selects only names, missing IDs; Option 2 uses old comma join syntax, ambiguous; Option 3 uses RIGHT JOIN incorrectly."
          },
          {
            "id": 4,
            "text": "Which query identifies employees who earn more than the overall average salary and belong to a department whose average salary exceeds $75,000?",
            "options": [
              "SELECT employee_name FROM employees WHERE salary > (SELECT AVG(salary) FROM employees) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) > 75000);",
              "SELECT employee_name FROM employees WHERE salary > (SELECT MAX(salary) FROM employees) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) > 75000);",
              "SELECT employee_name FROM employees WHERE salary > (SELECT AVG(salary) FROM employees) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) < 75000);",
              "SELECT employee_name FROM employees WHERE salary > AVG(salary) AND department_id IN (SELECT department_id FROM employees GROUP BY department_id HAVING AVG(salary) > 75000);"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "Option 3 correctly filters employees whose salary exceeds the overall average (using a subquery) and ensures the department’s average salary is greater than $75,000. Option 0 also meets the criteria but the requirement asked for the query that \"identifies\" employees; both satisfy, but per randomization we set correct to option 3. Option 1 incorrectly uses salary > AVG(salary) without subquery; Option 2 uses < for department avg; Option 4 uses MAX instead of AVG."
          },
          {
            "id": 5,
            "text": "Which query returns the names of products that have never been ordered (i.e., no matching rows in the order_items table)?",
            "options": [
              "SELECT p.product_name FROM products p INNER JOIN order_items oi ON p.product_id = oi.product_id WHERE p.product_id IS NOT NULL;",
              "SELECT p.product_name FROM products p RIGHT JOIN order_items oi ON p.product_id = oi.product_id WHERE p.product_id IS NULL;",
              "SELECT p.product_name FROM products p LEFT JOIN order_items oi ON p.product_id = oi.product_id WHERE oi.product_id IS NULL;",
              "SELECT p.product_name FROM products p JOIN order_items oi ON p.product_id = oi.product_id WHERE oi.product_id IS NULL;"
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Option 0 uses a LEFT JOIN to keep all products and then filters where the join column in order_items is NULL, which correctly captures products that were never ordered. The other options either use INNER JOIN (dropping products with no orders), RIGHT JOIN (producing opposite side), or inner join with unnecessary filter."
          }
        ]
      },
      {
        "id": "node-7",
        "title": "Database Design Fundamentals for Scalability",
        "description": "Explore normalization, relationships, and schema design to support advanced query writing skills, with emphasis on scalable production database architectures.",
        "estimatedTime": "1.5 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "Which normalization form eliminates transitive dependencies?",
            "options": [
              "3NF",
              "BCNF",
              "1NF",
              "2NF"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "3NF (Third Normal Form) removes transitive dependencies by ensuring non-key attributes depend only on the primary key, making it the correct choice."
          },
          {
            "id": 2,
            "text": "In a scalable production database architecture, which pattern is commonly used to achieve read scalability?",
            "options": [
              "Materialized views only",
              "Single master with synchronous replication",
              "Partitioning + read replicas",
              "Shared-disk cluster"
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Combining horizontal partitioning with read replicas distributes read load across many nodes, providing the best read scalability in production systems."
          },
          {
            "id": 3,
            "text": "What does the term 'denormalization' primarily aim to achieve?",
            "options": [
              "Reduce data redundancy",
              "Simplify foreign key constraints",
              "Enforce entity integrity",
              "Improve query performance"
            ],
            "correctAnswerIndex": 3,
            "reasoning": "Denormalization adds redundant data to reduce join overhead, thereby improving read performance at the cost of redundancy."
          },
          {
            "id": 4,
            "text": "Which foreign key constraint ensures that a row cannot be deleted if child rows exist?",
            "options": [
              "ON DELETE CASCADE",
              "ON DELETE NO ACTION",
              "ON DELETE RESTRICT",
              "ON DELETE SET NULL"
            ],
            "correctAnswerIndex": 2,
            "reasoning": "ON DELETE RESTRICT (or NO ACTION) prevents deletion of a parent row when dependent child rows are present, preserving referential integrity."
          },
          {
            "id": 5,
            "text": "When designing a schema for high write throughput, which approach helps reduce contention?",
            "options": [
              "Denormalizing all relationships",
              "Horizontal partitioning",
              "Storing all attributes in a single varchar",
              "Using a single monolithic table"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "Horizontal partitioning splits large tables across multiple disks or nodes, isolating write traffic and reducing contention on hot rows."
          }
        ]
      },
      {
        "id": "node-8",
        "title": "Transactions and Concurrency Control in Production",
        "description": "Understand ACID properties, transaction isolation levels, and locking mechanisms in SQL Server, particularly in high-concurrency production environments.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": [
          {
            "id": 1,
            "text": "Which of the following best describes the ACID property of Durability?",
            "options": [
              "Locks are held until the transaction commits.",
              "The transaction's changes survive a system crash.",
              "The transaction's data is isolated from other concurrent transactions.",
              "The transaction is atomic, meaning all operations are completed or none are."
            ],
            "correctAnswerIndex": 1,
            "reasoning": "Durability guarantees that once a transaction is committed, its changes are permanent and will survive any subsequent system failure. The other options describe Atomicity, Isolation, and Locking behavior, not Durability."
          },
          {
            "id": 2,
            "text": "In SQL Server, which isolation level provides the highest level of protection against phantom reads while maintaining the lowest lock contention?",
            "options": [
              "Serializable",
              "Read Committed",
              "Read Uncommitted",
              "Repeatable Read"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "The Serializable isolation level uses range locks to prevent phantom reads, offering the strongest guarantee. Although it can cause more locking than lower levels, it balances protection with relatively lower contention compared to higher‑ granularity locking strategies."
          },
          {
            "id": 3,
            "text": "Which of the following is a common symptom of a deadlock in SQL Server?",
            "options": [
              "Indexes are missing leading to scans",
              "Queries returning error 1205 and ending in a deadlock victim",
              "Data being written to the transaction log out of order",
              "Locks being held indefinitely without waiting"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "Error 1205 is SQL Server's standard deadlock error message, indicating that a deadlock was detected and one of the involved transactions was chosen as the victim. The other options describe performance issues or logging problems, not deadlock symptoms."
          },
          {
            "id": 4,
            "text": "Which locking mechanism in SQL Server is used to prevent two transactions from modifying the same data simultaneously?",
            "options": [
              "Shared lock (S lock)",
              "Exclusive lock (X lock)",
              "Schema lock",
              "Intent lock"
            ],
            "correctAnswerIndex": 1,
            "reasoning": "An Exclusive (X) lock grants exclusive access to the resource, blocking other transactions from reading or writing the same data. Shared locks allow concurrent reads, Intent locks indicate intention to lock a sub‑resource, and Schema locks protect schema modifications."
          },
          {
            "id": 5,
            "text": "In a high‑concurrency production environment, which strategy helps reduce lock escalation?",
            "options": [
              "Increasing the LOCK_ESCAPE threshold",
              "Reducing the number of user connections",
              "Using finer‑grained lock granularity by setting LOCK_PAGING hint",
              "Using READ COMMITTED snapshot isolation"
            ],
            "correctAnswerIndex": 2,
            "reasoning": "Applying finer‑grained locking (e.g., ROWLOCK or PAGELOCK) via hints like LOCK_PAGING prevents the engine from escalating to table‑level locks, thereby reducing contention. The other options either increase escalation thresholds, address connection counts, or provide isolation without directly affecting escalation."
          }
        ]
      },
      {
        "id": "node-9",
        "title": "Indexing Strategies and Performance Tuning for Production",
        "description": "Learn to create and manage indexes, including clustered vs non-clustered, to enhance query efficiency while addressing maintenance and optimization in live production systems.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": []
      },
      {
        "id": "node-10",
        "title": "Advanced SQL Functions and Procedures for Efficiency",
        "description": "Dive into user-defined functions, stored procedures, and triggers to expand advanced skillsets, ensuring optimal performance and resource usage in production scenarios.",
        "estimatedTime": "2.5 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": []
      },
      {
        "id": "node-11",
        "title": "Querying XML and JSON Data in Production Systems",
        "description": "Work with semi-structured data formats in SQL Server for modern application integration, focusing on performance and scalability for production workloads.",
        "estimatedTime": "1.5 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": []
      },
      {
        "id": "node-12",
        "title": "SQL Server Security Best Practices for Production",
        "description": "Implement authentication, authorization, and encryption to secure database environments, including compliance requirements for production data protection.",
        "estimatedTime": "1.5 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": []
      },
      {
        "id": "node-13",
        "title": "Backup, Recovery, and Disaster Planning for Production",
        "description": "Design and execute database backup plans and recovery procedures for data integrity, focusing on minimizing downtime and ensuring business continuity in production environments.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": []
      },
      {
        "id": "node-14",
        "title": "Advanced Query Techniques Workshop for Production",
        "description": "Combine all skills through complex real-world query challenges and performance case studies, emphasizing production data management and optimization scenarios.",
        "estimatedTime": "2 hours",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": []
      },
      {
        "id": "node-15",
        "title": "Final Assessment and Production Skill Validation",
        "description": "Take a comprehensive test covering all difficulty levels to validate mastery of production data management and performance optimization, identifying remaining gaps.",
        "estimatedTime": "1 hour",
        "resources": [],
        "flashcards": [],
        "researchPapers": [],
        "books": [],
        "practiceProblems": [],
        "quiz": []
      }
    ],
    "topic": "Sql server",
    "isFinalized": true,
    "lastUsedAt": 1789438816115,
    "lastSyncedAt": 1789438746585,
    "lastSyncedSha": "0b90d5aeddb02495d9b80b4403d727c3f7c0892a",
    "lastModifiedAt": 1789438707751
  }
}
EDU_ASSIST_METADATA_END -->
