# Student-Management-System
Java + MySQL CRUD Application
# 🎓 Student Management System (Java + MySQL)

## 📌 Description
A console-based Java application that performs CRUD operations using JDBC and MySQL.

## 🚀 Features
- Add Student
- View Students
- Update Student
- Delete Student

## 🛠 Tech Stack
- Java
- JDBC
- MySQL

## ⚙️ Setup Instructions
1. Create database:
   CREATE DATABASE student_db;

2. Create table:
   CREATE TABLE students (
       id INT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(100),
       age INT,
       course VARCHAR(100)
   );

3. Set environment variable:
   setx DB_PASSWORD "your_password"

4. Run Main.java

## 💡 Output
- Menu-driven console system
- Real-time database operations
