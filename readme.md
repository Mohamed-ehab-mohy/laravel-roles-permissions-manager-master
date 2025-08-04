# Laravel Roles & Permissions Manager

A simple and extensible Laravel application for managing user roles and permissions. This project provides a foundational structure for building web applications with user access control using Laravel's built-in authorization capabilities and database seeding.

## 🚀 Features

- Role-based access control (RBAC)
- User management
- Role and permission assignment
- Admin panel for managing roles and users
- Laravel 8+ compatible

## 🛠️ Technologies Used

- Laravel (PHP Framework)
- Blade (Laravel Templating)
- Bootstrap 5 (Frontend UI)
- MySQL (Database)

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mohamed-ehab-mohy/laravel-roles-permissions-manager-master.git
   cd laravel-roles-permissions-manager-master
Install dependencies:


composer install
Create environment file:


cp .env.example .env
Generate application key:

php artisan key:generate
Configure .env file with your database credentials:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
Run migrations and seeders:


php artisan migrate --seed
Start the development server:

php artisan serve
Login Credentials:
After seeding, you can use the following default login:

Email: admin@admin.com

Password: password

🧑‍💻 Admin Panel
After login, the admin can manage:

Users

Roles

Assigning permissions to roles and users

📝 License
This project is open-source and available under the MIT License.

Feel free to contribute or customize the project for your needs.


---

If you want to include more details (e.g. screenshots, contribution guidelines), just let me know!