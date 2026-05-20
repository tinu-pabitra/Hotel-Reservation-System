Hotel Reservation System
Project Description

The Hotel Reservation System is a Java-based application developed to manage hotel room bookings. It uses MySQL database to store customer details, room information, and reservation records.

Features
Add customer details
Book hotel rooms
View available rooms
Check reservation details
Cancel bookings
Manage data using MySQL
Technologies Used
Java
MySQL
JDBC
Database Setup
CREATE DATABASE hotel_db;

USE hotel_db;

CREATE TABLE reservations (
    id INT AUTO_INCREMENT PRIMARY KEY,
    customer_name VARCHAR(100),
    room_number INT,
    check_in DATE,
    check_out DATE
);
How to Run
Clone the project
Open in Eclipse / IntelliJ IDEA
Configure MySQL connection in Java code
Run HotelReservationSystem.java
Author

Pabitra Paramanik
