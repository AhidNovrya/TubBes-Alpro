
# Aplikasi Manajemen Koperasi - Jual Beli & Simpan Pinjam

Tugas Besar Mata Kuliah Algoritma dan Pemrograman.

## 📌 Deskripsi Aplikasi

Aplikasi koperasi berbasis terminal yang menyediakan dua jenis layanan utama:
1. **Koperasi Jual Beli**: Mencatat dan mengelola transaksi pembelian barang.
2. **Koperasi Simpan Pinjam**: Mencatat transaksi simpan dan pinjam dari anggota.

Program ditulis menggunakan bahasa Go, dan menampilkan antarmuka berbasis teks (TUI).

## 👨‍💻 Dibuat Oleh
- Ahid Novryan
- Fergie Alpandi Pramadhani

## 🧩 Fitur Utama

### 🔷 Koperasi Jual Beli
- Input data transaksi jual beli (barang, jumlah, total harga)
- ID transaksi otomatis (format: `KJB01`, `KJB02`, dst.)
- Tampilkan data semua transaksi
- Pencarian transaksi:
  - Berdasarkan ID (Binary Search)
  - Berdasarkan nama barang (Sequential Search)
- Edit, hapus, dan reset data
- Sorting data:
  - Berdasarkan jumlah atau total harga
  - Ascending (Selection Sort)
  - Descending (Insertion Sort)

### 🔷 Koperasi Simpan Pinjam
- Input data simpan atau pinjam anggota
- ID transaksi otomatis (format: `KSP01`, `KSP02`, dst.)
- Validasi input hanya menerima "simpan" atau "pinjam"
- Tampilkan data transaksi
- Tampilkan total simpan dan total pinjam
- Pencarian transaksi:
  - Berdasarkan ID (Binary Search)
  - Berdasarkan nama pelaku (Sequential Search)
- Sorting data:
  - Berdasarkan nama pelaku atau total transaksi
  - Ascending (Selection Sort)
  - Descending (Insertion Sort)
- Edit, hapus, dan reset data

## 📊 Tampilan Terminal
- Tabel ASCII rapi untuk jual beli dan simpan pinjam
- Tampilan berwarna untuk notifikasi sukses/gagal
- Clear screen dan jeda untuk pengalaman pengguna yang nyaman

## 🚀 Cara Menjalankan

1. Pastikan sudah menginstal Go: https://golang.org/dl/
2. Simpan file sebagai `koperasiv2.go`
3. Jalankan lewat terminal:
```bash
go run koperasiv2.go
```

## 💡 Ide Pengembangan Selanjutnya
- Simpan dan baca data dari file (CSV/TXT)
- Fitur anggota koperasi (login/registrasi)
- Dashboard laporan koperasi
- Export ke PDF atau Excel

## 📚 Materi Algoritma yang Diimplementasikan
- Struct array
- Sorting:
  - Selection Sort
  - Insertion Sort
- Searching:
  - Binary Search
  - Sequential Search
- Modular function design
- Validasi dan manipulasi data interaktif

## 🪪 Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan tugas kuliah. Silakan gunakan, modifikasi, dan kembangkan sesuai kebutuhanmu.
