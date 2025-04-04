# SQL Tasks on Employee Database

This project contains a series of SQL tasks focused on analyzing employee data from a database. The tasks cover a variety of SQL techniques, including **JOINs**, **Window Functions**, and aggregate queries. Each task is aimed at extracting meaningful insights from the employee database.

---

## Task 1: Display a List of 10 Employees with Their Current Salary

**Objective:**  
Retrieve the first 10 employees (randomly) with their `emp_no`, `first_name`, `last_name`, and their current salary. The order of the employees doesn't matter, the goal is to obtain the correct structure.

---

## Task 2: Display a List of 10 Employees with Their Current Job Title

**Objective:**  
Retrieve a list of 10 employees with their `emp_no`, `first_name`, `last_name`, and their current job title. The order of employees doesn't matter, only the correct structure is important.

---

## Task 3: Display a List of 10 Employees with Their Current Department

**Objective:**  
Retrieve the first 10 employees with their `emp_no`, `first_name`, `last_name`, and the department they currently work in. Again, the order is not important, but the correct structure is required.

---

## Task 4: Employee Distribution by Department: Count of Unique Employees

**Objective:**  
Find the count of unique employees in each department and present this information sorted by the department with the most employees.

---

## Task 5: Find the Highest Paid Employee in the Development Department

**Objective:**  
Find the highest paid employee in the **Development** department, returning their `emp_no`, `first_name`, `last_name`, and their current salary.

---

## Task 6: Find the Department of the Highest Paid Employee in the Company

**Objective:**  
Find the department of the highest paid employee in the company. Return their `emp_no`, `first_name`, `last_name`, `salary`, and the `dept_name` of their department.

---

## Task 7: Find the Employee with the Third Highest Salary

**Objective:**  
Retrieve the employee with the third highest salary. Output the `emp_no`, `first_name`, `last_name`, and salary for that employee.

---

## Task 8: Find Employees with Multiple Job Titles

**Objective:**  
Identify employees who have held multiple job titles during their tenure at the company. For each such employee, output their `emp_no`, `first_name`, `last_name`, and the list of job titles they held.

---

## Task 9: Find Employees Who Have Worked in Multiple Departments

**Objective:**  
Identify employees who have worked in more than one department. Output their `emp_no`, `first_name`, `last_name`, and the list of departments they have worked in.

---

## Task 10: Current Salary of Department Managers

**Objective:**  
For each department, output the department name, the `emp_no` of the current manager, their `first_name`, `last_name`, and their current salary.

---

## Task 11: Task on Using Window Functions

### Task 11.1: Using ROW_NUMBER

**Objective:**  
For the first 10 employees (by `emp_no`), display their `emp_no`, `first_name`, `last_name`, and their position number within the table using the `ROW_NUMBER()` function.

---

### Task 11.2: Salary History of an Employee

**Objective:**  
For the employee with `emp_no = 10001`, display their `emp_no`, the `from_date`, their salary, and the previous salary value for comparison.

---

### Task 11.3: Salary Rank within Department

**Objective:**  
For each employee, display their `emp_no`, `dept_name`, current salary, and their rank within the department based on salary using a window function.

---

### Task 11.4: Salary Change Over the Last 2 Years

**Objective:**  
Display the salary difference for the employee with `emp_no = 10001` between their current salary and the salary 2 years ago. The result should include `emp_no`, the salary from 2 years ago, the current salary, and the difference.

---

### Task 11.5: Determining the Highest Salary Increase

**Objective:**  
Identify the employee who received the largest salary increase within the last year, using the maximum `from_date` from the salary history. Display the `emp_no`, the salary from the previous year, the current salary, and the difference.

---

### Task 11.6: Salary Dynamics

**Objective:**  
Track the salary change of an employee (identified by `emp_no = 10001`) over time, showing the progression of salary for this employee.

---

## Task 12: Using NTILE

**Objective:**  
Distribute the specified employees into 3 groups based on their current salary using the `NTILE()` function. Display each employee's `emp_no`, `first_name`, `last_name`, salary, and group number.

---

### Notes:

- The project uses SQL functions such as `JOIN`, `GROUP BY`, `ORDER BY`, `NTILE`, `ROW_NUMBER()`, and window functions for data analysis and transformation.
- The employee database includes tables like `employees`, `departments`, `salaries`, `dept_emp`, and `titles`.

