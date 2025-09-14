# Development Guide

## Prerequisites
- PHP 8.1+
- MySQL 5.7+
- Composer
- Node.js and npm (optional for asset workflows)

## Setup
1. Clone the repository and `cd` into the project root.
2. Copy `Script/includes/config-example.php` to `Script/includes/config.php` and adjust settings.
3. Install PHP dependencies:
   ```bash
   cd Script
   composer install
   ```
4. (Optional) install JavaScript dependencies for asset builds:
   ```bash
   npm install
   ```
5. Start a local PHP server from the project root:
   ```bash
   php -S localhost:8000 -t Script
   ```

## Running Tests
This project currently has no automated tests. Contributors are encouraged to add tests using PHPUnit and run them before submitting changes.
