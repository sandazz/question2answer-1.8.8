
# Question2Answer Setup Instructions

## Prerequisites
Ensure you have XAMPP running with MySQL enabled.

## Installation Steps

1. **Create Configuration File**
    ```bash
    cp qa-config-example.php qa-config.php
    ```

2. **Configure Database Settings**
    - Open `qa-config.php` in your editor
    - Update the following with your database credentials:
      - Database host
      - Database name
      - Database username
      - Database password

3. **Create Local Database**
    - Open phpMyAdmin from XAMPP control panel
    - Create a new database matching the name in `qa-config.php`

4. **Run the Application**
    - Open your browser
    - Navigate to `http://localhost/question2answer-1.8.8/index.php`
    - Follow the on-screen installation wizard
