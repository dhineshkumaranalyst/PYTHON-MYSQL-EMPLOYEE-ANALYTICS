# Python MySQL Employee Analytics

A beginner-friendly Data Analytics project using **Python and MySQL** to connect with an employee database and perform basic SQL-based analysis.

## 📌 Project Overview

This project demonstrates how Python can connect to a MySQL database and retrieve employee data using SQL queries.

The project focuses on three basic analytics operations:

- View employee details
- Calculate average salary
- Find the highest-paid employee

## 🛠️ Technologies Used

- **Python**
- **MySQL**
- **SQL**
- **MySQL Connector/Python**

## 📊 Project Features

### 1. Employee Details
Retrieves and displays all employee records from the MySQL database.

### 2. Average Salary
Calculates the average salary of all employees using the SQL `AVG()` function.

### 3. Highest-Paid Employee
Identifies the employee with the highest salary using `ORDER BY` and `LIMIT`.

## 🗄️ Database

**Database:** `employee_analytics`

**Table:** `employees`

### Main Columns

| Column | Description |
|---|---|
| emp_id | Employee ID |
| emp_name | Employee Name |
| age | Employee Age |
| department | Department |
| salary | Employee Salary |
| joining_date | Joining Date |

## 🔗 Python–MySQL Connection

The project uses `mysql-connector-python` to establish a connection between Python and MySQL.

Install the required package:

```bash
pip install mysql-connector-python
