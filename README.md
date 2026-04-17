# Laravel ESDM Admin Application

## Project Overview

The Laravel ESDM Admin application is a web-based administrative interface designed for managing data related to the Energy and Mineral Resources (ESDM) sector. Built on top of the Laravel framework, this application enables efficient data operations, user management, and role-based access control for administrative users.

## Installation Instructions

To set up the Laravel ESDM Admin application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/esdmwilayah2-dot/Admin.git
   cd Admin
   ```

2. **Install dependencies**:
   Ensure you have Composer installed, then run:
   ```bash
   composer install
   ```

3. **Set up your environment**:
   Copy the example environment file and make the necessary adjustments:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your database credentials and application settings.

4. **Generate the application key**:
   ```bash
   php artisan key:generate
   ```

5. **Run migrations**:
   ```bash
   php artisan migrate
   ```

6. **Start the server**:
   ```bash
   php artisan serve
   ```
   The application will be available at `http://localhost:8000`

## Features

- User authentication and role management
- Responsive admin dashboard
- Data management for employment, projects, and reports
- Graphical presentation of statistics and data
- Easy navigation with a sidebar menu

## Folder Structure

```
├── app                # Contains the core application code
├── bootstrap          # Bootstrap files and cache
├── config             # Configuration files
├── database           # Migration and seed files
├── public             # Public assets
├── resources          # Views and assets
├── routes             # Web routes definition
├── storage            # Logs and compiled views
└── tests              # Automated tests
```

## Usage Guide

After installation, visit `http://localhost:8000` and log in using your admin credentials. Once logged in, you will have access to the admin dashboard where you can manage data, view statistics, and configure application settings.

For detailed guides on specific features, please refer to the documentation provided within the application.

----

> **Note**: Ensure you keep your application updated. Regularly check for Laravel updates and maintain your dependencies using Composer.