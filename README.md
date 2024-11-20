Hotel Management System Database;
 This repository contains the SQL database schema and stored procedures for a Hotel Management System. 
 It is designed to handle core functionalities such as room availability checking, booking management, 
 and error handling to ensure a seamless experience for both hotel staff and customers.

Features;
   Room Availability: Stored procedures to check room availability based on user-provided dates.
   Booking Management: Ensure accurate booking records with date constraints and error handling.
   Data Integrity: Includes transactional mechanisms to maintain database consistency.

Technologies Used;
  Database: MariaDB 10.4.18
  Management Tool: phpMyAdmin 5.1.0
  Programming Language: SQL
  Backend Integration: Compatible with PHP (tested on PHP 8.0.3)

How to Use;
Import the Database:
   Open your database management tool (e.g., phpMyAdmin).
   Create a new database (e.g., hotel-management-system).
   Import the SQL file provided in this repository.

Run the Stored Procedures:
  Use the available_room procedure to check for room availability:
  sql code:
  CALL available_room('2023-11-20', '2023-11-25'); 

Customize;
    Modify or extend the schema as per your project requirements.

Prerequisites;
Software:
   MariaDB or MySQL
   phpMyAdmin (optional but recommended)
Development Environment:
   Localhost or any compatible database hosting platform.

Contribution;
Feel free to fork this repository and make contributions. Create a pull request to submit your updates or improvements.
