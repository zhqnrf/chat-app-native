# ChatApp - PHP Native

This is a simple chat application built using PHP (native) and MySQL. This project allows users to communicate with each other in real-time. Follow the instructions below to set up the project on your local machine.

## Features

- Real-time messaging
- User registration and login
- Secure password hashing

## Requirements

- PHP 7.4 or higher
- MySQL
- Apache or Nginx
- Composer (optional, if you use third-party libraries)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/chatapp.git
cd chatapp
```

### 2. Set Up the Database

1. Create a new MySQL database named `chatapp`:

   ```sql
   CREATE DATABASE chatapp;
   ```

2. Import the database schema:

   - Use the provided SQL file in the repository (e.g., `chatapp.sql`) to create the necessary tables.
   - You can import it using a tool like phpMyAdmin or the MySQL CLI:

   ```bash
   mysql -u username -p chatapp < chatapp.sql
   ```

### 3. Configure the Database Connection

- Open the `config.php` file and update the database credentials to match your local setup:

  ```php
  <?php
  define('DB_HOST', 'localhost');
  define('DB_USER', 'your-username');
  define('DB_PASS', 'your-password');
  define('DB_NAME', 'chatapp');
  ?>
  ```

### 4. Run the Application

- Start your local server (Apache or Nginx).
- Open the application in your browser:

  ```
  http://localhost/chatapp
  ```

## License

This project is licensed under the MIT License.

---
