KirimCepat - Shipment & Delivery Management System

KirimCepat adalah aplikasi sistem manajemen pengiriman barang dan logistik berbasis web yang dibangun menggunakan framework CodeIgniter 4. Aplikasi ini dirancang untuk mempermudah pengelolaan paket, kurir (delivery), pembayaran online melalui Midtrans Payment Gateway**, serta pelacakan resi secara real-time.

Fitur Utama

- Autentikasi Pengguna:Sistem Login & Register untuk User dan Admin.
- Manajemen Paket:Pembuatan dan pencatatan data paket yang akan dikirim.
- Manajemen Shipment & Delivery:Pengelolaan status pengiriman barang dari gudang hingga ke tangan penerima.
- Integrasi Midtrans:Pembayaran ongkos kirim secara otomatis dan aman (mendukung e-wallet, bank transfer, QRIS, dll).
- Cek Resi / Tracking System:Fitur bagi pelanggan untuk melacak posisi paket mereka secara real-time hanya dengan memasukkan nomor resi.
- Dashboard Admin & User:Halaman khusus admin untuk kontrol penuh dan halaman user untuk melihat riwayat pengiriman.

Teknologi yang Digunakan

- Framework:[CodeIgniter 4.x](https://codeigniter.com/)
- Language:PHP 8.1.2
- Database:MySQL / MariaDB
- Payment Gateway:[Midtrans Sandbox/Production](https://midtrans.com/)
- Libraries & Tools:
  - `FakerPHP/Faker` (Untuk generator data testing)
  - `Kint` (Untuk kebutuhan debugging yang lebih baik)
  - PHPUnit (Untuk unit testing aplikasi)

Struktur Folder Utama

- `app/Config/` - Konfigurasi aplikasi (Database, Routes, App, Midtrans, dll).
- `app/Controllers/` - Logika utama aplikasi (Admin, Auth, Api, Payment, Shipment, dll).
- `app/Models/` - Model database (`UserModel`, `PaketModel`, `ShipmentModel`, `DeliveryModel`, `TrackingModel`).
- `app/Views/` - Tampilan antarmuka pengguna (Dashboard, Auth, Admin layouts, Cek Resi).
- `public/` - Dokumen web root yang berisi `index.php`, aset gambar (QRIS), dan konfigurasi server (`.htaccess`).

Cara Instalasi

1. Clone Repositori
bash
   git clone [https://github.com/username/kirimcepat.git](https://github.com/username/kirimcepat.git)
   cd kirimcepat
