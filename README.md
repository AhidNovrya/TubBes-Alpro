
# Aplikasi Manajemen Transaksi Koperasi
Tugas Besar Mata Kuliah Algoritma dan Pemrograman.

## Deskripsi Aplikasi

Aplikasi ini digunakan untuk mencatat dan mengelola transaksi pada sebuah koperasi. Data yang diolah meliputi ID transaksi, nama barang, jumlah, dan total harga. Aplikasi ini juga dilengkapi fitur pencarian, pengurutan, pengeditan, dan penghapusan data.

## Dibuat Oleh

- Ahid Novryan (main coder)
- Fergie Alpandi Pramadhani

## Spesifikasi

- a. Pengguna dapat memasukkan data transaksi sebanyak maksimal 100 data.
- b. ID transaksi akan dibuat otomatis berdasarkan urutan input (format: KOP01, KOP02, ...).
- c. Pengguna dapat mencetak semua data atau mencetak data yang telah diurutkan.
- d. Pencarian data dapat dilakukan berdasarkan:
  - ID Transaksi (Binary Search)
  - Nama Barang (Sequential Search)
- e. Data dapat diurutkan berdasarkan:
  - Jumlah barang
  - Total harga
- f. Metode pengurutan:
  - Ascending: Selection Sort
  - Descending: Insertion Sort
- g. Data dapat diedit atau dihapus secara individual.
- h. Tersedia opsi untuk menghapus seluruh data (reset).

## Extra

- Clear console untuk tampilan bersih
- Navigasi menu berbasis angka
- Tampilan tabel ASCII yang rapi
- Validasi input jumlah dan total harga
- Pemberian warna pada teks (jika terminal mendukung)

## Patch 1.0

- Implementasi menu utama menggunakan tampilan teks interaktif
- Penambahan fitur input, cetak, pencarian, edit, hapus, dan reset data
- Penggunaan struct dan array statis untuk menyimpan data transaksi
- Format tabel ASCII untuk menampilkan data

## Patch 1.1

- Menambahkan fitur sorting:
  - Selection Sort (ascending)
  - Insertion Sort (descending)
- Fitur sorting terintegrasi dengan menu cetak
- Menu modular untuk memilih kriteria pengurutan
- Sorting dilakukan pada salinan data agar binary search tetap berfungsi
- Penanganan kondisi jika data kosong

## Patch 1.2

- Peningkatan validasi input
- Menambahkan jeda agar pengguna bisa membaca output sebelum kembali ke menu
- Penyederhanaan dan modularisasi fungsi (seperti menu cetak dan menu kriteria sort)
- Tampilan konsisten dan user-friendly

## Patch 1.3

- Penyesuaian agar sesuai dengan aturan dosen (tanpa `return` pada fungsi void-style)
- Perbaikan minor untuk alur cetak data setelah sorting
- Struktur kode lebih bersih dan mudah dikembangkan
