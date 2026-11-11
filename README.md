# 🏢 Employee Management System

### A Java Swing & MySQL Desktop Application

A desktop-based Employee Management System developed using **Java, Java Swing, and MySQL** to simplify employee record management through an interactive graphical user interface.

---

## 📌 Project Overview

The Employee Management System is designed to help organizations manage employee information efficiently. It provides essential employee management operations, including adding, updating, viewing, and deleting employee records.

The application connects to a MySQL database to store and retrieve employee information.

## ✨ Key Features

- 🔐 **Login System** – Secure application entry through a login interface.
- ➕ **Add Employee** – Register new employees and save their details.
- ✏️ **Update Employee** – Modify existing employee information.
- 👁️ **View Employees** – Display employee records.
- 🗑️ **Remove Employee** – Delete employee records.
- 🗄️ **Database Connectivity** – Store and retrieve records using MySQL.
- 🖥️ **Graphical User Interface** – User-friendly Java Swing interface.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Java | Core application development |
| Java Swing | Graphical User Interface |
| MySQL | Database management |
| JDBC | Database connectivity |
| IntelliJ IDEA | Development environment |
| JCalendar | Date selection |
| rs2xml | Displaying database records |

## 📂 Project Structure

```text
Employee-Management-System/
│
├── lib/
│   ├── jcalendar-1.4.jar
│   ├── mysql-connector-j-26.10.0.jar
│   └── rs2xml.jar
│
├── src/
│   ├── employee/
│   │   └── management/
│   │       └── system/
│   │           ├── Splash.java
│   │           ├── Login.java
│   │           ├── Main_class.java
│   │           ├── AddEmployee.java
│   │           ├── UpdateEmployee.java
│   │           ├── RemoveEmployee.java
│   │           ├── View_Employee.java
│   │           └── conn.java
│   │
│   └── icons/
│
└── .gitignore
```

## ⚙️ Installation & Setup

### Prerequisites

- JDK 21 or compatible JDK
- IntelliJ IDEA
- MySQL Server
- MySQL Workbench

### Step 1: Clone the Repository

```bash
git clone https://github.com/sanatkumarswain/Employee-Management-System.git
```

### Step 2: Open the Project

Open the downloaded project folder in IntelliJ IDEA.

### Step 3: Configure Libraries

Add the JAR files available in the `lib` folder to the project's dependencies.

### Step 4: Configure MySQL

- Start your MySQL Server.
- Create the database named `employeemanagement`.
- Configure the required employee table according to the application's SQL queries.
- Verify the database connection settings in `conn.java`.

### Step 5: Configure Database Password

Set the Windows environment variable:

```text
EMP_DB_PASSWORD
```

Assign your local MySQL password to this variable. Do not hardcode or publish your password.

Restart IntelliJ IDEA after configuring the environment variable.

### Step 6: Run the Application

Run `Splash.java` or the configured application entry point in IntelliJ IDEA.

## 🗄️ Database

The application uses MySQL for persistent employee record storage.

JDBC is used to establish communication between the Java application and the MySQL database.

## 🎯 Project Objectives

- Understand Java object-oriented programming concepts.
- Implement database connectivity using JDBC.
- Develop desktop applications using Java Swing.
- Perform CRUD operations using MySQL.
- Build a practical application using Java and database technologies.

## 🚀 Future Improvements

- Role-based access control.
- Employee search and filtering.
- Improved input validation.
- Attendance and payroll management.
- Report generation and export functionality.

## 👨‍💻 Developer

**Sanat Kumar Swain**

B.Tech – Computer Science and Engineering

GitHub: [@sanatkumarswain](https://github.com/sanatkumarswain)

---

⭐ If you find this project useful, consider giving it a star!

**Thank you for visiting this repository.**
