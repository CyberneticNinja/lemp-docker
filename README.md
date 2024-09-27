# Laravel & TALL Stack Docker Environment

This repository contains a pre-configured Docker-based environment designed for quickly setting up and developing Laravel, Laravel Livewire, and TALL (Tailwind, Alpine.js, Laravel, Livewire) stack applications.

## Features

- **PHP 8.3** with FPM
- **Nginx** for serving the application
- **MariaDB** for database support
- **SQLite** integrated as an alternative database
- **Node.js** for managing frontend assets
- **Composer** for PHP dependency management

## Quick Start

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo/app  # Navigate to the 'app' folder where the Laravel project is located
2. docker-compose build command
3. docker-compose run -d command
4. docker-compose exec php bash command
5. inside the bash terminal run the composer install command
6. (optional) php artisan key:generate if needed
7. npm install command, followed by the command npm run build
8. (optional) if needed run php artisan migrate


##PLEASE NOTE
{PROJECT_NAME} needs to be changed to your project_name
