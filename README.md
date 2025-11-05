# 🍕 Pizza Delivery Web App

A full-featured, production-ready web application for online pizza ordering with home delivery. Browse our menu, customize your order, and enjoy delicious pizza delivered right to your door!

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

---

## ✨ Features

- **🏠 Landing Page** — Beautiful showcase of the pizzeria with featured menu items
- **🍕 Menu Browser** — Explore our full pizza catalog with descriptions and prices
- **🛒 Shopping Cart** — Add, remove, and manage your orders with ease
- **💰 Smart Cost Calculator** — Automatic pricing including base cost, delivery fees, and taxes
- **🎨 Modern UI** — Clean, intuitive interface built with Bootstrap
- **⚡ Optimized Performance** — Fast loading and smooth interactions

---

## 🛠️ Tech Stack

- **Backend:** Laravel (PHP framework)
- **Frontend:** Bootstrap 5 (Responsive CSS framework)
- **Database:** MySQL
- **Server:** Ready to deploy on any PHP-compatible hosting

---

## 🚀 Getting Started

### Prerequisites
- PHP 8.0 or higher
- Composer
- MySQL or MariaDB
- Node.js (optional, for asset compilation)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/pizza-delivery-app.git
   cd pizza-delivery-app
   ```

2. **Install dependencies:**
   ```bash
   composer install
   ```

3. **Set up environment file:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Configure your database in `.env`:**
   ```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=zero81
   DB_USERNAME=root
   DB_PASSWORD=
   ```

5. **Run migrations:**
   ```bash
   php artisan migrate
   ```

6. **Seed the database (optional):**
   ```bash
   php artisan db:seed
   ```

7. **Start the development server:**
   ```bash
   php artisan serve
   ```

8. **Open your browser:**
   ```
   http://localhost:8000
   ```

---

## 📋 Project Structure

```
pizza-delivery-app/
├── app/
│   ├── Http/Controllers/
│   ├── Models/
│   └── ...
├── database/
│   ├── migrations/
│   └── seeders/
├── resources/
│   ├── views/
│   ├── css/
│   └── js/
├── routes/
│   └── web.php
├── public/
└── ...
```

---

## 💡 Future Enhancements

- Payment gateway integration (Stripe, PayPal)
- User authentication & profiles
- Order history
- Reviews and ratings
- Admin dashboard
- Real-time delivery tracking
- SMS notifications

---

## 📝 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Author

**Riccardo Palazzi**
- 📸 Instagram: [@rrrriccardo](https://www.instagram.com/rrrriccardo/)
- 💼 LinkedIn: [Riccardo Palazzi](https://www.linkedin.com/in/riccardo-palazzi-21512221b/)

---

**Happy ordering! 🍕**
