# online-food-ordering-sql-project

# 🍔 Online Food Ordering Database System (SQL Project)

## 📌 Project Overview

This project is a fully designed relational database system for an Online Food Ordering Platform.

It simulates the backend database of a food delivery system where users can:
- Register and place orders
- View restaurants and menus
- Make payments
- Track order status

The system is built using pure SQL and demonstrates advanced database concepts including normalization, constraints, indexing, triggers, views, and stored procedures.

---

## 🛠 Technologies Used

- MySQL
- SQL (DDL, DML, DQL)
- Relational Database Design

---

## 🗄 Database Features

### ✔ Core Tables
- Users
- Restaurants
- Menu
- Orders
- Order_Items
- Payments

### ✔ Advanced Features
- Primary & Foreign Keys
- CHECK Constraints
- UNIQUE Constraints
- Indexing for performance optimization
- ON DELETE CASCADE
- Triggers for automation
- Stored Procedures for business logic
- Views for reporting
- Window Functions for ranking

---

## 📁 Project Structure
food-ordering-sql-project/
│
├── schema.sql → Database structure
├── sample_data.sql → Test data (50+ records)
├── queries.sql → Basic & advanced queries
├── views.sql → Reporting views
├── triggers.sql → Automation logic
├── procedures.sql → Stored procedures
└── README.md



---

## 🔥 Key Functionalities

### 1️⃣ Order Placement
- Orders are inserted via stored procedure.
- Total amount auto-calculated using trigger.

### 2️⃣ Revenue Analysis
- Restaurant-wise revenue
- Monthly revenue reports
- Top customers ranking

### 3️⃣ Data Integrity
- Menu items cannot have duplicate names per restaurant.
- Negative price updates prevented.
- Invalid payment statuses restricted.
- Cascade delete ensures referential integrity.

---

## 📊 Example Business Queries

- Top 5 Customers by Spending
- Most Ordered Item
- Average Order Value
- Monthly Revenue
- Pending Payments
- Restaurant Revenue Ranking

---

## 🧠 Advanced Concepts Demonstrated

- INNER JOIN, LEFT JOIN
- GROUP BY & HAVING
- Aggregate Functions
- Window Functions (RANK)
- Index Optimization
- Triggers (BEFORE & AFTER)
- Stored Procedures with Parameters
- LAST_INSERT_ID()
- Data Validation using CHECK constraints

---

## 🚀 How to Run the Project

1. Run [schema.sql](https://github.com/user-attachments/files/25710046/schema.sql)

2. Run [sample_data.sql](https://github.com/user-attachments/files/25710062/sample_data.sql)
`
3. Run [views.sql](https://github.com/user-attachments/files/25710096/views.sql)
`
4. Run [triggers.sql](https://github.com/user-attachments/files/25710103/triggers.sql)
`
5. Run [procedures.sql](https://github.com/user-attachments/files/25710104/procedures.sql)
`
6. Execute queries from [queries.sql](https://github.com/user-attachments/files/25710127/queries.sql)
`

---

## 🎯 Learning Outcome

This project demonstrates strong understanding of:

- Relational Database Design
- Data Integrity & Constraints
- Business Logic Implementation in SQL
- Performance Optimization
- Real-world Backend Database Architecture

---

## 👨‍💻 Author

ADAMU ALAMURI
