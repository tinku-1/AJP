# Hibernate WebApp - Employee Management System

## 📌 Overview
This is a **Java Full-Stack Web Application** built using **JSP, Servlets, Hibernate ORM, and Maven**.  
It provides an **Employee Management System** that allows users to perform **CRUD (Create, Read, Update, Delete)** operations on employee records.

This project demonstrates:
- MVC architecture with Servlets and JSP  
- Database persistence using Hibernate  
- Web deployment on Apache Tomcat  
- Maven-based build and dependency management  

---

## 🚀 Features
- ➕ Add new employees  
- 📋 View list of employees  
- ✏️ Update employee details  
- ❌ Delete employee records  
- 🔗 Hibernate ORM for seamless database integration  
- 🎨 JSP-based frontend with dynamic rendering  

---

## 🏗️ Project Structure
```

Hibernate\_WebApp-master/
│── pom.xml                 # Maven configuration
│── src/
│   ├── main/
│   │   ├── java/com/
│   │   │   ├── helper/FactoryProvider.java
│   │   │   ├── servlets/ (CRUD servlets)
│   │   │   └── vignan/Employee.java (Entity class)
│   │   ├── resources/hibernate.cfg.xml
│   │   └── webapp/
│   │       ├── index.jsp
│   │       ├── createEmployee.jsp
│   │       ├── updateEmployee.jsp
│   │       ├── deleteEmployee.jsp
│   │       ├── listEmployees.jsp
│   │       └── WEB-INF/web.xml
└── target/ (generated build files)

````

---

## 🛠️ Technologies Used
- **Java 8+**  
- **Hibernate ORM**  
- **JSP & Servlets**  
- **Maven**  
- **MySQL (or compatible RDBMS)**  
- **Apache Tomcat**  

---

## ⚙️ Setup & Installation

### 1️⃣ Prerequisites
- JDK 8 or higher  
- Apache Maven  
- Apache Tomcat 9+  
- MySQL Server  

### 2️⃣ Database Setup
1. Create a new database in MySQL:
   ```sql
   CREATE DATABASE employee_db;
````

2. Update database credentials in `src/main/resources/hibernate.cfg.xml`:

   ```xml
   <property name="hibernate.connection.url">jdbc:mysql://localhost:3306/employee_db</property>
   <property name="hibernate.connection.username">your_username</property>
   <property name="hibernate.connection.password">your_password</property>
   ```

### 3️⃣ Build & Deploy

1. Build the project with Maven:

   ```bash
   mvn clean install
   ```
2. Deploy the generated WAR file (`target/*.war`) into Tomcat’s `webapps/` folder.
3. Start Tomcat and open the application in your browser:

   ```
   http://localhost:8080/Hibernate_WebApp-master/
   ```

---

## 📸 Application Pages

* **Home Page (index.jsp)** – Navigation hub
* **Create Employee** – Form to add new employees
* **List Employees** – Displays all employees
* **Update Employee** – Edit existing employee details
* **Delete Employee** – Remove employee record

---

## 🤝 Contributing

Contributions are welcome!
Fork this repository, create a branch, commit your changes, and open a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.
```
