# 🛒 Kasir Supermarket - Laravel + AJAX + Sneat Template

Sistem kasir berbasis web dengan fitur lengkap untuk kebutuhan toko, minimarket, atau supermarket. Dibangun menggunakan **Laravel**, **Blade Sneat Template**, dan 100% AJAX Form.

---

## 🚀 Fitur Unggulan

### 🧱 Modul Utama:
1. **Manajemen Produk**
   - Tambah/Edit/Hapus Produk
   - Pencarian Produk
   - Stok dan Harga

2. **Manajemen Kategori**
   - Kelola kategori produk
   - Kategori tidak bisa ditambah langsung dari form produk

3. **Manajemen Stok Barang**
   - Tambah stok manual
   - Riwayat mutasi stok

4. **Suplai Barang**
   - Catat pengadaan dari supplier
   - Tambah stok otomatis saat suplai masuk

5. **Transaksi Penjualan**
   - Input keranjang belanja
   - Hitung otomatis (subtotal, diskon, total, kembalian)
   - Cetak struk
   - Pencatatan transaksi oleh kasir

6. **Manajemen Pengguna**
   - Role: Admin & Kasir
   - CRUD User

7. **Pengeluaran Operasional**
   - Catat pengeluaran harian
   - Kategori pengeluaran fleksibel
   - Laporan pengeluaran

8. **Pengaturan Toko & Struk**
   - Nama, Alamat, No HP Toko
   - Upload Logo
   - Footer Struk & Preview
   - Ukuran Struk (58mm / 80mm)

---

## 📊 Bonus:
- Dashboard Statistik Penjualan & Pengeluaran
- Laporan PDF / Excel (opsional)
- Sistem 100% AJAX untuk performa tinggi

---

## 📂 Struktur Database (Singkat)

| Tabel            | Keterangan                        |
|------------------|-----------------------------------|
| users            | Data pengguna & role              |
| categories       | Kategori produk                   |
| products         | Informasi produk                  |
| stock_histories  | Riwayat perubahan stok            |
| supplies         | Data suplai dari supplier         |
| members          | Member / pelanggan tetap (opsional) |
| sales            | Transaksi penjualan               |
| sale_items       | Detail barang dalam transaksi     |
| expenses         | Pengeluaran toko                  |
| settings         | Pengaturan toko & struk           |

---

## 🛠️ Teknologi

- Laravel 10+
- Laravel Breeze (tanpa register)
- Sneat – Bootstrap 5 Admin Template (Free)
- AJAX (jQuery atau Fetch API)
- SweetAlert / Toastr untuk notifikasi
- Spatie Laravel Permission (opsional)

---

## ⚙️ Cara Instalasi

```bash
git clone https://github.com/username/kasir-supermarket.git
cd kasir-supermarket
composer install
cp .env.example .env
php artisan key:generate
# Sesuaikan DB di .env
php artisan migrate --seed
php artisan serve

✨ Kontribusi & Pengembangan
Proyek ini bisa dikembangkan lebih lanjut:

-Modul laporan lengkap
-Integrasi printer thermal
-Support multi-gudang
-Aplikasi mobile (Ionic/Flutter)

📄 Lisensi
Proyek ini open-source untuk kebutuhan pembelajaran dan pengembangan pribadi. Jangan dijual ulang tanpa izin 🙏


---

Kalau kamu setuju, aku bisa bantu buatin file ini langsung dan kamu tinggal `README.md` → copy-paste ke folder project.

Perlu juga dibuatin `ERD` atau diagram alur sistem kasirnya? Bisa aku bantu sekalian.


