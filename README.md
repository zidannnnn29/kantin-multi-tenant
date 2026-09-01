# Kantin Multi-Tenant

Aplikasi web kantin berbasis Laravel 13 dengan konsep multi-tenant.

## Deskripsi

Kantin Multi-Tenant merupakan aplikasi berbasis web yang dikembangkan menggunakan Laravel 13.

Project ini dibuat untuk memenuhi tahapan pembelajaran dan implementasi Laravel, termasuk konfigurasi environment, database, autentikasi, testing, frontend build, serta persiapan fitur multi-tenant.

## Teknologi yang Digunakan

- Laravel 13
- PHP 8.4
- MariaDB / MySQL
- Composer
- Node.js & NPM
- Vite
- Redis
- Laravel Reverb
- Laravel Fortify
- Git & GitHub

## Struktur Project

Project utama berada pada:

```text
I:\ServBay\www\kantin-multi-tenant

Beberapa folder penting:

app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/
vendor/
Konfigurasi Database

Database yang digunakan:

Database : kantin
Host     : 127.0.0.1
Port     : 3306
Username : root

Konfigurasi database disimpan pada file .env.

File .env tidak dimasukkan ke repository Git karena berisi konfigurasi environment lokal.

Redis

Redis digunakan sebagai salah satu komponen pendukung aplikasi.

Konfigurasi Redis menggunakan:

Host : 127.0.0.1
Port : 6379

Redis Server dijalankan pada komputer lokal menggunakan Redis for Windows.

Authentication

Project menggunakan fitur authentication Laravel.

Fitur authentication yang tersedia meliputi:

Login
Register
Logout
Password Reset
Password Confirmation
Email Verification
Two Factor Authentication
Team Authentication
Passkey Authentication

Testing

Testing dilakukan menggunakan Laravel PHPUnit/Pest.

Perintah yang digunakan:

php artisan test

Hasil testing:

Tests: 71 passed
Assertions: 160

Seluruh test yang dijalankan berhasil.

Frontend Build

Frontend menggunakan Vite.

Untuk melakukan build production:

npm run build

Build berhasil dilakukan tanpa error.

Terdapat informasi bahwa package fontaine merupakan package opsional untuk optimized font fallbacks. Hal tersebut tidak menghalangi proses build.

Menjalankan Project

Pastikan berada pada folder project:

cd I:\ServBay\www\kantin-multi-tenant

Kemudian jalankan:

composer run dev

Command tersebut menjalankan beberapa service development:

PHP Laravel Server
Queue Listener
Vite Development Server

Laravel dapat diakses melalui:

http://127.0.0.1:8000

Vite berjalan pada:

http://localhost:5173
Git

Project menggunakan Git sebagai version control.

Untuk melihat status repository:

git status

Untuk menambahkan perubahan:

git add .

Untuk membuat commit:

git commit -m "chore(setup): bootstrap Laravel 13 development environment"

Repository kemudian dapat dihubungkan dengan GitHub menggunakan:

git remote add origin <URL-REPOSITORY-GITHUB>

Kemudian branch utama menggunakan:

git branch -M main

Dan project dapat dikirim ke GitHub dengan:

git push -u origin main
Catatan

File .env tidak boleh di-upload ke GitHub karena berisi konfigurasi environment lokal.

File .env.example digunakan sebagai contoh konfigurasi environment untuk developer lain.

Status Pengerjaan

Project Laravel 13 telah berhasil dibuat dan dikonfigurasi.

Status:

 Laravel 13 berhasil dibuat
 PHP berhasil dikonfigurasi
 Composer berhasil dikonfigurasi
 Database berhasil terhubung
 Migration berhasil dijalankan
 Redis berhasil dijalankan
 Authentication berhasil dikonfigurasi
 Team functionality tersedia
 Automated testing berhasil
 71 test berhasil dijalankan
 Vite production build berhasil
 Git repository berhasil dibuat
 Repository GitHub selesai di-push