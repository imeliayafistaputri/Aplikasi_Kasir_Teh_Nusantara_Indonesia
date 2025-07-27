# TUGAS_ALGORITMA_PEMOGRAMAN_PERTEMUAN_14

## ORDER TEH APP

Aplikasi sederhana berbasis CLI (Command Line Inyerface) untuk pesan teh.
Dibuat dengan Python menggunakan konsep Object-Oriented Programming (OOP)

LINK JIKA INGIN MENCOBA: https://colab.research.google.com/drive/11RYRl9yb2Irk0CFTX60tPRy9D1yZhi8y?usp=sharing

## FITUR
- Pilih Teh dari menu
- Tambah Teh ke daftar menu
- Lihat ringkasan pesanan
- Checkout dengan konfirmasi
- Pesa dan tampilan menggunakan bahasa yang santai

## CARA MENGERJAKAN

- Pastikan sudah install Python minimal versi 3x
- Clone repositori ini atau download file py nya
- Jalankan lewat terminal atau CMD

KODE: pytontehorder.py

## MENU TEH NUSANTARA

1. Teh Hijau - Rp.7000
2. Teh Melati - Rp.7000
3. Teh Oolong - Rp.8000
4. Teh Bunga Rosella - Rp.10000
5. Teh Gurah - Rp.10000

## STRUKTUR KODE

- Teh class

Menyimpan data nama dan harga Teh

-order class

1. add-item(): tambah teh kepesanan
2. show_order(): menunjukan daftar pesanan sama total harga
3. checkout(): konfirmasi beli dan reset pesanan
4. total(): hitung total harga pesanan

-main() function

teh_inventory/
|--teh_nusantara.py           # file utama program
|--inventory.json             # Data menu & stok (otomatis dibuat)
|--backup_inventory.json      # Backup data
|--README.md                  # Penjelasan data

Tempat program jalan, menampilkan menu, dan menerima input dari pengguna

## CONTOH SAAT DIGUNAKAN

---Menu Teh Nusantara---
1. Teh Hijau - Rp7000 (stock: 10)
2. Teh Melati - Rp7000 (stock: 7)
3. Teh Oolong - Rp8000 (stock: 10)
4. Teh Bunga Rosella - Rp10000 (stock: 12)
5. Teh Gurah - Rp10000 (stock: 15)
6. Lihat keranjang pesanan
7. Checkout
8. Laporan Penjualan
9. Backup data
10. Keluar

ketika checkout belum ada pesanan, akan muncul:
belum ada pesanan nih ka
