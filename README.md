# Advanced Web-Based Airline Reservation System

## Project Overview
The Advanced Web-Based Airline Reservation System is a comprehensive software solution designed for booking and managing airline tickets online. Developed in Java, this system offers a user-friendly interface for passengers and robust administrative controls for managing flights and reservations.

## Features

### Passenger Features
- **Flight Search:** Allows users to search for flights based on origin, destination, and travel dates.
- **Seat Selection:** Enables passengers to choose their preferred seats during the booking process.
- **Booking Management:** Allows users to view, modify, and cancel their bookings.
- **Passenger Pass Generation:** Generates printable boarding passes for passengers.

### Administrative Features
- **Flight Management:** Administrators can add, update, and remove flights.
- **Reporting:** Generates detailed reports on flight bookings, cancellations, and other key metrics.
- **User Authentication:** Secure login system for both passengers and administrators.
- **Role Management:** Controls access to different parts of the system based on user roles.

## System Requirements
- **Java Development Kit (JDK):** Version 6u1 or higher.
- **NetBeans IDE:** Version 6.9.1 or higher.
- **MySQL Database:** 
  - mysql-5.1.39
  - mysql-connector-odbc-5.1.6
  - mysql-gui-tools-5.0-r17
- **MySQL Connector:** mysql-connector-java-5.1.6-bin.jar
- **Apache Tomcat:** Version 6.0.26 (integrated with NetBeans).
- **Web Browser:** Firefox 3.6.3 or higher.

## Installation Instructions
1. **Install JDK:**
   - Download and install the Java Development Kit (JDK).
2. **Install NetBeans IDE:**
   - Download and install NetBeans IDE (Version 6.9.1 or higher).
3. **Install MySQL:**
   - Install MySQL and its components (mysql-5.1.39, mysql-connector-odbc-5.1.6, mysql-gui-tools-5.0-r17).
   - Default username: `root`, password: `admin`.
   - Modify the `database.java` file to match your MySQL username and password if different from the default.
4. **Install Firefox:**
   - Download and install Firefox (Version 3.6.3 or higher).
5. **Import Project in NetBeans:**
   - Open NetBeans IDE.
   - Import the `AirlineReservationSystem` project as a web project.
   - Add `mysql-connector-java-5.1.6-bin.jar` to Libraries if not already added.

## Usage
- **Launching the Application:**
  - Run the application through NetBeans IDE.
  - Access the application via a web browser using the specified URL.
- **Logging In:**
  - Use the provided dummy credentials for initial testing.
  - Admin credentials: `username: admin, password: admin`.
- **Flight Booking:**
  - Search for flights, select seats, and complete the booking process.
- **Administrative Tasks:**
  - Log in as an admin to manage flights and view reports.

## Dummy Users
Several dummy users are available in the system for testing purposes:

| User Name  | Password  | User Type         |
|------------|-----------|-------------------|
| admin      | admin     | Administrator     |
| user1      | pass1     | Passenger         |
| user2      | pass2     | Passenger         |

## Known Issues
- Some database-related issues may arise despite proper installation and configuration.
- Refer to the `DBQuery.sql` file for database queries, triggers, procedures, and events.

