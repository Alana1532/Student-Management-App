Student Management App

This is a simple console-based "Student Management System" built in "Java" using "JDBC" and "MySQL".  
It allows to add, view, update, and delete student records.

## Features
- Create a `studentdb` database automatically (if not exists).
- Create a `students` table automatically (if not exists).
- Perform CRUD operations:
  - Add a student
  - View all students
  - Update student details
  - Delete a student

## Requirements

1. Java Development Kit (JDK) - version 8 or higher
2. MySQL Server running on `localhost:3306`
3. MySQL JDBC Driver (Connector/J)

## Setup Instructions

1. Start MySQL Server
-Ensure MySQL server is running on:
  - **Host:** `localhost`
  - **Port:** `3306`

2. Update Database Credentials
In `StudentManagementApp.java`, update these values according to your local MySQL setup:
```java
private static final String USER = "root";              // Your MySQL username
private static final String PASSWORD = "your_password"; // Your MySQL password
```
3. Database Creation
-The program will automatically:
  - Create a database named studentdb (if not exists)
  - Create a table students (if not exists) with columns:
      - id
      - name
      - age
      - grade

4. Compile and Run



