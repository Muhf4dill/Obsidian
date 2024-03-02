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
Select * From nama_tabel where kolom harga_rental between nilai 1 and nilai 2;
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
Select * From nama_tabel where kolom harga_rental >= 50000;
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

##  <> ATAU  !=
### Struktur
```
Select * From nama_tabel where kolom harga_rental <> nilai 1
```
### Contoh
```
select * from mobil where harga_rental <> 50000;
Select * from mobil where harga_rental != 50000!;
```
**Penjelasan Perintah 1**
- SELECT:  adalah bagian dari pernyataan SELECT yang   menentukan mengambil semua kolom dari tabel mobil.
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


## IN 
### Struktur
```
Select *  from nama_tabel where kolom_pemilik IN (nilai kolom pemilik)
```

### Contoh
```
Select * from mobil where pemilik IN ("Ibrahim","Baim")
```
**Penjelasan**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE pemilik`: dalam pernyataan SQL digunakan untuk menyaring baris data berdasarkan nilai kolom `pemilik`.
- `IN ("Ibrahim", "Baim")`: adalah kondisi yang kita tentukan menggunakan operator `IN`.  berarti kita hanya ingin baris-baris di mana nilai kolom `pemilik` adalah `Ibrahim` atau `Baim`.
**Kesimpulan**
perintah  `Select * from mobil where pemilik IN ("Ibrahim","Baim")`akan menampilkan semua kolom dari tabel `mobil` di mana nilai kolom `pemilik` adalah `Ibrahim`atau `Baim`.
![gambar](assets/IN.JPG)

## IN + AND
### Struktur
```

```
### Contoh
```
Select * from mobil 
Where warna IN ("Hitam","Silver")
And harga_rental = 50000;
```

![gambar](assets/IAND.JPG)

## IN + OR
### Struktur
```

```
### Contoh
```
Select * from mobil
Where warna IN ("Hitam","Silver")
Harga_rental = 50000;
```

![gambar](assets/IOAND.JPG)

## IN + AND + OPERATOR
### Struktur
```

```
### Contoh
```
Select * from mobil 
Where warna IN ("Hitam","Silver")
And harga_rental > 50000

Select * from mobil 
Where warna IN ("Hitam","Silver")
And harga_rental < 100000
```
![gambar](assets/IAOAND.JPG)
# LIKE

## LIKE %Ib
### Struktur 
```
Select * from nama_tabel where kolom_pemilik LIKE "nilai Ib%"
```

### Contoh 
```
Select * From mobil 
Where pemilik LIKE "Ib%";
```
**Penjelasan**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE pemilik LIKE "Ib%"`: adalah kondisi yang menggunakan operator `LIKE`. `LIKE` digunakan untuk mencocokkan pola string.  Dimana nanti akan menampilkan nilai dari kolom `pemilik` yang huruf namanya berawalan dari `IB`. 
**Kesimpulan**
perintah `Select * From mobil where pemilik LIKE Ib%`: akan menampilkan semua kolom dari tabel `mobil` di mana nilai kolom `pemilik` dimulai dengan `Ib`.
![gambar](assets/LIKEIB.JPG)



## LIKE  %M

### Struktur
```
Select * from nama_tabel where kolom_pemilik LIKE "nilai%m"
```

### Contoh
```
Select * from mobil
Where pemilik LIKE "%M"

```
**Penjelasan**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE pemilik LIKE "%M"`: adalah kondisi yang menggunakan operator `LIKE`. `LIKE`     digunakan untuk mencocokkan pola string. Dimana nanti akan menampilkan nilai dari kolom `pemilik` yang huruf namanya diakhiri `M`.
**Kesimpulan**
Perintah `Select * from mobil Where pemilik LIKE "%M"`: 
akan menampilkan semua kolom dari tabel `mobil` di mana nilai kolom `pemilik` diakhiri dengan `M`.
![gambar](assets/LIKEM.JPG)

## LIKE B%M

### Struktur
```
Select * from nama_tabel where kolom_pemilik LIKE " Nilaib%m"
```
### Contoh
```
Select * from mobil 
Where pemilik LIKE "b%m"
```
**Penjelasan**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE pemilik LIKE "b%m"`: adalah kondisi yang  menggunakan operator `LIKE`. `b` adalah karakter yang harus ada di awal nilai kolom `pemilik`, `%m`adalah wildcard yang cocok dengan nol atau lebih karakter sebelum `m`.
**Kesimpulan**
perintah `Select * from mobil Where pemilik LIKE "b%m"`: akan menampilkan semua kolom dari tabel `mobil` di mana nilai kolom `pemilik` dimulai dengan `b` dan diikuti oleh karakter apa pun sebelum `m`.

![Gambar](assets/LIKEBM.JPG)

## NOT LIKE 
### Struktur
```
Select * from nama_tabel where kolom_peminjam NOT LIKE " Nilai a%"
``` 

### Contoh
```
Select * from mobil where peminjam NOT LIKE "a%";
```
**Penjelasan**
- `SELECT`:  adalah bagian dari pernyataan `SELECT` yang menentukan mengambil semua kolom dari tabel `mobil`.
- `FROM mobil`: adalah bagian dari perintah  `FROM` yang menunjukkan tabel mana yang akan diambil dari data tabel `mobil`.
- `WHERE peminjam NOT LIKE "a%"`: adalah kondisi yang  menggunakan operator `LIKE`. `"a%"` adalah pola yang harus dicocokkan. karena menggunakan operator `NOT LIKE`,  berarti akan menampilkan nilai kolom `peminjam` yang tidak dimulai dengan huruf `a`.
**Kesimpulan**
Perintah `Select * from mobil where peminjam NOT LIKE "a%"` : akan menampilkan semua kolom dari tabel `mobil` di mana nilai kolom `peminjam` tidak dimulai dengan huruf `"a"`.

![gambar](assets/NOTLIKE.JPG)