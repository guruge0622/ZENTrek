📌 ZENTrek – Tour Guide Booking System

## 🌍 Overview

Zentrek is a web-based tour guide booking system designed to connect tourists with local tour guides in Sri Lanka. The platform allows users to explore guide profiles, check availability, make bookings, and manage reservations through a simple and user-friendly interface.

This project was developed as part of an academic coursework to demonstrate skills in web development using HTML, CSS, PHP, and MySQL.

## 🎯 Key Features

- Guide profile browsing (Guide Bios page)
- Check guide availability
- Tour booking system
- Payment system integration (basic structure)
# ZENTrek

ZENTrek is a web-based tour guide booking system that connects tourists with local tour guides in Sri Lanka. This repository contains the site source (HTML/CSS/JS) and a PHP backend intended for deployment on a local XAMPP/Apache environment. It was created as an academic project to demonstrate full‑stack web development with PHP and MySQL.
## Overview

A compact summary of the repository, how to run it locally, and how to configure the database and application settings.

## Contents

- Source files: HTML, PHP, CSS, JavaScript
- Database schema: `database/zentrek.sql`
- Example configuration: `config.example.php`

## Features

- Guide profile browsing
- Availability checks and bookings
- Booking management (view/cancel)
- Basic payment flow structure
- Reviews and feedback stored in the database
- User authentication (login/signup)

## Requirements

- PHP 7.4+ with PDO extension
- MySQL or MariaDB
- XAMPP or equivalent Apache+PHP development stack

## Local installation

1. Install XAMPP and start Apache and MySQL.
2. Place the project folder in your web root (example path):

```powershell
Copy-Item -Path . -Destination 'C:\xampp\htdocs\zentrek' -Recurse
```

3. Import the SQL schema:

```bash
mysql -u root -p zentrek < database/zentrek.sql
```

4. Configure database connection using `config.example.php` (copy to `config.php` and set credentials).
5. Open http://localhost/zentrek/ in your browser.

## Configuration

Use `config.example.php` as the template for `config.php`. The example shows PDO usage and recommended settings.

## Contributing

Contributions are welcome. Please open issues for bugs or feature requests. Create pull requests from feature branches for code changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

Repository owner: https://github.com/guruge0622


