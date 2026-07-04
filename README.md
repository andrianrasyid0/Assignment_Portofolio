# Analisis Penjualan Alat Tulis UMKM
## Overview
 Proyek ini menganalisis data penjualan dari UMKM alat tulis untuk mengidentifikasi : 
  - Produk terlaris
  - Kota dengan kinerja terbaik
  - Tren penjualan
  - Perilaku pembayaran pelanggan

Analisis dilakukan menggunakan Microsoft Excel dan visualisasi dasboar interaktif.
## About Me
- Saya seorang lulusan Teknik Elektro yang memiliki ketertarikan di bidang data analisis
- Tools yang di biasa digunakan seperti :
  - Python (Pandas,numpy)
  - SQL
  - Excel(Power Query,Pivot table, Dashboard)
## Data Understanding
 - Analisa penjualan UMKM alat tulis , penjual ingin mengetahui product mana yang paling laku dan dari kota mana supaya bisa meningkatkan total sales
 - Data understanding :
   - Dataset : UMKM Alat Tulis
   - Jumlah data : 10005
   - Periode : 2022 - 2025 
   - Kolom :
     - ID_Transaction	Order_date
     - ID_Customer
     - Product
     - Brand
     - Harga
     - Kuantitas
     - Harga_Total
     - Total_Diskon
     - Total_Sales
     - Biaya_Ongkir
     - Grand_Total
     - Status Order
     - Payment_Method
     - Nama_Customer
     - Gender
     - Alamat
     - Kota
- Data Preparation:
   - [x] Menghapus data duplikat
   - [x] Menangani missing value
   - [x] Mengubah tipe data
   - [x] Membuat kolom baru
   - [x] Filtering data
## Proses Analisa
  Analisa dilakukan menggunakan Microsoft Excel
  - Mengimport data = import dataset ke Microsoft Excel
  - Membersihkan data = Menghapus data duplikat,menangani data kososng, memperbaiki format data
  - Menghitung total penjualan = Menggunkan Pivot Table untuk menghitung total penjualan, jumlah transaksi, atau keuntungan berdasarkan kategori, produk, atau wilayah
  - Menghitung profit tiap kategori = Menggunakan rumus Excel seperti SUM, AVERAGE, COUNT
  - Menganalisis tren penjualan tahunan = Menggunakan rumus Excel seperti SUM, AVERAGE, COUNT
  - Menganalisis produk terlaris = Menggunakan rumus Excel seperti SUM, AVERAGE, COUNT
  - Membandingkan performa antar wilayah = Membuat grafik seperti Bar Chart, Column Chart, Line Chart, atau Pie Chart untuk memperjelas hasil analisis.
## Insight & Rekomendasi
  Bagian ini menunjukkan kemampuan menginterpretasikan hasil analisis, bukan hanya menyajikan angka.
- Insight :
  - Kota denpasar berkontribusi 30% dati total sales
  - Kategori Map A4 menjadi product yang banyak terjual di 4 tahun terakhir
  - Penjualan menurun sekitar 50% di 2025 dibandingkan 2024
- Rekomendasi :
  - Fokus promosi pada wilayah dengan penjualan rendah.
  - Optimalkan strategi pemasaran pada periode dengan permintaan tinggi.
<center><img src="Gambar\Dasboard UMKM.png"></img></center>
