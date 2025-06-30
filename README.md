
# Task 5 - SQL Joins 

##  Objective
To master INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL OUTER JOIN using EMPLOYEES and DEPT tables.

##  Tables Used
### DEPT
- DEPTNO (Primary Key)
- DNAME (Unique)
- LOCATION

### EMPLOYEES
- EMPNO (Primary Key)
- ENAME
- JOB
- MGR
- HIREDATE
- SALARY
- DEPTNO (Foreign Key referencing DEPT)

##  Data Inserted
3 Departments and 5 Employees with various job roles and department assignments.

##  SQL JOIN Queries Demonstrated

- **INNER JOIN**: To fetch employees along with department details where matching department exists.
- **LEFT JOIN**: To fetch all employees with department details, if available.
- **RIGHT JOIN**: To fetch all departments and the employees in them, if available.
- **FULL OUTER JOIN (Simulated)**: Combined LEFT and RIGHT JOIN using UNION to fetch all employees and departments.

##  Tools Used
- MySQL Workbench / SQLite
- SQL standard syntax (MySQL-compatible)

##📎 Submission
- SQL File: `task5.sql`
- README File: `README.md`

