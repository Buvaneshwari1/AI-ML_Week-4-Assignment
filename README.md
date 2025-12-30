# AI-ML_Week-4-Assignment


## SQL Window Functions Assignment

## Project Overview
This repository demonstrates the usage of **SQL Window Functions** using two sample tables.  
The objective of this project is to understand and apply commonly used analytical functions in SQL with clear examples and proper documentation.


## Database Tables

### 1️ Employees
Stores employee-related information.

| Column Name | Data Type |
|------------|----------|
| emp_id | INT (Primary Key) |
| emp_name | VARCHAR |
| department | VARCHAR |
| salary | INT |
| hire_date | DATE |

---

### 2️ Attendance
Stores employee login and logout details.

| Column Name | Data Type |
|------------|----------|
| attendance_id | INT (Primary Key) |
| emp_id | INT |
| login_time | TIMESTAMP |
| logout_time | TIMESTAMP |

---

## SQL Concepts Covered

This project includes examples of the following SQL functions:

### 🕒 TIME Functions
- `EXTRACT()`
- `TIMESTAMPDIFF()`
Used to calculate login hour and total working hours.

### ROW_NUMBER()
Assigns a unique number to each row based on salary order.

### RANK()
Ranks employees based on salary (with gaps).

### DENSE_RANK()
Ranks employees without gaps in ranking.

### PARTITION BY
Applies ranking within each department.

### FIRST_VALUE()
Retrieves the highest salary in each department.

### PERCENT_RANK()
Displays the percentile ranking of employee salaries.

