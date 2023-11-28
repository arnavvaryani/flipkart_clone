# Flipkart Clone

## Introduction
This project is a web-based clone of the popular e-commerce platform Flipkart. It is designed to demonstrate a basic e-commerce website with functionalities like product browsing, cart management, and user authentication.

## Features
- User Registration and Login
- Product Browsing
- Cart Functionality
- Checkout Process

## Prerequisites
- Web server (Apache/Nginx)
- PHP
- MySQL

## Installation

### Setting Up the Environment
1. Install XAMPP/WAMP or any similar stack that includes Apache, PHP, and MySQL.
2. Start the Apache and MySQL services.

### Deploying the Application
1. Clone the repository or download the project files.
2. Move the `Flipkart_Clone-main` folder to your web server's root directory (e.g., `htdocs` in XAMPP).

### Configuring the Database
1. Access phpMyAdmin by visiting `http://localhost/phpmyadmin`.
2. Create a new database named `flipkart_clone`.
3. Import the provided SQL file located in the `database` folder.

### Setting Up the Application
1. Open `db.php` file.
2. Update the database connection details as follows:
   - Server: `localhost`
   - Username: `root`
   - Password: `<your_mysql_password>` (Leave blank if no password is set)
   - Database Name: `flipkart_clone`

## Usage
Open a web browser and navigate to `http://localhost/Flipkart_Clone-main` to start using the application.
