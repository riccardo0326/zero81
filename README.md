# Pizza Delivery Web Application

A full-stack web application for managing online pizza orders and home delivery. The project provides a complete ordering workflow, from menu browsing and product selection to cart management and automatic order cost calculation.

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge\&logo=laravel\&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge\&logo=bootstrap\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)

---

## Overview

The application simulates a pizza delivery service, allowing customers to browse the available menu, manage their cart, and calculate the final order cost.

The project was developed with **Laravel** as the backend framework, **MySQL** for data persistence, and **Bootstrap 5** for the responsive user interface.

---

## Features

* **Menu Management** — Browse pizzas with descriptions, prices, and available products.
* **Shopping Cart** — Add, remove, and update items before completing an order.
* **Order Cost Calculation** — Automatically calculates item costs, delivery fees, and applicable taxes.
* **Responsive Interface** — Mobile-friendly UI built with Bootstrap 5.
* **Database Integration** — Persistent storage for menu items and application data.
* **Server-Side Architecture** — Backend logic and application routing implemented using Laravel.
* **Seeded Database** — Included seeders for quickly populating the development database.

---

## Tech Stack

| Layer              | Technology             |
| ------------------ | ---------------------- |
| Backend            | Laravel / PHP          |
| Frontend           | Bootstrap 5, HTML, CSS |
| Database           | MySQL / MariaDB        |
| Package Management | Composer               |
| Development Server | Laravel Artisan        |

---

## Getting Started

### Requirements

Before running the application, make sure the following tools are installed:

* PHP 8.0+
* Composer
* MySQL or MariaDB
* Node.js *(optional, depending on the asset pipeline)*

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/riccardo0326/zero81.git
cd zero81
```

#### 2. Install PHP dependencies

```bash
composer install
```

#### 3. Configure the environment

Create a local `.env` file from the example configuration:

```bash
cp .env.example .env
php artisan key:generate
```

#### 4. Configure the database

Update the database configuration in `.env`:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=zero81
DB_USERNAME=root
DB_PASSWORD=
```

Create the corresponding database before continuing.

#### 5. Run migrations

```bash
php artisan migrate
```

#### 6. Populate the database

To load the default development data:

```bash
php artisan db:seed
```

#### 7. Start the application

```bash
php artisan serve
```

The application will be available at:

```text
http://localhost:8000
```

---

## License

This project is released under the **MIT License**.

---

## Author

**Riccardo Palazzi**

* Instagram — [@rrrriccardo](https://www.instagram.com/rrrriccardo/)
* LinkedIn — [Riccardo Palazzi](https://www.linkedin.com/in/riccardo-palazzi-21512221b/)
