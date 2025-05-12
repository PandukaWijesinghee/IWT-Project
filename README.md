# IWT-Project Voting System

This is a web-based voting system developed for the IWT Project. The application allows users to register, log in, and participate in voting. Admins, judges, and IT consultants have special roles for managing and evaluating the voting process.

## Features

- User registration and authentication
- Role-based access (User, Admin, Judge, IT Consultant)
- Voting functionality
- Admin panel for managing users and votes
- Judge and IT consultant evaluation modules

## Technologies Used

- PHP (Backend)
- MySQL (Database)
- HTML, CSS, JavaScript (Frontend)
- XAMPP/WAMP for local development

## Installation & Setup

### 1. Prerequisites

- [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/) installed
- Web browser (Chrome, Firefox, etc.)

### 2. Clone or Download the Project

Copy the `IWT-Project` folder into your web server's root directory:

- **XAMPP:** `C:\xampp\htdocs\IWT-Project`
- **WAMP:** `C:\wamp64\www\IWT-Project`

### 3. Database Setup

1. Start Apache and MySQL from your XAMPP/WAMP control panel.
2. Open [phpMyAdmin](http://localhost/phpmyadmin).
3. Create a new database named `votingsystem`.
4. Import the provided SQL file (if available) to set up tables and initial data.

### 4. Configure Database Connection

Edit `project/backend/sqlConnect.php` and ensure the following settings match your environment:

```php
$servername = "localhost:3306";
$username = "root";
$password = "";
$database = "votingsystem";
```

### 5. Run the Application

Open your browser and go to:

```
http://localhost/IWT-Project/project/index.php
```

## Usage

- Register as a new user or log in with existing credentials.
- Admins can manage users and voting events.
- Judges and IT consultants can evaluate as per their roles.


## Troubleshooting

- Ensure Apache and MySQL are running.
- Check database credentials in `sqlConnect.php`.
- Make sure the database `votingsystem` exists and tables are imported.

## License

This project is for educational purposes.

---

*Developed for the IWT Project.*
