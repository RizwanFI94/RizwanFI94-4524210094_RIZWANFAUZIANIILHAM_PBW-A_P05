# 📘 Laporan Praktikum Pertemuan Ke - 5

🧑‍🎓 Rizwan Fauziani Ilham - 4524210094

# 🏫 Website SMP Mentari Ceria

Aplikasi website sekolah berbasis Laravel yang menampilkan informasi kegiatan sekolah dan fitur buku tamu digital untuk SMP Mentari Ceria.

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.2-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8.2">
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
</p>

## Instalasi

### 1. Clone Repository

```bash
git clone RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05
cd smpmentari
```

### 2. Install Dependencies

```bash
# Install PHP dependencies
composer install

# Install Node dependencies
npm install
```

### 3. Setup Environment

```bash
# Copy file .env
cp .env.example .env

# Generate application key
php artisan key:generate
```

### 4. Setup Database

```bash
# Jalankan migrasi
php artisan migrate
```

### 5. Build Assets

```bash
# Development
npm run dev

# Production
npm run build
```

### 6. Jalankan Aplikasi

```bash
# Menggunakan built-in server
php artisan serve

# Atau menggunakan composer script (recommended)
composer dev
```

Aplikasi akan berjalan di: `http://localhost:8000`

## 📋 Daftar Isi

- [Tentang Aplikasi](#-tentang-aplikasi)
- [Fitur Utama](#-fitur-utama)
- [Tech Stack](#-tech-stack)
- [Persyaratan Sistem](#-persyaratan-sistem)
- [Instalasi](#-instalasi)
- [Penggunaan](#-penggunaan)
- [Struktur Database](#-struktur-database)
- [Struktur Project](#-struktur-project)
- [Pengembangan](#-pengembangan)
- [Testing](#-testing)
- [Lisensi](#-lisensi)

## 🎯 Tentang Aplikasi

Website SMP Mentari Ceria adalah aplikasi web sederhana yang dibangun dengan Laravel 12 untuk menampilkan informasi dan kegiatan sekolah. Aplikasi ini dilengkapi dengan fitur buku tamu digital yang memungkinkan pengunjung meninggalkan pesan dan kesan mereka.

### Fitur Halaman:

1. **Halaman Home** - Menampilkan kegiatan-kegiatan terbaru sekolah
2. **Buku Tamu** - Formulir interaktif untuk pengunjung meninggalkan pesan

## ✨ Fitur Utama

- ✅ **Tampilan Kegiatan Sekolah** - Showcase kegiatan terbaru dengan card design
- ✅ **Buku Tamu Digital** - Pengunjung dapat meninggalkan pesan
- ✅ **Form Validasi** - Validasi input untuk nama, email, dan pesan
- ✅ **Real-time Feedback** - Notifikasi sukses/error setelah submit
- ✅ **Responsive Design** - Tampilan optimal di semua device
- ✅ **Timestamp Relatif** - Menampilkan waktu pesan (e.g., "2 jam yang lalu")
- ✅ **Modern UI/UX** - Desain clean dengan Tailwind CSS

## 🛠️ Tech Stack

### Backend
- **Laravel** 12.x - PHP Framework
- **PHP** ^8.2 - Programming Language
- **MySQL** - Database (Development)
- **Eloquent ORM** - Database Management

### Frontend
- **Blade Templates** - Template Engine
- **Tailwind CSS** 4.0 - CSS Framework
- **Vite** 7.0 - Asset Bundler & HMR
- **Axios** - HTTP Client

### Development Tools
- **Laravel Sail** - Docker Development Environment
- **Pest PHP** - Testing Framework
- **Laravel Pint** - Code Style Fixer
- **Concurrently** - Multi-command Runner

## 📸 Hasil Screenshot Tampilan Website SMP Mentari

### Halaman Home
<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.05%20(2).jpeg" />

### Halaman Buku Tamu
<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.05%20(4).jpeg" />

### Halaman Register
<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.04%20(2).jpeg" />

### Halaman Login
<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.04%20(1).jpeg" />

### Halaman Dashboard

Dashboard di akses ketika sudah login dan bisa mengatur profile dan pusat kendali dari website SMP Mentari

<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.03.jpeg" />

<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.04.jpeg" />

Kendali atau mengelola kegiatan SMP Mentari

<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.03%20(1).jpeg" />

Kelola Buku Tamu

<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.05%20(4).jpeg" />

Konfigurasi tampilan Home Kegiatan per page dengan default nya 6 (Bisa diubah sesuai keinginan)

<img width="1920" height="1080" alt="image" src="https://github.com/RizwanFI94/RizwanFI94-4524210094_RIZWANFAUZIANIILHAM_PBW-A_P05/blob/5d4eaca66d4b532e7d4532940a4777902619b651/img/WhatsApp%20Image%202026-10-13%20at%2011.14.03%20(2).jpeg" />

<p align="center">
Made with Rizwan for SMP Mentari Ceria
</p>
