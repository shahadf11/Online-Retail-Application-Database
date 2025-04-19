# Online-Retail-Application-Database
 #Online Retail Application Database

This project involves designing and implementing a database for an Online Retail Application.
The system supports the management of categories, products, customers, orders, and shipments, simulating the core operations of an e-commerce platform.



 ##Database Structure

### 1. Categories
- Each category has:
  - A unique ID
  - A category name  
- A category can contain *many products*, but a product belongs to only one category.

### 2. Products
- Each product includes:
  - Unique product ID
  - Product name
  - Category ID (foreign key)
  - Price
  - Quantity in stock

### 3. Customers
- Each customer record contains:
  - Unique customer ID
  - Full name
  - Password
  - Address
  - Phone number

### 4. Orders
- Each order has:
  - A unique order ID
  - A product ID (foreign key)
  - Quantity ordered  
- One order can include multiple products, but each product can only be in one order.

### 5. Shipments
- Each shipment includes:
  - Unique shipment ID
  - Customer ID (foreign key)
  - Order ID (foreign key)
  - Shipment date
  - Total price  
- Each order has exactly one shipment, and each shipment is linked to one customer.  
- A customer may have multiple shipments.



## Project Components

- Data Definition Language (DDL): Defines database schema and structure.
- Data Manipulation Language (DML): Includes SQL statements for inserting, updating, and deleting records.
- Entity Relationship Model (ER Model): Visual representation of the database design.


## Purpose

This project demonstrates practical skills in database design and SQL implementation for a retail business context. 
It prepares students for real-world application development by using structured data and logical relationships.

