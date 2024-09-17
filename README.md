

# Tourism Management System (TMS)

## Project Overview

The **Tourism Management System (TMS)** is a web-based application developed using **PHP** and **MySQL** that facilitates the management of tour packages and bookings. This system offers modules for **Admin**, **Registered Users**, and **Guest Users**, allowing for seamless handling of tour bookings, inquiries, and user management. The system is designed to simplify the booking process for users while providing robust tools for administrators to manage packages, users, and other operations.

## Project Requirements

- **Project Name**: Tourism Management System (TMS)
- **Languages Used**:  
  - PHP (Version 5.6, 7.x)
- **Database**:  
  - MySQL 5.x
- **User Interface Design**:  
  - HTML, AJAX, JQUERY, JavaScript
- **Web Browser Compatibility**:  
  - Mozilla Firefox, Google Chrome, Internet Explorer (IE8+), Opera
- **Software Required**:  
  - XAMPP / WAMP / MAMP / LAMP

## Modules of Tourism Management System in PHP

### 1. Admin Module

The **Admin Module** allows system administrators to manage various aspects of the platform:

- **Create and Manage Packages**:  
  - Admins can create new tour packages, update existing ones, and delete outdated packages.

- **Manage Users**:  
  - Admins can view and manage registered users on the platform.

- **Manage Inquiries**:  
  - Admins can handle inquiries submitted by both users and guest users.

- **Manage Issues**:  
  - Admins can address issues or complaints generated by users.

- **Manage Bookings**:  
  - Admins can manage bookings made by users, including approvals, cancellations, and modifications.

- **Manage Pages**:  
  - Admins can update static content pages such as About Us, Terms & Conditions, and more.

- **Change Password**:  
  - Admins can update their login credentials to enhance security.

- **Admin Dashboard**:  
  - The admin dashboard provides an overview of the platform’s activity, including user statistics, booking counts, and package status.

### 2. Users Module

The **Users Module** provides features for registered users to interact with the platform:

- **User Registration**:  
  - Users can register with valid credentials to access the system.

- **User Login**:  
  - Registered users can log in with their email and password to access their account.

- **Forgot Password**:  
  - Users can recover their password using their registered email address if they forget it.

- **Tour Booking**:  
  - Users can browse available tour packages and book their preferred options.

- **Manage Booking**:  
  - Users can view, modify, or cancel their bookings.

- **Generate Ticket**:  
  - Users can submit complaints or issues regarding their bookings through a ticketing system.

- **Change Password**:  
  - Users can change their login password for enhanced account security.

### 3. Guest Users Module

The **Guest Users Module** allows non-registered users to explore the platform:

- **Visit the Website**:  
  - Guest users can browse the website and view available tour packages.

- **Submit Inquiry**:  
  - Guest users can submit inquiries about packages or other services offered by the platform without needing to register.

## Features Summary

- **User-friendly interface** for seamless navigation and booking experience.
- **Admin control panel** for managing packages, users, bookings, and other system functionalities.
- **Booking and Inquiry Management**: Users can manage bookings, and both users and guests can submit inquiries.
- **Secure login and password recovery** for registered users and admin.
- **Cross-browser compatibility** for smooth access across all major web browsers.

## Installation Instructions

1. **Download and Install XAMPP, WAMP, MAMP, or LAMP**:
   - **XAMPP**: [Download Here](https://www.apachefriends.org/index.html)
   - **WAMP**: [Download Here](http://www.wampserver.com/en/)
   - **MAMP**: [Download Here](https://www.mamp.info/en/)
   - **LAMP**: Install as per your Linux distribution guidelines.

2. **Clone or Download the Project Repository**:
   ```bash
   git clone https://github.com/yourusername/tourism-management-system.git
   ```

3. **Move the Project to Your Server Root Directory**:
   - XAMPP: `C:/xampp/htdocs/`
   - WAMP: `C:/wamp/www/`
   - MAMP: `/Applications/MAMP/htdocs/`
   - LAMP: `/var/www/html/`

4. **Create the Database**:
   - Open **phpMyAdmin** in your browser (usually `http://localhost/phpmyadmin`).
   - Create a new database, e.g., `tms_db`.
   - Import the provided SQL file (`tms.sql`) into the new database.

5. **Configure the Project**:
   - Open the project’s configuration file (`config.php`) and update the database credentials:
     ```php
     $host = 'localhost';
     $user = 'root';  // or your MySQL username
     $password = '';  // or your MySQL password
     $dbname = 'tms_db';  // your database name
     ```

6. **Run the Project**:
   - Open your browser and navigate to `http://localhost/your_project_folder/`.

## License
This project is open-source and available under the [MIT License](LICENSE).
