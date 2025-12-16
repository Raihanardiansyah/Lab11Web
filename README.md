# Pratikum 11: PHP OOP
### NAMA : Raihan Ardiansyah
### NIM : 312410396
### KELAS : TI.24.A3

**Langkah-langkah Praktikum**

- A. Persiapan Struktur Folder

<img src="gambar1.png" width="700">

Langkah 1: Pindahkan file Database.php dan Form.php (dari praktikum sebelumnya) ke
dalam folder class/.

- File: form.php

<img src="code1.png" width="700">

- File: database.php

<img src="code2.png" width="700">

- B. Konfigurasi Dasar

<img src="code3.png" width="700">

**Tugas & Implementasi**

Implementasikan konsep modularisasi dari praktikum sebelumnya dan terapkan konsep
routing pada project yang baru.

<img src="code4.png" width="700">

<img src="code5.png" width="700">

<img src="code6.png" width="700">

<img src="code7.png" width="700">

<img src="code8.png" width="700">

<img src="code9.png" width="700">

<img src="web1.png" width="700">

<img src="web2.png" width="700">

# Pratikum 11: Autentikasi dan Session

1. Buat Tabel users

Jalankan SQL berikut di phpMyAdmin pada database latihan_oop:

<img src="gambar2.png" width="700">

2. Insert Data Dummy (User Admin)

Password harus di-hash (dienkripsi). Untuk contoh ini, kita buat user dengan password

"admin123".

Jalankan SQL ini:

<img src="gambar3.png" width="700">

B. Update Routing (index.php)

Kita perlu memodifikasi index.php agar mengecek apakah user sudah login atau belum
sebelum membuka halaman tertentu.

**Buka dan edit file index.php:**

<img src="code10.png" width="700">

C. Membuat Modul User (Login & Logout)

Buat folder baru: module/user/.

1. File: module/user/login.php

Halaman ini berisi Form Login dan logika pemrosesan saat tombol submit ditekan.

<img src="code11.png" width="700">

2. File: module/user/logout.php

File untuk menghapus session.

<img src="code12.png" width="700">

D. Penyesuaian Tampilan (Header)

Kita perlu mengubah template/header.php agar menu navigasi berubah dinamis:

● Jika Belum Login: Tampilkan menu Home dan Login.

● Jika Sudah Login: Tampilkan menu Home, Artikel, dan Logout.

Update template/header.php:

<img src="code13.png" width="700">

**Tugas Praktikum**


<img src="web3.png" width="700">

<img src="web4.png" width="700">

<img src="web5.png" width="700">

<img src="web6.png" width="700">
