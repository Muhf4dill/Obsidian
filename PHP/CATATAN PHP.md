# Apa itu Web dinamis dan PHP?
Web dinamis adalah jenis situs web yang menggunakan server-side scripting untuk menampilkan konten yang dihasilkan secara dinamis berdasarkan permintaan pengguna. PHP adalah salah satu bahasa pemrograman yang sering digunakan untuk membuat halaman web dinamis. Dengan PHP,dapat membuat situs web yang berinteraksi dengan pengguna, mengolah data dari formulir, mengakses database, dan melakukan berbagai tugas lainnya di sisi server untuk menghasilkan konten yang dinamis.

# ECHO dan Commentar 
Echo adalah perintah dalam PHP yang digunakan untuk menampilkan teks atau nilai variabel ke browser. memungkinkan  untuk menghasilkan output langsung pada halaman web.
Contoh kode:
```php
<?php $nama = "John"; echo "Halo, " . $nama . "!"; // Output: Halo, John! ?>
```
Komentar digunakan dalam kode PHP untuk menambahkan catatan atau penjelasan yang tidak akan dieksekusi oleh interpreter PHP. Ada dua jenis komentar dalam PHP: komentar satu baris yang dimulai dengan // dan komentar blok yang dimulai dengan /* dan diakhiri dengan */. Komentar membantu dalam dokumentasi kode, memudahkan pemahaman, dan memungkinkan pengembang untuk meninggalkan pesan untuk diri mereka sendiri atau pengembang lain yang mungkin bekerja pada proyek yang sama.
Contoh kode
```php
<?php
// Ini adalah komentar satu baris
$nama = "John";

/*
Ini adalah contoh komentar blok
Komentar ini bisa mencakup beberapa baris kode
*/
echo "Halo, " . $nama . "!"; // Output: Halo, John!
?>

```
# Variable const Operator 
 Variable dalam PHP digunakan untuk menyimpan nilai yang dapat berubah. Mereka dideklarasikan dengan awalan tanda dollar ($), diikuti dengan nama variabel. Contohnya adalah $nama_variabel = nilai;.
 Contoh kode
```php
<?php
$nama = "John";
$umur = 25;

echo "Nama: " . $nama . "<br>";
echo "Umur: " . $umur . " tahun";
?>

```
Const adalah konstanta dalam PHP yang nilainya tidak dapat diubah setelah dideklarasikan. Mereka dideklarasikan menggunakan fungsi define(). Contohnya adalah define("NAMA_KONSTANTA", nilai_konstanta);.
Contoh kode
```PHP
<?php
define("NAMA_KONSTANTA", "nilai_konstanta");

echo NAMA_KONSTANTA;
?>

```
Operator dalam PHP digunakan untuk melakukan operasi pada nilai variabel. Beberapa operator dasar termasuk operator aritmatika (+, -, *, /), operator penugasan (=), operator perbandingan (==, !=, <, >, <=, >=), dan operator logika (&&, ||, !). Dengan operator, Anda dapat melakukan berbagai macam manipulasi nilai dalam kode PHP Anda.

Contoh kode
```php
<?php
$nama = "John";
echo "Halo, " . $nama . "!";
?>

```