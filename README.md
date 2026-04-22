📌 ZENTrek – Tour Guide Booking System

## 🌍 Overview

Zentrek is a web-based tour guide booking system designed to connect tourists with local tour guides in Sri Lanka. The platform allows users to explore guide profiles, check availability, make bookings, and manage reservations through a simple and user-friendly interface.

This project was developed as part of an academic coursework to demonstrate skills in web development using HTML, CSS, PHP, and MySQL.

## 🎯 Key Features

- Guide profile browsing (Guide Bios page)
- Check guide availability
- Tour booking system
- Payment system integration (basic structure)
- Booking management (view & cancel bookings)
- Review and feedback system (stored in database)
- User login system
- Admin-friendly data structure using MySQL

## 🛠️ Technologies Used

- Frontend: HTML5, CSS3, JavaScript
- Backend: PHP
- Database: MySQL
- Server: XAMPP (Apache + MySQL)

## 📁 Project Structure

zentrek/
│
├── index.php
├── login.php
├── register.php
├── guide-bios.php
├── availability.php
├── booking.php
├── manage_bookings.php
├── payment.php
│
├── css/
│   ├── style.css
│   ├── availability.css
│
├── js/
│   ├── script.js
│
├── images/
│
└── database/
	└── zentrek.sql

## 🗄️ Database

The system uses a MySQL database to store:

- User information
- Guide profiles
- Bookings
- Payments
- Reviews and feedback

Import the SQL file:

`database/zentrek.sql`

into phpMyAdmin.

## 🚀 How to Run the Project Locally

1. Install XAMPP
2. Start Apache and MySQL

Move project folder to:

`C:\xampp\htdocs\zentrek`
Import database using phpMyAdmin

Open browser and run:

http://localhost/zentrek/



## 📌 Project Purpose

This project was built to:

- Practice full-stack web development
- Understand database-driven applications
- Simulate a real-world booking system
- Improve UI/UX design skills

## 📈 Future Improvements

- Online payment gateway integration (PayPal/Stripe)
- Real-time chat with guides
- Advanced admin dashboard
- Mobile responsive optimization
- Google Maps integration for tour locations


