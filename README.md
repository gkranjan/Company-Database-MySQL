# 🏢 Company Database Management System – MySQL

## 📌 Project Overview

The **Company Database Management System** is a relational database project developed using MySQL to manage and organize company-related information efficiently.

This project demonstrates practical SQL database design concepts, including table creation, primary keys, foreign keys, relationships, constraints, data insertion, and database management.

It represents a company environment where employee information, department details, project assignments, and working hours are maintained in a structured database.

## 🎯 Project Objectives

- Design a structured relational database for company operations.
- Maintain employee and department information.
- Manage company projects and employee project assignments.
- Establish relationships between multiple tables using foreign keys.
- Practice real-world SQL queries and database operations.
- Understand relational database design and data integrity.

## 🗄️ Database Information

**Database Name:** `company_db`

**Database Technology:** MySQL 8.0

## 📂 Database Tables

| Table Name | Description |
|---|---|
| `employees` | Stores employee details, salary, email and manager information. |
| `departments` | Maintains department names and locations. |
| `projects` | Stores project names and budgets. |
| `employee_projects` | Maintains employee-project assignments and working hours. |
| `customers` | Stores customer information and registration details. |
| `restaurants` | Stores restaurant names and ratings. |

## 🔗 Database Relationships

- Employees are associated with departments.
- Employees can report to other employees through a self-referencing relationship.
- Employees can participate in multiple projects.
- Projects can have multiple employees assigned.
- The `employee_projects` table manages the many-to-many relationship between employees and projects.

## 🛠️ SQL Concepts Covered

- Database Creation and Selection
- CREATE TABLE
- INSERT INTO
- SELECT Statements
- Primary Key
- Foreign Key
- UNIQUE Constraint
- NOT NULL Constraint
- AUTO_INCREMENT
- Relational Database Design
- One-to-Many Relationships
- Many-to-Many Relationships
- Self-Referencing Foreign Keys
- Table Structure and Data Management

## 📁 Project Structure

```text
Company-Database-MySQL/
│
├── company_db.sql
│
└── README.md
```

## 🚀 How to Run This Project

**Step 1:** Install MySQL Server 8.0 or a compatible version.

**Step 2:** Open MySQL Command Line or MySQL Workbench.

**Step 3:** Execute the SQL file:

```sql
SOURCE C:/path/to/company_db.sql;
```

**Step 4:** Select the database:

```sql
USE company_db;
```

**Step 5:** View available tables:

```sql
SHOW TABLES;
```

**Step 6:** Retrieve employee records:

```sql
SELECT * FROM employees;
```

## 💡 Practical Use Cases

- Employee information management
- Department-wise employee organization
- Project allocation and tracking
- Employee salary management
- Manager and employee hierarchy
- Employee working-hours tracking

## 📌 Future Enhancements

- Add advanced SQL JOIN queries.
- Implement subqueries and correlated subqueries.
- Create views for employee and department reports.
- Implement stored procedures and functions.
- Add triggers for automated database operations.
- Perform employee salary and project-budget analysis.
- Optimize queries using indexes.

## 👨‍💻 Author

**Gautam Kumar Ranjan**

GitHub: [@gkranjan](https://github.com/gkranjan)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.

**Technology:** MySQL | SQL | Relational Database Management System
