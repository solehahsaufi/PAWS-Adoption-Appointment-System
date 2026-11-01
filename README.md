# PAWS Adoption Appointment System

## Project Overview

PAWS Adoption Appointment System is a web-based system developed to support the pet adoption process. The system allows adopters to browse available pets, book adoption appointments, and submit adoption applications. Staff can manage pet information, appointment requests, booking schedules, and adoption applications.

This project was developed as an academic group project for ICT600: Web Technology and Application.

## Features

### Adopter Module
- User registration and login
- Profile management
- Browse and search available pets
- View pet details
- Book adoption appointments
- View and manage appointment requests
- Submit adoption applications
- Track application status

### Staff Module
- Staff login
- Manage pet records
- Add and edit pet information
- Review and approve or reject appointment requests
- View booking schedules
- Review and manage adoption applications

## Technologies Used

- HTML
- CSS
- JavaScript
- PHP
- MySQL
- XAMPP

## Installation Guide

1. Download or clone this repository.
2. Extract the project folder if downloaded as a ZIP file.
3. Move the `PAWS` folder into the XAMPP `htdocs` directory.
4. Start Apache and MySQL using XAMPP Control Panel.
5. Open phpMyAdmin.
6. Create a database named `paws_db`.
7. Import the `paws_db.sql` database file.
8. Check the database connection settings in `connection.php`.
9. Open the system using the following URL:

   `http://localhost/PAWS/`

## Database Configuration

Make sure the database name and MySQL port in `connection.php` match your local XAMPP configuration.

## Project Information

**Project:** PAWS Adoption Appointment System  
**Course:** ICT600 – Web Technology and Application  
**Project Type:** Academic Group Project
