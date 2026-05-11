# 📦 Evidence Seizure Management System

A web-based application built with Laravel to streamline the recording, tracking, and reporting of seized evidence items.

---

## 🚀 Features

- 🔐 **Authentication** — Secure login system with role-based access control
- 📋 **Evidence Management (CRUD)** — Add, view, edit, and delete seized evidence records
- 📄 **PDF Reports** — Generate and print official evidence seizure reports
- 📊 **Dashboard** — Overview of all evidence data at a glance

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | Laravel |
| Frontend | Bootstrap, Blade Template |
| Database | MySQL |
| Build Tool | Vite |
| Language | PHP |

---

## ⚙️ Installation

### Requirements
- PHP >= 8.0
- Composer
- MySQL
- Node.js & NPM

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/aynafez-666/sistem-penyidik.git
cd sistem-penyidik

# 2. Install PHP dependencies
composer install

# 3. Install Node dependencies
npm install

# 4. Copy environment file
cp .env.example .env

# 5. Generate application key
php artisan key:generate

# 6. Configure your database in .env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=sistem_penyidik
DB_USERNAME=root
DB_PASSWORD=

# 7. Run database migrations & seeders
php artisan migrate --seed

# 8. Build frontend assets
npm run dev

# 9. Start the server
php artisan serve
```

Then open your browser at `http://localhost:8000`

---

## 🗄️ Database Setup

Import the SQL file manually if not using migrations:

1. Create a database named `sistem_penyidik`
2. Import `database/` folder SQL file via phpMyAdmin or CLI:

```bash
mysql -u root -p sistem_penyidik < database/sistem_penyidik.sql
```

---

## 👤 Author

**M. Wirayuda Prawira**
- GitHub: [@aynafez-666](https://github.com/aynafez-666)


---

## 📝 License

This project was developed as part of an academic assignment at **Universitas Islam Kalimantan Muhammad Arsyad Al Banjari (UNISKA) Banjarmasin** — Informatics Engineering.
