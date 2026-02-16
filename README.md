# JDBC Operations Project

## 📌 Project Description
This project demonstrates basic JDBC (Java Database Connectivity) operations using MySQL database.

It includes programs to perform:

- Select Employee Records
- Update Employee Records
- Delete Employee Records

These programs connect to a MySQL database and execute SQL queries using JDBC.

---

## 🛠 Technologies Used

- Java
- JDBC API
- MySQL Database
- MySQL Connector/J
- Git & GitHub

---

## 📂 Project Files

- selection-emp.java → Fetches employee records from database
- update-emp.java → Updates employee data
- delete-emp.java → Deletes employee record

---

## ⚙️ Database Setup

1. Install MySQL
2. Create database:

```sql
CREATE DATABASE jdbc_db;
USE jdbc_db;

CREATE TABLE employee (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    salary DOUBLE
);
