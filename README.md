# Lab8Web
PHP dan Database MySQL
### Langkah-langkah Praktikum
### Persiapan
*Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.*

### Mengakses MySQL Client menggunakan PHP MyAdmin
*Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser:* #http://localhost/phpmyadmin/

### Membuat Database
CREATE DATABASE latihan1;

### Memnbuat Tabel

![1.png](img/1.png)

### Menambahkan Data
Menambahkan data melalui phpMyAdmin

![2.png](img/2.png)

### Dan ini melihat database melalui Terminal/CMD

![3.png](img/3.png)

Tampilan Data Barang

![4.png](img/4.png)

### Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![5.png](img/5.png)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab8_php_database/

![6.png](img/6.png)

### Membuat file koneksi database
Buat file baru dengan nama koneksi.php

![7.png](img/7.png)

Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan
koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”;

![8.png](img/8.png)

