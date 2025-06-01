
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

### 📦 Opsi 1: Menjalankan dari File `.exe` (Windows)
1. Buka folder tempat file `koperasi.exe` disimpan.
2. Klik dua kali file `koperasi.exe`, atau buka via CMD:
   ```cmd
   koperasi.exe
   ```
3. Aplikasi akan berjalan di terminal/command prompt.

> Pastikan file `.exe` tidak dipindahkan dari folder yang memiliki dependensi tambahan (jika ada).

### 🛠️ Opsi 2: Menjalankan dari Source Code `.go`
1. Pastikan sudah menginstal Go: https://golang.org/dl/
2. Simpan file sebagai `koperasi.go`
3. Jalankan lewat terminal:
   ```bash
   go run koperasi.go
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

