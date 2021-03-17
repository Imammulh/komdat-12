## komdat-12
Repository Github Kelompok 12 KOM 312-Komunikasi Data dan Jaringan
Anggota kelompok 12:
- Fawwaz Khairi         (G64180042)
- Imam Mulhaq Rosyadi   (G64180047)
- Muhamad Khoiru Tobi A (G64180065)
- Ahmad Tedy Murtadho   (G64180082)

<img src="https://lh3.googleusercontent.com/pw/ACtC-3flKG42xMQ8-CIo_0kd2vNdq3oUA6yfS0F-Lm2FueO9du7u0Ydz2W4Q1l4Aky4C0dzLGbVKTTO3Zeybz_MSy-IjiTPeDA2YQZWlLZ8zDmBS0aAJP0rUtMpeAYXmZFpE3ovV7SAdCobtUgd0kOzl1cs1=w450-h253-no?authuser=1" alt="demo-gif" height="500" >

# Aplikasi Web "Hexo"

<img src="https://raw.githubusercontent.com/hexojs/logo/master/hexo-logo-avatar.png" alt="hexo-logo" height="120" align="right">

[Sekilas Tentang](#sekilas-tentang) | [Instalasi](#instalasi) | [Konfigurasi](#konfigurasi) | [Cara Pemakaian](#cara-pemakaian) | [Pembahasan](#pembahasan) | [Referensi](#referensi)


## Sekilas Tentang
[`^ kembali ke atas ^`](#)

**Hexo** adalah framework blog sederhana dan powerfull yang didukung oleh Node.js. Web statis generator yang super cepat ini hanya membutuhkan waktu beberapa detik untuk membangun sebuah website lengkap. 

**Fitur**
- Blazing fast generating
- Support for GitHub Flavored Markdown and most Octopress plugins
- One-command deploy to GitHub Pages, Heroku, etc.
- Powerful API for limitless extensibility
- Hundreds of themes & plugins

## Instalasi
[`^ kembali ke atas ^`](#)

#### Kebutuhan Sistem :
- Sistem Operasi Unix, Linux, Windows, atau Mac
- [Git](http://git-scm.com/)
- [Node.js](http://nodejs.org/) (recommend latest version)

#### Proses Instalasi (Ubuntu) :

Install VM (Virtual Machine) dan Ubuntu :

1. Download VM pada link berikut https://www.virtualbox.org/wiki/Downloads (Kami menggunakan Oracle Virtualbox)
2. Download Ubuntu pada link berikut https://ubuntu.com/download/desktop
3. Selesaikan instalasi VM yang telah didownload
4. Buka Virtualbox yang telah diinstall, klik tombol "New" untuk membuat VM baru. Tentukan nama VM yang akan dibuat sesuai dengan keinginan dan pilih tipe operasi sistem beserta    versinya yang akan diinstal pada VM. Lalu, klik tombol "Next"

   <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image005.png" alt="new VM">
4. Tentukan ukuran memori yang akan dialokasikan untuk VM yang akan dibuat (Sesuaikan dengan kapasitas RAM yang terdapat pada komputer). Lalu, klik tombol "Next"

   <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image007.png" alt="RAM">
5. Pilih 'Create a virtual hard drive now' dan klik tombol "Create"
   
   <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/createVM.png" alt="Virtual Hard Drive"> 
6. Tentukan tipe Hard Drive File. Pilih saja VDI sesuai dengan defaultnya. Lalu, klik tombol "Next"

   <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image009.png" alt="new VM"> 
7. Pada tipe storage pilih "Fixed size" untuk meningkatkan performa VM. Lalu, klik tombol "Next"

   <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image010.png" alt="Storage"> 
8. Tentukan lokasi file VM yang akan diinstal dan ukuran storage yang akan dialokasikan untuk VM. Lalu, klik tombol "Create"

   <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image011.png" alt="Location & Size"> 
 
9. Tunggu proses pembuatan VM selesai

   <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image012.png" alt="Selesai">
10. Setelah VM berhasil dibuat selanjutnya adalah menginstall Ubuntu. Pilih VM yang sudah dibuat. Klik tombol "Settings". Lalu, klik tombol "Storage' dan kemudian "Empty" di   bawah "Controller:IDE". Klik kanan pada ikon "CD/DVD"

    <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image013.png" alt="Mount">
11. Pilih file ISO Ubuntu untuk di-mount

    <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image015.png" alt="Mount 2" >
12. Klik tombol "Ok"

    <img src="https://brb.nci.nih.gov/seqtools/images/ubuntu/image017.png" alt="Mount 3">
13. Terakhir, klik pada VM yang sudah dibuat dan klik tombol "Start" untuk menjalankan VM dan melanjutkan instalasi Ubuntu




Setup VM (Konfigurasi SSH dan port-forwarding) :

Sebelum menginstall hexo pertama - tama akan dilakukan instalasi ubuntu di virtual box dengan konfigurasi pada tab network seperti berikut :

<img src="https://lh3.googleusercontent.com/pw/ACtC-3fADjoPlFzDtAmI62QDfMycKfFQJBqfIsuxXyRnss9zWLDAhg4Dl0SsbVVpSD_P_gGZhLChXzmbHlyFDX726hmbf2fT5sjBZMaf_6RHYN2wzLttygpsAE2Yla-VOdIGvSPukP_z4JT5UGZve8pjN2iR=w1131-h635-no?authuser=0" alt="port-logo" height="500">

##### Login ke server dengan ssh
```
ssh username@localhost -p -2200
```
jika berhasil login, tampilan akan menjadi seperti berikut:

<img src="https://lh3.googleusercontent.com/pw/ACtC-3dAkzMJkRrvi_F9ykl-1G4p-sq7rYPlUkb8EkMdQng4XDktSQBisUlIIliPJZqE8LW04veRwUAWpb8PvlCkPXuWJAgwMQDyw5-TXQhlFdook4GJ7o7sExAUPKFSkV8VJ3Ps25gnXo0pQsU-cwhUTtp7=w1181-h667-no?authuser=1" alt="port-logo" height="500">

install Git dan Node.js :

##### Install Git
<img src="https://git-scm.com/images/logo@2x.png" alt="git-logo" height="90" align="right" >

1. install Git versi terbaru
    ``` 
    $ sudo apt install git
    ```

2. untuk mengecek versi git
    ```
    $ git --version
    ```

##### Install Node.js
<img src="https://camo.githubusercontent.com/720ed473d178f9380291709d2223860ade4f3c7bc368e3fea1ad057b8dc9c6f5/68747470733a2f2f6e6f64656a732e6f72672f7374617469632f696d616765732f6c6f676f2d6c696768742e737667" alt="node.js-logo" height="90" align="right" >

1. install Node.js
    ``` 
    $ sudo apt-get install -y nodejs
    ```

2. untuk mengecek versi 
    ```
    $ node -v
    ```

3. install npm
    ```
    $ sudo apt install npm
    ```
 
4. untuk mengecek versi
   ```
    $ npm -v
    ```

## Konfigurasi
[`^ kembali ke atas ^`](#)

1. siapkan direktori baru untuk project Hexo
```
$ mkdir "name folder"
```
2. buka direktori folder
```
$ cd hexo_1
```
3. Install Hexo
```
$ npm install hexo
``` 
4. Buat sebuah blog
```
$ npx hexo init blog 
```
5. Setelah dibuat, masuk kedalam direktori tersebut
```
$ cd blog
```
6. install semua dependencies yg dibutuhkan Hexo
```
$ npm install
```
7. kemudian jalankan server Hexo
```
$ npx hexo server
```


# Cara Pemakaian
[`^ kembali ke atas ^`](#)

Cara pemakaian **CMS Hexo.io** ini sangat mudah, kamu hanya perlu membuka terminal untuk membuat halaman blog baru:
1. Membuat blog baru
```
$ hexo new "<nama blogmu>"
```
2. Kamu bisa langsung mengedit halaman blog dengan membuka file markdown yang telah dibuat, atau dengan mengedit langsung melalui terminal dengan:
```
$ nano <nama-blog-mu>.md
```
3. Jika kamu membuka melalui file markdownnya kamu hanya perlu menyimpan ulang file tersebut, tetapi jika kamu mengedit melalui terminal kamu perlu mendeploynya terlebih dahulu:
```
$ hexo deploy
```
4. Maka halaman blog baru akan muncul


# Pembahasan
[`^ kembali ke atas ^`](#)
Keunggulan **Hexo.io**
- **Cepat**, Akses website cenderung lebih cepat karena framework ini mengkonversi file Markdown menjadi file html statis).
- **Simple**, Framework ini cukup sederhana dari sisi konfigurasi, cukup gunakan 5 perintah cli (command line interface) blog sudah siap digunakan.
- **Powerful**, Sangat powerful , karena opensource sehingga tersedia banyak plugin & tema yang keren - keren.


Tentu saja, sebuah aplikasi memiliki beberapa kekurangan. Kekurangan yang dimiliki **Hexo.io** antara lain :
- Menyediakan space penyimpanan yang kecil sehingga terdapat limitasi saat ingin mengupload file berukurang besar
- Hexo tidak menggunakan database


Jika dibandingkan dengan CMS sejenisnya seperti **Blogger**, CMS ini memiliki beberapa keunggulan dan kelemahan. Berikut adalah beberapa perbandingan antara kedua CMS ini :

- Template Blogger Susah dicustomisasi
- Pada Blogger Custom Domain belum Support Https
- Hexo sangat mudah untuk dicustom dan karena sifatnya statis, maka bisa ditaruh di Github Page sehingga untuk pengeluaraan budget blog hanya pada domain saja




# Referensi
[`^ kembali ke atas ^`](#)

1. https://hexo.io/docs/
2. https://brb.nci.nih.gov/seqtools/installUbuntu.html
3. https://indrakusuma.web.id/2017/11/30/mengapa-saya-menggunakan-hexo-framework/
4. https://raniaamina.id/membuat-blog-dengan-hexo/
5. 
