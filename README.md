# Warung-Nasi-Pos

Warung Nasi POS System
Aplikasi kasir (Point-of-Sale) untuk warung makan kecil, dibangun dengan prinsip Object-Oriented Programming (OOP)

# tentang proyek
Warung Nasi POS System adalah aplikasi desktop kasir yang dikembangkan untuk membantu operasional warung makan kecil (Warung Nasi). Proyek ini dibuat sebagai bagian dari mata kuliah Pemrograman Berorientasi Objek (PBO) dan menerapkan konsep-konsep OOP secara nyata dalam skenario kehidupan sehari-hari.

Aplikasi ini memungkinkan kasir untuk mengelola pesanan dan transaksi dengan mudah melalui antarmuka yang bersih dan intuitif.

# Fitur Utama
- Login & Register — Sistem autentikasi dengan verifikasi email
- Manajemen Menu — Kategori lengkap: Nasi Goreng, Ikan Bakar, Ayam Bakar, Gorengan, Minuman
- Transaksi Kasir — Interface pengelolaan pesanan dan pembayaran
- UI yang Bersih — Desain antarmuka desktop yang user-friendly

# konsep OOP yang Diterapkan
- Encapsulation - Data menu dsn trsndskdi dibungkus dalam class dengan getter/setter 
- Inheritance - class produk mewarisi properti dari class dasar menuItem
- Modularity - setiap fotur (auth, menu, transaksi) dipisahkan ke modul tersendiri

# Cara menjalankannya
persyaratan
- Java JDK 11 atau lebih baru
- IDE (intellIJ IDEA)

# Langkah-langkah
# 1. Clone repository ini
git clone https://github.com/username/warung-nasi-pos.git

# 2. Masuk ke folder proyek
cd warung-nasi-pos

# 3. Buka di IDE dan jalankan file Main.java

Atau buka langsung project-nya di IDE favorit kamu, lalu run Main.java

# Struktur Proyek

warung-nasi-pos
├── src
│   ├── auth
│   │   ├── Login.java
│   │   └── Register.java
│   ├── menu/
│   │   ├── MenuItem.java
│   │   └── MenuManager.java
│   ├── transaction/
│   │   └── TransactionManager.java
│   └── Main.java
├── assets/
│   └── screenshot.png
└── README.md
