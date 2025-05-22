# 📚 Tugas web programing ll - Laravel 10

Modul pertemuan 1 - 4
---

## 🚀 Fitur Aplikasi

- CRUD data anggota (tambah, hapus, Delet)
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
### 4. Creat and Import Database

Buat database baru di phpmyadmin dengan nama db_crud

Import file db_crud.sql dari folder web-programing-ll/database/ ke MySQL kamu (via phpMyAdmin atau terminal).

### 5. Atur Koneksi Database di .env
```bash
DB_DATABASE=db_crud
DB_USERNAME=root
DB_PASSWORD=
```

### 6. Jalankan Server
```bash
php artisan serve
```

### berikut adalah screenshoot output dari tugas ini


Buka browser dan akses http://127.0.0.1:8000/helloworld.

![helloworld](https://github.com/yogisaputra92/web-programing-ll/blob/main/screenshoot/Screenshot%20from%202025-05-09%2014-50-14.png)

Buka browser dan akses http://127.0.0.1:8000/getlorem.

![getlorem](https://github.com/yogisaputra92/web-programing-ll/blob/main/screenshoot/Screenshot%20from%202025-05-09%2014-53-02.png)

Buka browser dan akses http://127.0.0.1:8000/anggota.

![getlorem](https://github.com/yogisaputra92/web-programing-ll/blob/main/screenshoot/Screenshot%20from%202025-05-09%2015-05-07.png)
