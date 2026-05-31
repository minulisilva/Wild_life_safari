# 🦁 Wildlife Safari Booking Website

## 📌 Overview

The **Wildlife Safari Booking Website** is a PHP-based web application designed to manage safari tours, customer reservations, feedback, and staff operations. It provides a complete online platform for users to explore safari packages, make bookings, and interact with the service, while administrators can manage tours, customers, and system data.

---

## ✨ Features

### 🏕️ Tour Management

* Display safari tour listings
* View detailed tour information
* Manage tour availability

### 📅 Booking & Reservations

* Online safari booking system
* Reservation processing and confirmation
* Payment UI integration

### 👤 User Management

* User authentication (login/logout)
* Admin and staff access control
* Session-based security

### 💬 Customer Interaction

* Feedback submission system
* Contact forms for inquiries

### 📄 Informational Pages

* About Us page
* FAQ section
* Privacy Policy & Terms pages

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL / MariaDB
* **Server:** Apache (XAMPP / WAMP)

---

## 📁 Project Structure

```
*.php                  → Main application pages (frontend + backend logic)
config.php            → Database configuration file
database_script/      → SQL backup and database schema (tranqilsafari)
images/               → Website images and media assets
js/                   → JavaScript functionality
stylesheets/          → CSS styling files
```

---

## ⚙️ Requirements

* PHP 7.x or higher
* MySQL / MariaDB
* Apache Server (XAMPP/WAMP recommended)
* Web browser

---

## 🚀 Setup Instructions

### 1. Install Server Environment

Install **XAMPP**, **WAMP**, or any PHP + MySQL local server.

### 2. Project Setup

Copy the project folder into your web root directory:

```
C:\xampp\htdocs\wildlifesafari
```

### 3. Database Setup

1. Open **phpMyAdmin**
2. Create a database:

   ```sql
   CREATE DATABASE tranqilsafari;
   ```
3. Import SQL file from:

   ```
   database_script/
   ```

### 4. Configure Database Connection

Update `config.php` if needed:

```php
$servername = "localhost";
$username = "root";
$password = "";
$db_name = "tranqilsafari";
```

### 5. Run the Project

Open browser and navigate to:

```
http://localhost/wildlifesafari/index.php
```

---

## ⚠️ Notes

* Ensure PHP sessions are enabled for login functionality
* Keep `images/`, `js/`, and `stylesheets/` directories properly linked
* Verify database connection before running the project
* Default configuration uses local MySQL credentials
