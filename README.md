# Sngine

Sngine is a full-featured PHP social networking platform for building your own social network.

## Overview
- **Core** located in the `Script/` directory containing the PHP application.
- **Apps** holds mobile stubs for Android/iOS.
- **Docs** provides end-user and developer documentation.
- **Extras** includes optional modules and resources.

## Installation
1. Install PHP, MySQL, and Composer.
2. Copy `Script/includes/config-example.php` to `Script/includes/config.php` and update database credentials and site URL.
3. From the `Script/` directory run `composer install` to pull PHP dependencies.
4. Start a local server with `php -S localhost:8000 -t Script` and visit `http://localhost:8000`.

## Directory Structure
```
Apps/     # Mobile applications
Docs/     # Project documentation
Script/   # Core PHP application
Updates/  # SQL update scripts
```

## How to Contribute
1. Fork the repository and create a new branch for your feature or fix.
2. Make your changes following PHP best practices.
3. Run available tests or linters before submitting.
4. Open a pull request describing your changes.

See [Docs/development.md](Docs/development.md) for environment setup and additional guidelines.

## License
Sngine is distributed under a commercial license. See the product documentation for more details.
