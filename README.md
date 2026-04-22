📌 ZENTrek – Tour Guide Booking System

## 🌍 Overview

Zentrek is a web-based tour guide booking system designed to connect tourists with local tour guides in Sri Lanka. The platform allows users to explore guide profiles, check availability, make bookings, and manage reservations through a simple and user-friendly interface.

This project was developed as part of an academic coursework to demonstrate skills in web development using HTML, CSS, PHP, and MySQL.

## 🎯 Key Features

- Guide profile browsing (Guide Bios page)
- Check guide availability
- Tour booking system
- Payment system integration (basic structure)
# ZENTrek — Tour Guide Booking System

ZENTrek is a lightweight web application for connecting tourists with local tour guides in Sri Lanka. It demonstrates a complete HTML/CSS/JS frontend with a PHP backend and a MySQL database, built as an academic project to showcase full‑stack web development concepts.

---

## Table of contents

1. [Key features](#key-features)
2. [Tech stack](#tech-stack)
3. [Project structure](#project-structure)
4. [Prerequisites](#prerequisites)
5. [Install & run](#install--run)
6. [Database setup](#database-setup)
7. [Configuration example](#configuration-example)
8. [Contributing](#contributing)
9. [Future improvements](#future-improvements)
10. [License & contact](#license--contact)

---

## Key features

- Browse guide profiles (Guide Bios)
- Check guide availability and book tours
- Booking management (view / cancel)
- Basic payment workflow structure
- Reviews and feedback persisted in MySQL
- User authentication (login / signup)

## Tech stack

- Frontend: HTML5, CSS3, JavaScript
- Server: PHP (Apache/XAMPP)
- Database: MySQL

## Project structure

Top-level layout (representative):

```
zentrek/
├─ index.php
├─ Home.html
├─ login.php
├─ signup.php
├─ guidebios.html
├─ availability.php
├─ processbooking.php
├─ css/
├─ js/
└─ database/zentrek.sql
```

See the repository root for the full list of pages and assets.

## Prerequisites

- PHP (>=7.4) and Apache (included in XAMPP)
- MySQL or MariaDB
- Composer is not required (plain PHP project)

## Install & run (local)

1. Install and start XAMPP (Apache + MySQL).
2. Copy the project folder to your web root (example):

```powershell
Copy-Item -Path . -Destination 'C:\xampp\htdocs\zentrek' -Recurse
```

3. Import the SQL schema (see Database setup).
4. Open in browser: http://localhost/zentrek/

## Database setup

1. Open phpMyAdmin (http://localhost/phpmyadmin) or use the MySQL client.
2. Create a new database (e.g., `zentrek`).
3. Import `database/zentrek.sql` from the repository.

If using the MySQL CLI:

```bash
mysql -u root -p zentrek < database/zentrek.sql
```

## Configuration example

Create a small config file (example `config.php`) and update DB credentials:

```php
<?php
// config.php
return [
	'db_host' => '127.0.0.1',
	'db_name' => 'zentrek',
	'db_user' => 'root',
	'db_pass' => '',
];
```

Include or require this config where needed and use PDO or mysqli to connect safely.

## Contributing

- Fork the repository and open a pull request for non-trivial changes.
- For bug fixes or documentation updates, push to a feature branch and create a PR.

## Future improvements

- Integrate a production payment gateway (Stripe/PayPal)
- Add responsive/mobile-first UI improvements
- Admin dashboard for guide & booking management
- Google Maps for tour locations

## License & contact

This project is provided as-is for educational purposes. Add a license file if you intend to open-source it.

For questions or collaboration, contact the repository owner via GitHub: https://github.com/guruge0622

---

If you'd like, I can:

- add a `LICENSE` file (MIT/Apache)
- include sample screenshots in `docs/` and update README with thumbnails
- create `config.example.php` and a `.env` template

Tell me which of these you'd prefer next.


