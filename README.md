# Hotel Management System

A comprehensive Hotel Management System built with PHP and MySQL, featuring room booking, user management, and admin controls.

## Features

- **User Authentication**: Secure registration and login for guests.
- **Room Booking**: Browse rooms, check availability, and book rooms.
- **Admin Dashboard**:
  - Manage rooms and room types.
  - View and manage bookings.
  - Manage users and staff.
  - View contact messages.
- **Contact System**: Guests can send messages to the admin.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.

## Prerequisites

- **PHP** (version 7.4 or higher)
- **MySQL** (or MariaDB)
- **Apache** (or Nginx)
- **phpMyAdmin** (for database management)

## Installation

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone https://github.com/CodeByAadil/hotel_management.git
    cd hotel_management
    ```

2.  **Set up the database**:
    - Open `hb_website.sql` in phpMyAdmin or your preferred SQL client.
    - Run the SQL script to create the database and tables.

3.  **Configure the database connection**:
    - Open `admin/inc/db.php`.
    - Update the database credentials if necessary:
      ```php
      $hname = 'localhost';
      $uname = 'root';
      $pass = '';
      $db = 'hb_website';
      ```

4.  **Configure the site URL**:
    - Open `admin/inc/essentials.php`.
    - Ensure `SITE_URL` is set correctly:
      ```php
      define('SITE_URL', 'http://localhost/hotel_management/');
      ```

5.  **Run the application**:
    - Open your browser and navigate to `http://localhost/hotel_management/`.

## Usage

### Admin Login
- **Username**: `admin@gmail.com`
- **Password**: `admin`

### User Access
- Users can register and log in to book rooms.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap 5
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache
