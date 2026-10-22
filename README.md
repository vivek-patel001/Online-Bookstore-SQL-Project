# 📚 Online Bookstore Data Analysis using SQL

## 📌 Project Overview
This project focuses on analyzing an online bookstore database using SQL. The database contains information about books, customers, and orders. SQL queries are used to explore book inventory, customer details, sales performance, and revenue.

## 🎯 Project Objectives
- Analyze book inventory and pricing.
- Identify books by genre and publication year.
- Explore customer locations and order history.
- Calculate total stock and revenue.
- Identify top-selling books and authors.
- Analyze customer spending patterns.
- Calculate remaining book stock after orders.

## 🛠️ Tools & Technologies
- **Database:** PostgreSQL
- **Language:** SQL
- **Dataset Format:** CSV
- **Version Control:** GitHub

## 🗂️ Project Structure
```text
Online-Bookstore-SQL-Project/
├── README.md
├── online_bookstore.sql
└── data/
    ├── Books.csv
    ├── Customers.csv
    └── Orders.csv
```

## 🗄️ Database Schema

### 1. Books
Contains information about books available in the bookstore.

- `Book_ID` – Unique book identifier
- `Title` – Book title
- `Author` – Author name
- `Genre` – Book genre
- `Published_Year` – Year of publication
- `Price` – Book price
- `Stock` – Available stock

### 2. Customers
Contains customer information.

- `Customer_ID` – Unique customer identifier
- `Name` – Customer name
- `Email` – Customer email
- `Phone` – Customer phone number
- `City` – Customer city
- `Country` – Customer country

### 3. Orders
Contains bookstore order details.

- `Order_ID` – Unique order identifier
- `Customer_ID` – Reference to the Customers table
- `Book_ID` – Reference to the Books table
- `Order_Date` – Date of the order
- `Quantity` – Quantity ordered
- `Total_Amount` – Total order amount

## 🔍 SQL Analysis

### Basic SQL Queries
1. Retrieve all books in the Fiction genre.
2. Find books published after 1950.
3. List customers from Canada.
4. Retrieve orders placed in November 2023.
5. Calculate the total stock of books.
6. Find the most expensive book.
7. Retrieve orders with a quantity greater than one.
8. Find orders with a total amount exceeding $20.
9. List all unique book genres.
10. Find the book with the lowest stock.
11. Calculate total revenue from all orders.

### Advanced SQL Queries
1. Calculate the total number of books sold by genre.
2. Find the average price of Fantasy books.
3. Identify customers who have placed at least two orders.
4. Find the most frequently ordered book.
5. Retrieve the top three most expensive Fantasy books.
6. Calculate the total quantity of books sold by each author.
7. Identify cities associated with orders exceeding $30.
8. Find the customer who spent the most on orders.
9. Calculate remaining stock after accounting for ordered quantities.

## 💡 SQL Concepts Used
- SELECT and WHERE
- ORDER BY and LIMIT
- DISTINCT
- Aggregate Functions: SUM(), AVG(), COUNT()
- GROUP BY and HAVING
- JOIN operations
- Primary Keys and Foreign Keys
- Filtering and sorting data

## 📈 Key Learning Outcomes
- Writing SQL queries to analyze relational datasets.
- Understanding relationships between books, customers, and orders.
- Analyzing sales, revenue, inventory, and customer behavior.
- Using aggregate functions and joins to extract insights.
- Working with PostgreSQL and CSV datasets.

## ▶️ How to Run the Project
1. Install PostgreSQL and open pgAdmin or another SQL client.
2. Create a database named `online_bookstore`.
3. Open `online_bookstore.sql` in the SQL editor.
4. Create the Books, Customers, and Orders tables.
5. Import the three CSV files into their corresponding tables.
6. Update the CSV file paths in the SQL script to match your computer.
7. Execute the SQL queries to explore the data and analyze bookstore performance.

**Note:** Import the CSV data before running the analysis queries. Ensure that the CSV columns match the table structure.

## 👨‍💻 Author
**Vivek Patel**

## 📄 License
This project is intended for educational and portfolio purposes.
