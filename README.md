![sIB2EnSTFqWKFPJ7k1W7QCYAqaIn8OZ8b9s7X9QDRhzJrinGp10WGMkcRPlEGgzI0cx3uN_NwJ1B99gmx5UyimDtZuFYyuwjarOdWelN6iaQdCiA415kIcfdWampTJrGj803El4vlB201kAWQltjFRR5uoxadiCFRK6kZVqNisA](https://github.com/user-attachments/assets/91438174-0049-4d5d-a48a-2378af4e76db)# 🛒 SQL E-Commerce Database Project

### 👨‍💻 Created by: Tripathi

---

## 📌 Project Overview

This is my first SQL project where I designed and implemented a complete **E-Commerce Database System**.
The project includes database creation, table relationships, sample data insertion, and analytical queries.

---

## 🧱 Database Structure

The project consists of the following tables:

### 1. Customers

* Stores customer information
* Fields: `customer_id`, `name`, `email`, `city`, `signup_date`

### 2. Products

* Contains product details
* Fields: `product_id`, `product_name`, `category`, `price`, `stock`

### 3. Orders

* Tracks customer orders
* Fields: `order_id`, `customer_id`, `order_date`, `order_status`

### 4. Order Items

* Stores product-wise order details
* Fields: `order_item_id`, `order_id`, `product_id`, `quantity`

### 5. Payments

* Records payment transactions
* Fields: `payment_id`, `order_id`, `payment_mode`, `amount`, `payment_date`

---

## 🔗 Relationships

* One customer → Many orders
* One order → Many order items
* One product → Many order items
* One order → One payment

---

## 📊 Key SQL Queries

### 💰 Total Revenue

Calculates total earnings from all payments.

### 📦 Revenue by Product

Shows which products generate the most revenue.

### 🧑‍💼 Top Customers

Identifies highest spending customers.

### 🔥 Best Selling Products

Displays most frequently sold products.

### ❌ Cancelled Orders

Counts total cancelled orders.

---

## 🛠️ Tools Used

* MySQL
* SQL (DDL, DML, Joins, Aggregations)

---

## 🚀 What I Learned

* Database design and normalization
* Writing complex SQL queries
* Using JOINs and GROUP BY
* Real-world business data analysis

---

## 📁 How to Use

1. Open MySQL Workbench or any SQL tool
2. Run the SQL file
3. Uncomment sections step-by-step:

   * Database creation
   * Table creation
   * Data insertion
   * Queries

---

## 🌟 Future Improvements

* Add indexes for performance
* Create views for reporting
* Build dashboard using Power BI / Tableau

---

## 🙌 Acknowledgement

This project helped me understand real-world database systems and improved my SQL skills.

---

⭐ If you like this project, feel free to give it a star!
