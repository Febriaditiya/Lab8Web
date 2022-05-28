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

### Membuat File Index.PHP

![9.png](img/9.png)

![10.png](img/10.png)

![11.png](img/11.png)

### Membuat File tambah.PHP

![12.png](img/12.png)

![13.png](img/13.png)

![14.png](img/14.png)

### Membuat File ubah.PHP

![15.png](img/15.png)

![16.png](img/16.png)

![17.png](img/17.png)

![18.png](img/18.png)

### Membuat File hapus.PHP

![19.png](img/19.png)

## Tampilan Data Barang

![20.png](img/20.png)

## Tampilan jika ingin menambahkan barang

![21.png](img/21.png)

*Hasil Barang yang di tambahkan*

![22.png](img/22.png)

## Tampilan Jika ingin Ubah Barang

![23.png](img/23.png)

*Hasil barang yang di ubah Pada tabel nomor 2*

![24.png](img/24.png)

## Tampilan Jika ingin menghapus barang 

![25.png](img/25.png)

*Barang yang sudah di hapus pada tabel nomor 3*

![26.png](img/26.png)



