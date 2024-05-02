# Pesona Indonesia
## Penjelasan
Sebelum responsif (Sebelum penambahan media query):
1. **Fixed Width**: Tata letak elemen-elemen seperti navbar, konten, dan kontainer tidak menyesuaikan lebar layar. Mereka memiliki lebar tetap yang mungkin tidak optimal untuk perangkat dengan lebar layar yang berbeda-beda.
2. **Tidak Responsif terhadap Ukuran Layar**: Tata letak elemen-elemen tidak berubah secara dinamis untuk berbagai ukuran layar. Hal ini dapat menyebabkan masalah tata letak, overflow, atau elemen yang terpotong di layar yang lebih kecil.
3. **Konten Tetap**: Konten seperti teks dan gambar tetap pada posisi dan ukuran aslinya tanpa penyesuaian berdasarkan lebar layar.
Setelah responsif (Setelah penambahan media query):
1. **Fluid Layout**: Tata letak elemen-elemen seperti navbar, konten, dan kontainer dirancang untuk menyesuaikan lebar layar dengan cara yang lebih fleksibel. Mereka dapat memperluas atau menyusut untuk menyesuaikan ukuran layar.
2. Responsif terhadap Ukuran Layar: Tata letak elemen-elemen diatur dengan media query sehingga dapat berubah secara dinamis berdasarkan lebar layar. Hal ini memastikan bahwa tampilan situs tetap optimal di berbagai perangkat dan ukuran layar.
3. Konten Dinamis: Konten seperti teks dan gambar dapat menyesuaikan ukuran dan posisi mereka berdasarkan lebar layar. Ini memastikan bahwa konten tetap mudah dibaca dan diakses bahkan pada layar yang lebih kecil.
### Contoh Kode
```html
<!DOKTYPE HTML>
<html>
  <head>
    <title>  Pesona Indonesia  </title>
    <link rel="stylesheet" href="PesonaI.css">
  </head>
<nav class="navbar">
        <img src="Camera/gambar1.jpg" alt="gambar1">
        <p>Beranda</p>
        <p>Berita</p>
        <p>About</p>
        <img src="Camera/Gambar2.jpg" alt="opsi" id="opsi">
    </nav>

    <div class="background">
        <div class="text">
            <h2>Selamat Datang di Indonesia</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.<br>
                Quasi quibusdam blanditiis natus. Est voluptatibus eum,<br>
                officia expedita unde reiciendis maiores, magni perspiciatis ipsum<br>
                quae ipsam, illum beatae eaque omnis nostrum!</p>
            <input class="button" type="button" value="klik disini!">
        </div>
    </div>

    <h2 align="center">Berita</h2>
    <div class="container">
        <div class="box">
            <img class="gambar" src="Camera/Gambar3.jpg" alt="pantai kuta">
            <h3 align="center">Pantai Kuta</h3>
            <p align="center">Lorem ipsum dolor sit amet<br> consectetur adipisicing elit.<br>
                Quasi quibusdam blanditiis natus.<br> Est voluptatibus eum,<br>
                officia expedita unde reiciendis<br> maiores, magni perspiciatis ipsum<br>
                quae ipsam, illum beatae eaque omnis nostrum!</p>
            <input align="center" class="tombol" type="button" value="lihat selengkapnya!">
        </div>

        <div class="box">
            <img class="gambar" src="Camera/gambar4.jpg" alt="pantai kuta">
            <h3 align="center">Pantai Kuta</h3>
            <p align="center">Lorem ipsum dolor sit amet<br> consectetur adipisicing elit.<br>
                Quasi quibusdam blanditiis natus.<br> Est voluptatibus eum,<br>
                officia expedita unde reiciendis<br> maiores, magni perspiciatis ipsum<br>
                quae ipsam, illum beatae eaque omnis nostrum!</p>
            <input align="center" class="tombol" type="button" value="lihat selengkapnya!">
        </div>

        <div class="box">
            <img class="gambar" src="Camera/gambar5.jpg" alt="pantai kuta">
            <h3 align="center">Pantai Kuta</h3>
            <p align="center">Lorem ipsum dolor sit amet<br> consectetur adipisicing elit.<br>
                Quasi quibusdam blanditiis natus.<br> Est voluptatibus eum,<br>
                officia expedita unde reiciendis<br> maiores, magni perspiciatis ipsum<br>
                quae ipsam, illum beatae eaque omnis nostrum!</p>
            <input align="center" class="tombol" type="button" value="lihat selengkapnya!">
        </div>

        <div class="box">
            <img class="gambar" src="Camera/gambar6.jpg" alt="pantai kuta">
            <h3 align="center">Pantai Kuta</h3>
            <p align="center">Lorem ipsum dolor sit amet<br> consectetur adipisicing elit.<br>
                Quasi quibusdam blanditiis natus.<br> Est voluptatibus eum,<br>
                officia expedita unde reiciendis<br> maiores, magni perspiciatis ipsum<br>
                quae ipsam, illum beatae eaque omnis nostrum!</p>
            <input align="center" class="tombol" type="button" value="lihat selengkapnya!">
        </div>
    </div>
  
   <div class="container2">
   <div> 
   <h4> About </h4>
   </div>  
     <div>
       <p> Perkenalkan Nama Saya Muhammad Fadhil Dari Kelas XI RPL 1 Moto Hidup Saya Bersyukur adalah kunci untuk membuka pintu kebahagiaan.
       </p>
     </div>
  <img src="Camera/Gambar7.jpg" alt="gambar7">
  </div>
</html>
```

```css
body {
  margin: 0;
  padding: 0;
}

.navbar {
  display: flex;
  position: fixed;
  margin-bottom: 500px;
  background-color: white;
  padding-right: 100%;
  justify-content: center;
  box-shadow: 0px 0px 5px 0px;
  z-index: 99;
}

.navbar > img {
  padding-left: 300px;
  padding-right: -10px;
  padding-bottom: 10px;
  padding-top: 10px;
  width: 110px;
  height: 60px;
  margin-left: 60px;
}

.navbar > p {
  padding: 15px;
  cursor: pointer;
  transition: 0.8s all;
}

.navbar p:hover {
  transform: scale(1.3);
}

.navbar p:active {
  transform: scale(0.8);
}

.background {
  background-image: url(Camera/3.jpg);
  background-size: cover;
  width: 1150px;
  height: 400px;
  padding-top: 50%;
  justify-content: center;
  align-items: center;
}

.button {
  background-color: blue;
  color: white;
  padding: 10px;
  border-radius: 5px;
  cursor: pointer;
  border: none;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: -20px;
  width: 100px;
  margin: 0 auto;
}

.button:hover {
  background-image: white;
  color: navy;
  padding: 10px;
  border-radius: 5px;
  cursor: pointer;
  border: none;
}

.text {
  color: white;
  text-align: center;
  padding-top: 5%;
  padding-bottom: 199px;
}

.box {
  border: 1px black;
  border-radius: 10px;
  box-shadow: 2px 2px 2px 2px;
  background-color: white;
  width: 250px;
  height: 450px;
  margin-left: 45px;
}

.tombol {
  background-color: blue;
  color: white;
  margin-left: 40px;
  height: 40px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.tombol:hover {
  background-color: navy;
  color: white;
}

.gambar {
  margin-top: 20px;
  width: 200px;
  height: 150px;
  padding-left: 15px;
  border-radius: 40px;
}

.container {
  display: flex;
  flex-direction: row;
}

.end {
  background-color: blue;
  color: white;
  width: 100%;
  height: 300px;
  margin-top: 5px;
  display: flex;
}

#border {
  width: 200px;
  height: 200px;
  padding-top: 10px;
  border-radius: 100px;
  margin-top: 50px;
  margin-left: 20px;
  margin-right: 30px;
  filter: grayscale(100);
}

#jd {
  text-align: center;
}

.text {
  margin-top: 40px;
  margin-left: 10px;
  display: flex;
  flex-direction: column;
}

.container2 {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
  background-color: steelblue;
  width: 90%;
  max-width: 1100px;
  height: auto;
  margin-top: 100px;
}

.container2 img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  filter: grayscale(100%);
  margin-right: 20px;
}

.container2 h4 {
  text-align: center;
  color: white;
  margin-bottom: 20px;
}

.container2 > div:nth-child(1) {
  order: 1;
}

.container2 > div:nth-child(2) {
  order: 2;
}

.container2 p {
  text-align: center;
  color: white;
  margin-bottom: 20px;
}

@media only screen and (min-width: 600px) {
  .container2 {
    flex-direction: row;
  }

  .container2 > div:nth-child(1) {
    order: 1;
  }

  .container2 > div:nth-child(2) {
    order: 2;
  }
}


```
### Hasil
![gambar](AsetR/BR.jpg)

![gambar](AsetR/R.jpg)