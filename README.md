# mvc-example
Contoh pengaplikasian MVC menggunakan native PHP secara sederhana.
Pada versi ini, digunakan style psr4 untuk autoloading.

Dalam contoh ini tidak ada routing controller melalui address bar, melainkan menggunakan query browser biasa.

Untuk tabel-nya dapat dibuat terlebih dahulu menggunakan database mysql

CREATE TABLE mhs (id int(11) not null auto_increment primary key, nim char(14) not null, nama varchar(255) not null) -> copy dan paste ke jendela query mysql

Untuk koneksi database, saya menggunakan PDO sebagai pengganti dari mysql_connect() info lengkap, kunjungi http://php.net/manual/en/book.pdo.php

Tugas11PWL_A11.2020.12641_Muhamad Salman Adhim Baqy
