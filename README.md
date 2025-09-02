Hibernate WebApp - Employee Management System
📌 Overview

This project is a Java Full-Stack Web Application built with JSP, Servlets, and Hibernate ORM, packaged with Maven.
It implements a simple Employee Management System where users can perform CRUD (Create, Read, Update, Delete) operations on employee records.

The application demonstrates:

MVC architecture using Servlets + JSP

Database persistence with Hibernate

Web deployment using Apache Tomcat

Maven project structure for easy dependency management

🚀 Features

Add a new employee

View list of employees

Update employee details

Delete employee records

Hibernate-based ORM for DB operations

JSP-based frontend with dynamic rendering

🏗️ Project Structure
Hibernate_WebApp-master/
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

🛠️ Technologies Used

Java 8+

Hibernate ORM

JSP & Servlets

Maven

MySQL (or any RDBMS)

Apache Tomcat

⚙️ Setup & Installation
1️⃣ Prerequisites

Install JDK 8+

Install Apache Maven

Install Apache Tomcat 9+

Install MySQL Server

2️⃣ Database Setup

Create a database in MySQL:

CREATE DATABASE employee_db;


Update database credentials in hibernate.cfg.xml:

<property name="hibernate.connection.url">jdbc:mysql://localhost:3306/employee_db</property>
<property name="hibernate.connection.username">your_username</property>
<property name="hibernate.connection.password">your_password</property>

3️⃣ Build & Deploy

Navigate to the project folder and build:

mvn clean install


Deploy the generated WAR file to Tomcat’s webapps/ folder.

Start Tomcat and access the app at:

http://localhost:8080/Hibernate_WebApp-master/

📸 Screens (JSP Pages)

Home Page (index.jsp) – Navigation

Create Employee – Add new employee

List Employees – View all employees

Update Employee – Edit employee details

Delete Employee – Remove employee record

🤝 Contributing

Contributions are welcome!
Feel free to fork this repo, create a new branch, and submit a pull request.

📜 License

This project is licensed under the MIT License.
