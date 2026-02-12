# E-Commerce Database Schema
## Objective
To design and implement a relational database schema for an E-Commerce system as part of the SQL Developer Internship Task-1.

## Tools Used
- MySQL
- MySQL Workbench

## Database Name
EcommerceDB

## Tables Created
1. Customers  
2. Products  
3. Orders  
4. OrderDetails  
5. Payments  

## Table Description
- **Customers**: Stores customer information.
- **Products**: Stores product details and stock.
- **Orders**: Stores order details placed by customers.
- **OrderDetails**: Junction table to manage many-to-many relationship between Orders and Products.
- **Payments**: Stores payment information for orders.

## Key Concepts Applied
- DDL (CREATE DATABASE, CREATE TABLE)
- Primary Key & Foreign Key
- Normalization
- One-to-Many and Many-to-Many relationships
- ER Diagram

## Outcome
A well-structured, normalized E-Commerce database schema with proper relationships between entities.

## Files Included
- `schema.sql` – SQL script to create database and tables
- `ecommerce_er_diagram.png` – ER diagram of the database
- `README.md` – Project documentation

