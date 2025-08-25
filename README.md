# 🏥 Hospital Management Database System

## 📌 1. Project Title
**Hospital Management Database System**

---

## ✅ 2. Objectives
- Design a **fully normalized relational database** for hospital operations.
- Implement **14 interrelated tables** as per the ER diagram.
- Populate each table with **20+ records** for testing and analysis.
- Execute **SQL queries** to demonstrate real-world hospital operations such as:
    - Appointments
    - On-call nurses
    - Physician specializations
    - Medication prescriptions
    - Room allocations
- Enforce **data integrity** with **Primary Keys (PK)** and **Foreign Keys (FK)**.

---

## 🛠 3. Tools & Technologies
- **Database Engine**: SQLite / MySQL (scripts compatible)
- **ER Design Tool**: Oracle Data Modeler / Draw.io
- **Languages**: SQL
- **Files in this Repository**:
    - [`Database.sql`](./Database.sql) – Full schema & data population
    - [`queries.sql`](./queries.sql) – Set of complex queries
    - [`HOSPITAL DATABASE Information.docx`](./HOSPITAL%20DATABASE%20Information.docx) – Project report
    - [`Relational Diagram.pdf`](./Relational%20Diagram.pdf) – ER Diagram

---

## 🔍 4. Process
### **Step 1: Database Design**
- Derived **14 tables** from ER diagram ([View ER Diagram](./Relational%20Diagram.pdf)).
- Implemented **Primary Keys**, **Composite Keys**, and **Foreign Keys** as per relational constraints.

### **Step 2: Implementation**
- **Schema creation & population**:
    - [`Database.sql`](./Database.sql) contains:
        - `CREATE TABLE` statements for 14 tables.
        - `INSERT INTO` statements with **20+ sample rows per table**.
- **Query execution**:
    - [`queries.sql`](./queries.sql) demonstrates **39 complex queries**, including:
        - Joins, aggregations, subqueries, nested queries.
        - Analytical queries like finding the busiest physician, available rooms, etc.

### **Step 3: Testing**
- Executed queries on the populated dataset.
- Verified **referential integrity** and **correct outputs**.

---

## 🗄 5. Database Schema
The database consists of **14 interrelated tables**:

1. `Block`  
2. `Room`  
3. `Nurse`  
4. `Physician`  
5. `Department`  
6. `Appointment`  
7. `Patient`  
8. `Stay`  
9. `Procedure`  
10. `Trained_in`  
11. `Affiliated_with`  
12. `Prescribes`  
13. `Medication`  
14. `Undergoes`  
15. `On_call`  

*(As per [Relational Diagram.pdf](./Relational%20Diagram.pdf))*

---

## 🌟 6. Key Features
- **Composite Primary Keys** in junction tables:
    - `Undergoes`, `On_call`, `Trained_in`, `Affiliated_with`
- **Referential Integrity** maintained:
    - Every foreign key references the correct parent table.
- **Sample Data Volume**:
    - Each table populated with **20+ entries** for testing.

---

## 🔍 7. Query Demonstration
- [`queries.sql`](./queries.sql) includes:
    - List of **registered and unregistered nurses**.
    - Find **physicians who are department heads**.
    - Calculate **room availability by floor and block**.
    - Identify **patients with multiple appointments**.
    - Detect **violations of training certifications**.

---

## ✅ 8. Outcomes
- Successfully implemented a **normalized hospital database**.
- Achieved **data integrity** through PK-FK relationships.
- Tested real-world scenarios with **complex queries**.

---

## ▶ 9. How to Run
1. Import `Database.sql` in your database engine (SQLite, MySQL).
2. Run `queries.sql` for validations and analytics.
3. Use **DB Browser for SQLite** or **MySQL Workbench** for visualization.

---

## 📂 10. Proofs & Links
- **ER Diagram**: [Relational Diagram.pdf](./Relational%20Diagram.pdf)
- **Schema & Data**: [Database.sql](./Database.sql)
- **Queries**: [queries.sql](./queries.sql)
- **Project Documentation**: [HOSPITAL DATABASE Information.docx](./HOSPITAL%20DATABASE%20Information.docx)

---

### ✅ Author
**Developed by:** *[Your Name]*  
**Course/Project:** Database Management System Project

---
