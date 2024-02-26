# Select lanjutan
## AND
### Struktur
```
Select kolom4,kolom5 from [nama_tabel] where kolom warna="isi kolom warna" And kolom pemilik="isi kolom pemilik"
```
### Contoh
```
select warna,pemilik From mobil where warna="Hitam" AND pemilik="Ibrahim";
```
**PENJELASAN**
- `SELECT warna, pemilik `:  adalah bagian dari perintah `SELECT` yang menentukan kolom mana yang akan ditampilkan dalam hasil query contoh memilih kolom `warna` dan `pemilik` dari tabel `mobil`. 
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE warna="Hitam" AND pemilik="Ibrahim"`: adalah bagian dari perintah `WHERE` yang memberikan kriteria untuk data yang akan dipilih. Kriteria tersebut adalah `warna mobil` adalah `hitam` dan `pemilik mobil` adalah `Ibrahim`.
**KESIMPULAN**
Perintah  `SELECT warna, pemilik FROM mobil WHERE warna='Hitam' AND pemilik='Ibrahim';` digunakan untuk mengambil informasi tentang mobil yang memiliki warna ``"Hitam"`` dan dimiliki oleh `"Ibrahim"`. 

![gambar](AND.BS.jpg)

## OR
### Struktur
```
Select kolom4,kolom5 from [nama_tabel] where kolom warna="isi kolom warna" And kolom pemilik="isi kolom pemilik"
```
### Contoh
```
select warna,pemilik From mobil where warna="Hitam" or pemilik="Ibrahim";
```
**PENJELASAN**
- `SELECT warna, pemilik `:  adalah bagian dari perintah `SELECT` yang menentukan kolom mana yang akan ditampilkan dalam hasil query contoh memilih kolom `warna` dan `pemilik` dari tabel `mobil`. 
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE warna="Hitam" OR pemilik="Ibrahim"`: adalah bagian dari perintah `WHERE` yang memberikan kriteria untuk data yang akan dipilih. Kriteria tersebut adalah `warna mobil` adalah `hitam` dan `pemilik mobil` adalah `Ibrahim`.
**KESIMPULAN**
 Perintah  `SELECT warna, pemilik FROM mobil WHERE warna='Hitam' AND pemilik='Ibrahim';` digunakan untuk mengambil informasi tentang mobil yang memiliki warna ``"Hitam"`` dan dimiliki oleh `"Ibrahim"`. 

![gambar](OR.BS.jpg)

## BETWEEN  AND
### Struktur
```
Select * From nama_tabel where kolom harga_rental between 100000
```
### Contoh
```
select * from mobil where harga_rental between 100000 and 200000;
```
**PENJELASAN**

- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE harga_rental BETWEEN 100000 AND 200000`: adalah bagian dari pernyataan `WHERE`  yang memberikan kriteria untuk data yang akan dipilih. Kriteria tersebut adalah kolom `harga_rental` yang berada kisaran antara `100.000 dan 200.000`.
**KESIMPULAN**
Perintah `SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;` digunakan untuk mengambil semua kolom dari `tabel mobil`di mana nilai kolom `harga_rental` yang berada kisaran antara `100.000` dan `200.000.`
![Gambar](BTWN..jpg)

## NOT BETWEEN
### Struktur
```
Select * From nama_tabel where kolom harga_rental not between nilai 1 and nilai 2;
```
### Contoh
```
select * from mobil where harga_rental not between 100000 and 200000;
```
**PENJELASAN**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE harga_rental NOT BETWEEN 100000 AND 200000`: adalah bagian dari pernyataan `WHERE`  yang memberikan kriteria untuk data yang akan dipilih. Kriteria tersebut adalah kolom `harga_rental` yang tidak berada kisaran antara `100.000 dan 200.000`.
**KESIMPULAN**
Perintah `SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;` digunakan untuk mengambil semua kolom dari `tabel mobil`di mana nilai kolom `harga_rental` yang tidak berada kisaran antara `100.000` dan `200.000.



![gambar](NBTWN..jpg)

## <=
### Struktur
```
Select * From nama_tabel where kolom harga <= nilai 1
```

### Contoh
```
select * from mobil where harga_rental <=50000;
```
**Penjelasan**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`. 
- `WHERE harga_rental <= 50000`: adalah bagian dari pernyataan `WHERE` yang memberikan kriteria data yang akan dipilih. Kriteria tersebut adalah kolom `harga_mobil` kurang atau sama dengan `50.000`.
**Kesimpulan**
Perintah `SELECT * FROM mobil WHERE harga_rental <= 50000;` digunakan untuk mengambil semua data dari tabel `mobil` di mana harga rental mobil kurang dari atau sama dengan `50.000`.
![Gambar](LB..jpg)

##  =>
### Struktur
```
Select * From nama_tabel where kolom harha_rental >= 50000;
```
### Contoh
```
select * from mobil where harga_rental >=50000;
```
**Penjelasan**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang   menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE harga_rental >= 50000`: adalah bagian dari pernyataan `WHERE` yang memberikan kriteria data yang akan dipilih. Kriteria tersebut adalah kolom `harga_rental` lebih besar dari atau sama dengan `50.000`.
**Kesimpulan**
Perintah `SELECT * FROM mobil WHERE harga_rental >= 50000;` digunakan untuk mengambil semua data dari tabel `mobil` di mana harga rental mobil lebih besar dari atau sama dengan `50.000`.
![gambar](LK..jpg)

## <> ATAU  !=
### Struktur
```
Select * From nama_tabel where kolom harga_rental <> nilai 1
```
### Contoh
```
select * from mobil where harga_rental <> 50000;
Select * from mobil where harga_rental != 50000!;
```
**Penjelasan Perintah 1 **
 - `SELECT`:  adalah bagian dari pernyataan `SELECT` yang   menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE harga_rental <> 50000`: adalah bagian dari pernyataan `WHERE` yang memberikan kriteria  data yang akan dipilih. Kriteria tersebut adalah kolom `harga_rental` tidak sama dengan `50.000`.
**Penjelasan Perintah 2**
 - `SELECT`:  adalah bagian dari pernyataan `SELECT` yang   menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE harga_rental != 50000`: adalah cara lain untuk menyatakan kriteria yang sama dengan pernyataan sebelumnya. `Operator !=` digunakan untuk menunjukkan ketidaksamaan, sehingga menampilkan data kolom `harga_rental` tidak sama dengan `50.000`.
**Kesimpulan**
Kesimpulan dari kedua pernyataan tersebut adalah bahwa hasilnya  berisi semua informasi tentang `mobil` yang memiliki `harga_rental` tidak sama dengan `50.000`.
![Gambar](LK.LB..jpg)


## Tantangan
### Struktur
```
select pemilik from nama_tabel where no_plat=" Nilai no_plat";
```
### Contoh
```
select pemilik from mobil where no_plat ="DD 2650 XY";
```
**Penjelasan**
- `SELECT pemilik`: adalah bagian dari pernyataan `SELECT`  yang menentukan kolom mana yang akan ditampilkan dalam hasil query.  Contoh kode diatas menampilkan kolom `pemilik`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE no_plat = DD 2650 XY`: adalah bagian dari pernyataan `WHERE` yang memberikan kriteria data yang akan dipilih. Kriteria tersebut adalah kolom `no_plat` sama dengan `DD 2650 XY`.
**Kesimpulan**
Perintah `SELECT pemilik FROM mobil WHERE no_plat = DD 2650 XY `; digunakan untuk mengambil nama `pemilik_ mobil` dari tabel `mobil` di mana `nomor plat mobil`adalah `DD 2650 XY`.

**Hasil**
![Gambar](TTN.jpg)

