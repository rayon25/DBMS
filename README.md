Student Management System

Overview
This project is a Student Management System designed to store and manage information about students, their payments, and fee status.
The system consists of three main tables: Students, Payments, and FeeStatus.

Table Structure

Students Table

Columns:
USN: Unique Student Number (Primary Key)
FirstName: First name of the student
MiddleName: Middle name of the student (nullable)
LastName: Last name of the student
Email: Email address of the student
PhoneNumber: Contact phone number of the student
SEM: Semester of the student
Department: Department of the student

Payments Table

Columns:
PaymentID: Unique identifier for each payment (Primary Key)
USN: Unique Student Number (Foreign Key referencing Students table)
Amount: Amount of the payment
PaymentDate: Date of the payment

FeeStatus Table

Columns:
USN: Unique Student Number (Primary Key, Foreign Key referencing Students table)
PaidStatus: Indicates whether the fee is paid (TRUE/FALSE)

Usage

-Setup Database: Execute the provided SQL script to create the necessary tables.
-Insert Data: Use SQL INSERT statements to populate the tables with student information, payment records, and fee status.
-Queries and Operations: Perform various operations such as retrieving student details, recording payments, and updating fee status using SQL queries.

Sample Data
Sample data has been provided in the SQL script to demonstrate the structure and functionality of the system. You can customize and expand the data according to your requirements.

Contributors
--> ROHIT JADHAV
--> PRATIK CHITTI

For any feedback, suggestions, or issues, please commit.
