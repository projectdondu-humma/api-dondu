# 📦 DonDu — Backend API Service

[![Laravel](https://img.shields.io/badge/Laravel-11.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com)
[![Payment Gateway](https://img.shields.io/badge/Payment-Midtrans%20Snap-002B49?style=for-the-badge)](https://midtrans.com)

Layanan backend RESTful API untuk platform donasi terintegrasi (uang dan barang layak pakai). Layanan ini bertanggung jawab atas otentikasi pengguna berbasis peran (*RBAC*), manajemen inventaris barang donasi, integrasi transaksi pembayaran digital via payment gateway, penanganan *webhook*, serta pencatatan *audit trail* keuangan.

---

## 🏗️ System Architecture & Tech Stack

* **Core Framework:** Laravel 11 (PHP 8.2+)
* **Database Engine:** MySQL 8.0 (InnoDB)
* **Authentication:** Laravel Sanctum (Token-based API Authentication)
* **Payment Integration:** Midtrans Snap / Core API (Sandbox Environment)
* **Design Pattern:** Repository & Service Pattern + Eloquent API Resources
* **API Testing & Documentation:** Postman Collection / Swagger OpenAPI

---

## 📋 System Requirements

Sebelum menjalankan aplikasi di server lokal, pastikan environment kamu sudah terpasang dependensi berikut:

* PHP `>= 8.2` (dengan ekstensi: `bcmath`, `ctype`, `curl`, `mbstring`, `openssl`, `pdo_mysql`, `tokenizer`, `xml`)
* Composer `>= 2.5`
* MySQL `>= 8.0` atau MariaDB `>= 10.4`
* Git

---

## ⚙️ Installation & Local Setup

Ikuti langkah-langkah berikut untuk mengonfigurasi proyek dari awal:

### 1. Clone Repositori
```bash
git clone https://github.com/projectdondu-humma/api-dondu.git
cd api-dondu


tes aja