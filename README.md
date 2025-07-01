# PERSONAL WEB

**Deskripsi**

Studi kasus ini bertujuan untuk membangun sebuah aplikasi web personal yang bersifat dinamis, di mana pemilik web dapat mengelola konten secara mandiri melalui halaman admin. Aplikasi dikembangkan menggunakan PHP dan menyimpan data menggunakan database MySQL. Tampilan antarmuka dirancang menggunakan Tailwind CSS agar responsif, modern, dan mudah dikustomisasi. 

Website ini memiliki dua bagian utama: 
1. Halaman Publik, yang dapat diakses oleh semua pengunjung.
2. Halaman Admin, yang hanya dapat diakses setelah login, digunakan untuk
mengelola konten.

**Fitur-fitur**
1. Login & Logout (Halaman login admin dengan validasi, Sistem sesi untuk melindungi halaman admin, Logout untuk mengakhiri sesi dengan aman)
2. Manajemen Artikel (Tambah artikel (judul + isi),  Edit artikel yang sudah ada, Hapus artikel, Tampilkan daftar artikel di halaman utama, Sidebar "Daftar Artikel" yang terupdate otomatis)
3. Manajemen Gallery (Upload gambar beserta judul, Ganti gambar dan judul yang sudah ada, Hapus gambar, Tampilkan gambar di halaman galeri publik dalam grid responsif)
4. Manajemen About (Tambah deskripsi tentang diri, Edit dan hapus bagian “About”, Tampilkan deskripsi di halaman publik about.php)
5. Dashboard Statistik Admin (Menampilkan ringkasan jumlah: Artikel & Gambar di gallery)
6. Halaman Publik yang Rapi & Dinamis (Artikel terbaru ditampilkan otomatis, Galeri responsif dan ringan, Tentang Saya tampil dengan struktur informatif)

**Teknologi yang Digunakan**
1. Bahasa Pemrograman : PHP
2. Database : MySQL
3. Frontend : Tailwind CSS, HTML
4. Server Side : Apache / XAMPP

**Struktur Folder**

![Screenshot 2025-06-23 115243](https://github.com/user-attachments/assets/0717420f-1eba-4070-bf7e-5dfcb35055de)

**User Interface Halaman Publik**

A. Halaman Home / Artikel

Halaman Home atau Halaman Artikel adalah halaman yang menampilkan daftar artikel dan artikel terbaru.


B. Halaman Gallery

Halaman Gallery adalah halaman yang menampilkan foto-foto mahasiswa secara individu.


C. Halaman About

Halaman About adalah halaman yang menampilkan deskripsi tentang saya atau profile dari masing-masing mahasiswa.


**User Interface Halaman Admin**

A. Halaman Login

Halaman Login adalah halaman yang digunakan untuk mengakses halaman admin, diperlukan username dan password.


B. Halaman Beranda

Halaman Beranda merupakan halaman yang menampilkan statistik Jumlah Artikel dan Jumlah Gallery.

C. Halaman Kelola Artikel

Halaman Kelola Artikel adalah halaman untuk mengelola Artikel dimulai dari Tampil Artikel, Tambah Artikel, Edit Artikel dan Hapus Artikel.


D. Halaman Kelola Gallery

Halaman Kelola Gallery adalah halaman untuk mengelola Gallery dimulai dari Tampil Gallery, Tambah Gallery, Edit Gallery dan Hapus Gallery.


E. Halaman About

Halaman About adalah halaman untuk mengelola About dimulai dari Tampil About, Tambah About, Edit About dan Hapus About.
