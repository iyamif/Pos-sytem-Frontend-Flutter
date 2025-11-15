## 📦 POS System – Flutter Frontend

Aplikasi Point of Sale (POS) berbasis Flutter yang terhubung dengan REST API Laravel.
Aplikasi ini dirancang untuk kasir, admin toko, atau bisnis retail dengan fitur lengkap seperti manajemen produk, transaksi penjualan, supplier, dan inventory.
## 🔰 Badges
<p align="left">
  <img src="https://img.shields.io/badge/Flutter-3.x-blue" />
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green" />
  <img src="https://img.shields.io/badge/Backend-Laravel%2010-red" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
  <img src="https://img.shields.io/github/stars/your-username/your-repo?style=social" />
</p>

---
## 🛠 Tech Stack
- Flutter 3+
- Dart
- State Management: Provider / GetX (pilih salah satu yang kamu gunakan)
- HTTP client: http / dio
- Backend: Laravel POS API (Sanctum)
---

### Clone the repository from github.
```bash
https://github.com/iyamif/Pos-sytem-Frontend-Flutter.git
```
### Install dependencies
```bash
flutter pub get
```
### Jalankan aplikasi
```bash
flutter run
```
---
### 👤 Login Default (Jika pakai seeder Laravel)
```
Email : kasri@pos.com
Password : password123
```
---
# 🚀 Fitur Utama

### 🔐 Authentication
- Login menggunakan email & password
- Laravel Sanctum token authentication
- Two-Factor Authentication (2FA) menggunakan OTP

### 🛒 POS (Kasir)
- Input nama Customer
- Tambah produk ke cart
- Hitung total otomatis
- Proses transaksi cepat
- Pengurangan stok otomatis setelah transaksi

### 📦 Product Management
- List produk
- CRUD produk
- Kelola stok & kategori

### 📊 Inventory
- Lihat stok real-time
- Filter stok rendah
- Riwayat perubahan stok

### 📑 Supplier & Purchase Order
- Data supplier
- Riwayat pembelian barang

### 🧾 Order History
- Riwayat transaksi lengkap
- Detail penjualan per item

---
### 🧪 API Backend
```bash
https://github.com/iyamif/Pos-System-Backend-Laravel.git
```
---
### 🤝 Contributing

Pull request welcome!

---
### 📄 License
MIT License.
Silakan gunakan & modifikasi sesuai kebutuhan.

