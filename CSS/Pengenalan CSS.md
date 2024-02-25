# Percobaan Kedua
## Kode CSS
```
button{
Width:150px;
Height:50px;
Color: white;
text-align: right ;
margin-top :50px;
}
```
## Color
### Before
![gambar](WRN.jpg)
### After 
![gambar](WRN.W.jpg)
Color adalah memberikan warna kepada tulisan yang dimana sebelum di kasih color atau warna tulisan nya berwarna hitam. setelah dikasih color atau warna tulisan klik aku berwarna putih
## TEXT-ALIGN

### Before
![gambar](WRN.jpg)
### After 
![gambar](RGHT.jpg)

Text-align adalah memberikan perataan kepada teks dimana saat kita menggunakan text-align = right  membuat posisi teks lebih ke samping kanan. 
## margin-top 
### Before
![Gambar](WRN.jpg)
### After
![gambar](MRGN.jpg)

Margin top digunakan untuk menentukan jarak antara batas atas suatu elemen dengan elemen di atasnya.

## Pemanggilan CSS
### Inline 

### Internal


### External
**Penjelasan**
- `<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
**Code**
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>CSS</title>
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    
    
     </body>
  
</html>
```
## Selektor CSS
### Elemen Selector 



### Class Selector
**Penjelasan**
- `<!DOCTYPE html>`: Mendefinisikan tipe dokumen sebagai HTML versi 5. 
- `<html>`: Menandakan awal dan akhir dari dokumen HTML.
- `<head>`: Berisi informasi tambahan tentang dokumen HTML, seperti judul dan tautan ke file CSS.    
- `<title>CSS</title>`: Menentukan judul dokumen yang akan ditampilkan di tab browser.
- `<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
- `<body>`: Berisi konten yang akan ditampilkan kepada pengguna.  
- `<p class="biru"> ini warna biru </p>`: Elemen ini hanya memiliki satu kelas CSS, yaitu "biru". Oleh karena itu, elemen tersebut akan menerapkan gaya yang telah ditentukan untuk kelas "biru" dalam file CSS atau dalam bagian gaya internal/inline yang berkaitan dengan kelas tersebut. Dan memberikan warna biru. 

**Code**
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>CSS</title>
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    
    
    <p class="biru" >ini warna biru </p>
    
     </body>
  
</html>


```
**Hasil**
![gambar](BR.jpg)



### ID Selector
**Penjelasan**
- `<!DOCTYPE html>`: Mendefinisikan tipe dokumen sebagai HTML versi 5. 
- `<html>`: Menandakan awal dan akhir dari dokumen HTML.
- `<head>`: Berisi informasi tambahan tentang dokumen HTML, seperti judul dan tautan ke file CSS.    
- `<title>CSS</title>`: Menentukan judul dokumen yang akan ditampilkan di tab browser.
- `<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
- `<body>`: Berisi konten yang akan ditampilkan kepada pengguna.  
- Elemen `<p id="hijau"> ini warna hijau </p>` memiliki atribut `id` yang menentukan identitas uniknya dalam dokumen HTML. Dengan demikian, fungsi dari atribut `id` ini adalah untuk memberikan cara yang unik untuk merujuk atau menargetkan elemen tersebut dalam CSS. Dan memberikan warna hijau pada teks. 
**Code**
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>CSS</title>
     



    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    <p style="font-size: 48px;">Welcome CSS!</p>
    <h1>Halo RPL 1</h1>
    
    <p id="hijau" > ini warna hijau </p>
  </body>
  
</html>

```
**Hasil**
![gambar](HJ.jpg)