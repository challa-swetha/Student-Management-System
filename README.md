# 🚀 Student Management System (Java + MySQL + JDBC)

## 📌 Overview

A **backend-driven Java application** that performs full **CRUD (Create, Read, Update, Delete)** operations using **JDBC and MySQL**.
This project demonstrates strong fundamentals in **database integration, object-oriented programming, and backend system design**.

---

## ✨ Features

* ➕ Add new student records
* 📋 View all students from database
* ✏️ Update student details dynamically
* ❌ Delete student records
* 🔗 Real-time MySQL database connectivity
* ⚙️ Menu-driven console interface

---

## 🛠️ Tech Stack

* **Language:** Java
* **Database:** MySQL
* **Connectivity:** JDBC
* **Tools:** IntelliJ IDEA, Git, GitHub

---

## 🧠 Concepts Applied

* Object-Oriented Programming (OOP)
* JDBC (Java Database Connectivity)
* SQL (CRUD operations)
* DAO Design Pattern
* Exception Handling
* Environment Variable Security

---

## 📂 Project Structure

```
Student-Management-System/
│
├── src/
│   ├── Main.java
│   ├── Student.java
│   ├── StudentDAO.java
│   ├── DBConnection.java
│
├── README.md
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 1️⃣ Create Database

```sql
CREATE DATABASE student_db;
USE student_db;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    course VARCHAR(100)
);
```

---

### 2️⃣ Configure Environment Variable (Security 🔐)

```bash
setx DB_PASSWORD "your_password"
```

Restart your IDE after setting this.

---

### 3️⃣ Run Application

* Open project in IntelliJ
* Run `Main.java`

---

## 📸 Output Preview

```
===== Student Management System =====
1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Exit
```

---

## 💡 Key Highlights

* Built a **real backend system** with database integration
* Implemented **modular architecture using DAO pattern**
* Ensured **secure credential handling using environment variables**
* Designed **scalable and maintainable code structure**

---

## 🚀 Future Enhancements

* Add GUI (Java Swing / JavaFX)
* Convert to Spring Boot REST API
* Add authentication system
* Deploy as full-stack application

---

## 🤝 Contribution

Feel free to fork this repository and improve it!

---

## 📬 Contact

**Swetha Challa**
📧 [swethareddychalla09@gmail.com](mailto:swethareddychalla09@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/challa-swetha/) | GitHub

---

⭐ If you found this project useful, consider giving it a star!
