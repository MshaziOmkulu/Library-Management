# Library Management System Database

## Description
This project is a MySQL-based relational database schema designed for a Library Management System. It tracks authors, books, borrowers, and loans with appropriate constraints and relationships.

## Tables and Relationships
- **Authors**: Stores author details.
- **Books**: Stores book details with a foreign key linking to Authors.
- **Borrowers**: Stores borrower info.
- **Loans**: Junction table for many-to-many relationship between Books and Borrowers, tracking loan and return dates.

## Setup Instructions
1. Open your MySQL environment (e.g., MySQL Workbench).
2. Create a new database (e.g., `CREATE DATABASE libraryDB;`).
3. Select the database: `USE libraryDB;`
4. Import the `library_management.sql` file or paste its content and run.
5. The tables with relationships and constraints will be created.

## ERD Diagram
![ERD Screenshot] INSIDE THE FILE 
