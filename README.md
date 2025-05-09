# 📚 Tugas web programing ll - Laravel 10 - modul 1 - 4

Aplikasi web sederhana berbasis Laravel 10 untuk mengelola data anggota
---

## 🚀 Fitur Aplikasi

- CRUD data anggota (tambah, edit, hapus, lihat)
- invalid-feedback

---

## ⚙️ Cara Instalasi

### 1. Clone Repository
```bash
git clone git@github.com:yogisaputra92/web-programing-ll.git
cd web-programing-ll/project-laravel10
```

### 2. Install Dependency
```bash
composer install
npm install && npm run dev
```

### 3. Buat File .env dan Generate Key
```bash
cp .env.example .env
php artisan key:generate
```

### 4. Atur Koneksi Database di .env
```bash
DB_DATABASE=db_crud
DB_USERNAME=root
DB_PASSWORD=
```
### 5. Import Database

Import file db_crud.sql dari folder web-programing-ll/database/ ke MySQL kamu (via phpMyAdmin atau terminal).

### 6. Jalankan Server
```bash
php artisan serve
```
Buka browser dan akses http://127.0.0.1:8000.


