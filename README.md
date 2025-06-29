# Intro_to_DB
ALX Book Store Database
This project contains the SQL schema for a simple book store database, designed to manage authors, books, customers, orders, and order details.

Database Structure
Authors: Stores author information.
Books: Stores book details, linked to authors.
Customers: Stores customer information.
Orders: Stores customer orders.
Order_Details: Stores details of each order, including books and quantities.
Tables
Authors(author_id, author_name)
Books(book_id, title, author_id, price, publication_date)
Customers(customer_id, customer_name, email, address)
Orders(order_id, customer_id, order_date)
Order_Details(orderdetailid, order_id, book_id, quantity)
Usage
Run the SQL script alx_book_store.sql in your MySQL environment.
The script will create the database and all necessary tables with appropriate relationships.
Notes
Foreign key constraints ensure data integrity between tables.
Email addresses in the Customers table are unique.