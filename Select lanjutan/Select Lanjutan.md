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
**Penjelasan**


![gambar](Aset/AND.BS.JPG)

## OR
### Struktur
```
Select kolom4,kolom5 from [nama_tabel] where kolom warna="isi kolom warna" And kolom pemilik="isi kolom pemilik"
```
### Contoh
```
select warna,pemilik From mobil where warna="Hitam" or pemilik="Ibrahim";
```

![gambar](Aset/OR.BS.JPG)

## BETWEEN  AND
### Struktur
```
Select * From nama_tabel where kolom harga_rental between 100000
```
### Contoh
```
select * from mobil where harga_rental between 100000 and 200000;
```
![Gambar](Aset/BTWN..JPG)

## NOT BETWEEN
### Struktur
```
Select * From nama_tabel where kolom harga_rental not between nilai 1 and nilai 2;
```
### Contoh
```
select * from mobil where harga_rental not between 100000 and 200000;
```
![gambar](Aset/NBTWN..JPG)

## <=
### Struktur
```
Select * From nama_tabel where kolom harga <= nilai 1
```

### Contoh
```
select * from mobil where harga_rental <=50000;
```
![Gambar](Aset/LB..JPG)

##  =>
### Struktur
```
Select * From nama_tabel where kolom harha_rental >= 50000;
```
### Contoh
```
select * from mobil where harga_rental >=50000;
```
![gambar](Aset/LK..JPG)

## <> ATAU  !=
### Struktur
```
Select * From nama_tabel where kolom harga_rental <> nilai 1
```
### Contoh
```
select * from mobil where harga_rental <>50000;
```
![Gambar](Aset/LK.LB..JPG)


## Tantangan
### Struktur
```
select pemilik from nama_tabel where no_plat=" Nilai no_plat";
```
### Contoh
```
select pemilik from mobil where no_plat ="DD 2650 XY";
```
**Hasil**

![Gambar](Aset/TTN.JPG)

