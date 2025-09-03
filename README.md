# my-repo

Sample Sales Database Schema (Project XYZ)
This repository contains a SQL script to create and populate a relational database for a fictional company named "XYZ". The primary goal of this project is to demonstrate fundamental SQL and database design skills.

Project Overview
The database schema is designed to track core business entities such as employees, departments, customers, products, and sales transactions. It serves as a practical example of how to structure a database to ensure data integrity and facilitate efficient data retrieval for business intelligence and reporting.

Key Skills Demonstrated:
Database Design: Designing a relational schema with multiple interconnected tables.

Data Definition Language (DDL):

CREATE SCHEMA to organize the database objects.

CREATE TABLE with various data types (INT, VARCHAR, DATE, DECIMAL).

Defining PRIMARY KEY and FOREIGN KEY constraints to enforce data integrity.

Data Manipulation Language (DML):

INSERT INTO to populate the tables with realistic sample data.

Schema Structure
The database includes the following tables:

DEPARTMENTS: Stores department information.

EMPLOYEES: Contains employee details and links each employee to a department.

CUSTOMERS: Stores customer contact and location data.

PRODUCTS: A list of all products offered, including their prices and categories.

ORDERS: Tracks customer orders, the date they were placed, and the employee who handled them.

ORDER_DETAILS: A junction table that provides details for each order, linking it to specific products and quantities.

PAYMENTS: Records payments made by customers.

How to Use
Clone this repository to your local machine.

Open the XYZ.sql file in a SQL client of your choice (e.g., MySQL Workbench, DBeaver, SQL Server Management Studio).

Execute the script to create the schema, tables, and insert the sample data.

You can now perform your own queries on the database to explore the data.

