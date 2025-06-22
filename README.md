# Hospital-Management-Database-Project
SQL Server database project with tables, stored procedures, triggers, and functions for hospital management.


# 🏥 Hospital Management Database Project

A structured and normalized SQL Server database project that simulates core functionalities of a hospital management system. It includes table definitions, sample data, stored procedures, views, triggers, and user-defined functions to manage and automate various hospital operations such as patient registration, doctor assignments, and reporting.

---

## 📌 Project Overview

This project was developed as part of an Advanced Database Management Systems course to demonstrate a real-world implementation of a relational database using SQL Server Management Studio (SSMS). It represents how data-driven solutions can help streamline hospital processes and ensure data integrity, security, and accessibility.

---

## 🎯 Objectives

- 📊 Design a relational database for hospital operations with normalized structure.
- 🛠️ Implement SQL scripts to create tables, insert data, and define logical relationships.
- 🔄 Develop reusable stored procedures for patient, doctor, and appointment operations.
- 🔍 Create views for easy reporting and data aggregation.
- 🔔 Implement triggers to enforce business rules and automate system responses.
- 🧠 Define user-defined functions to support modular operations.

---

A glimpse of the ERD Diagram

![Hospital_Management](https://github.com/user-attachments/assets/10ae58c4-1e16-4f1c-8476-58e25d308c5b)

---

## ✅ Key Features

- Fully normalized schema with primary and foreign key constraints.
- Separate SQL scripts for modular design and easy execution.
- Sample data for testing and demonstration purposes.
- Logic encapsulated using:
  - Stored Procedures
  - Triggers
  - Views
  - User-defined Functions
- Easy to set up and run on any SQL Server instance using SSMS.

---

## 📁 Folder & File Structure

| File Name               | Description                                                  |
|-------------------------|--------------------------------------------------------------|
| `Create_Tables.sql`     | Contains all `CREATE TABLE` statements for the database.     |
| `Insert_Data.sql`       | Inserts sample records into all major tables.                |
| `Stored_Procedures.sql` | Contains procedures for querying and updating data.          |
| `Views.sql`             | Contains database views for streamlined data access.         |
| `Triggers.sql`          | Defines triggers for actions like logging or enforcing rules.|
| `Functions.sql`         | User-defined functions for calculations like age, etc.       |

---

## 🧰 Tools & Technologies Used

- **SQL Server Management Studio (SSMS)**
- **T-SQL (Transact-SQL)**
- **SQL Server Express / Developer Edition** (for local execution)
- ERD tools (optional) to visualize schema

---

## ⚙️ How to Run This Project

1. Open **SQL Server Management Studio (SSMS)**.

2. Create a new database in your server:
  
3. CREATE DATABASE HospitalDB;

Select the HospitalDB database.

4. Execute the following .sql files in order:

Create_Tables.sql

Insert_Data.sql

Stored_Procedures.sql

Views.sql

Triggers.sql

Functions.sql

6. Query the database using your own SELECT statements or call stored procedures to see results.

---

📚 Learning Outcomes

By working with this project, you will understand how to:

Design normalized databases with real-world relationships

Implement SQL DDL and DML operations

Write and use stored procedures and triggers

Use views and functions to enhance modularity and clarity

Manage real-world business logic inside a database system

---

💬 Feedback
If you find this project useful or have suggestions for improvement, feel free to open an issue or submit a pull request.

---

👩‍💻 Author

Sai Sindhuja Rama.

[Github](https://github.com/sindhujarama26)

[LinkedIn](https://www.linkedin.com/in/sai-sindhuja-rama-07b6a7370/)

