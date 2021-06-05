# Lab8Web

nama : Dewan Batara Subarjah 

kelas : TI.19.C1

nim : 311910593

# Langkah-langkah Praktikum

# Persiapan

Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.

# Menjalankan MySQL Server

Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![1a](https://user-images.githubusercontent.com/56387936/120875306-63eb4100-c5d5-11eb-8b21-f6d6b5751b1e.JPG)

# Mengakses MySQL Client menggunakan PHP MyAdmin

Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser:  http://localhost/phpmyadmin/

# Membuat Database dan Membuat Tabel

![1b](https://user-images.githubusercontent.com/56387936/120875337-94cb7600-c5d5-11eb-95d8-c6c9806323ff.JPG)

# Menambahkan Data

# Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![1c](https://user-images.githubusercontent.com/56387936/120875392-d1976d00-c5d5-11eb-9991-13502fdece44.JPG)
![1d](https://user-images.githubusercontent.com/56387936/120875415-f12e9580-c5d5-11eb-8b59-68ca4d1af894.JPG)
![1e](https://user-images.githubusercontent.com/56387936/120875429-fbe92a80-c5d5-11eb-83b1-d37cf5fc66d5.JPG)

# Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![1f](https://user-images.githubusercontent.com/56387936/120875471-2f2bb980-c5d6-11eb-92ce-b0742b0cd6f7.JPG)

# Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:

http://localhost/lab8_php_database/

# Membuat file koneksi database

Buat file baru dengan nama koneksi.php\

![1g](https://user-images.githubusercontent.com/56387936/120875496-51bdd280-c5d6-11eb-8bf1-ca79bc362870.JPG)

# Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan

koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”;

![1h](https://user-images.githubusercontent.com/56387936/120875531-7c0f9000-c5d6-11eb-87fa-c7aa3307287a.JPG)

# Membuat file index untuk menampilkan data (Read)

Buat file baru dengan nama index.php

![1i](https://user-images.githubusercontent.com/56387936/120875566-a1040300-c5d6-11eb-8f66-e18b8de969e3.JPG)
![1j](https://user-images.githubusercontent.com/56387936/120875570-a95c3e00-c5d6-11eb-9447-cf7e1e3396f5.JPG)

Hasilnya

![1k](https://user-images.githubusercontent.com/56387936/120875601-d7418280-c5d6-11eb-8732-0d6f4f28077c.JPG)

# Menambah Data (Create)

Buat file baru dengan nama tambah.php

![1l](https://user-images.githubusercontent.com/56387936/120876033-be39d100-c5d8-11eb-9d05-e6f061026a0f.JPG)
![1m](https://user-images.githubusercontent.com/56387936/120876065-e9242500-c5d8-11eb-85ed-da8341c9bb7f.JPG)
![1n](https://user-images.githubusercontent.com/56387936/120876845-6356a880-c5dd-11eb-8e44-bbdcd6cc065e.JPG)

hasilnya : 

![1o](https://user-images.githubusercontent.com/56387936/120876852-6c477a00-c5dd-11eb-945a-e7e6df4229a6.JPG)

# Mengubah Data (Update)

Buat file baru dengan nama ubah.php

![1p](https://user-images.githubusercontent.com/56387936/120876866-8719ee80-c5dd-11eb-8b06-ead35a721afd.JPG)
![1q](https://user-images.githubusercontent.com/56387936/120876870-8c773900-c5dd-11eb-9864-93fa2ab425ce.JPG)
![1r](https://user-images.githubusercontent.com/56387936/120876875-939e4700-c5dd-11eb-942e-4d31b3108aea.JPG)
![1s](https://user-images.githubusercontent.com/56387936/120876879-9862fb00-c5dd-11eb-8b75-ac67a47a1aa2.JPG)

Data sebelum Di ubah :

![2](https://user-images.githubusercontent.com/56387936/120876893-ad3f8e80-c5dd-11eb-95d7-8748656c529f.JPG)

ata setelah Di ubah :

![2a](https://user-images.githubusercontent.com/56387936/120876903-bd576e00-c5dd-11eb-9f1c-40d580f908c7.JPG)

# Menghapus Data (Delete)

Buat file baru dengan nama hapus.php

![2b](https://user-images.githubusercontent.com/56387936/120876948-0b6c7180-c5de-11eb-88ea-56cff9593d52.JPG)

Data sebelum di hapus :

![2c](https://user-images.githubusercontent.com/56387936/120876971-23dc8c00-c5de-11eb-8c48-166279c418f9.JPG)

Data setelah Di Hapus :

![2d](https://user-images.githubusercontent.com/56387936/120877117-ecbaaa80-c5de-11eb-8e03-4031e4f0e5c6.JPG)

# Agar Tampilan nya Terlihat Rapih dan Menarik

# Tambahkan CSS di dalamnya

![2e](https://user-images.githubusercontent.com/56387936/120877160-1a9fef00-c5df-11eb-9939-fc8c0f72bf61.JPG)
