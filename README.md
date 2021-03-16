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

Sebelum menginstall hexo pertama - tama akan dilakukan instalasi ubuntu di virtual box dengan konfigurasi pada tab network seperti berikut :

<img src="https://lh3.googleusercontent.com/pw/ACtC-3fADjoPlFzDtAmI62QDfMycKfFQJBqfIsuxXyRnss9zWLDAhg4Dl0SsbVVpSD_P_gGZhLChXzmbHlyFDX726hmbf2fT5sjBZMaf_6RHYN2wzLttygpsAE2Yla-VOdIGvSPukP_z4JT5UGZve8pjN2iR=w1131-h635-no?authuser=0" alt="port-logo" height="500">

Install VM (Virtual Machine)
1. Download VM pada link berikut https://www.virtualbox.org/wiki/Downloads (Kami menggunakan Virtualbox)
2. Selesaikan instalasi VM yang telah didownload
3. 

install Git dan Node.js 
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


# Cara Pemakaian
[`^ kembali ke atas ^`](#)

Cara pemakaian **CMS Hexo.io** ini sangat mudah, karena aplikasi ini telah menyediakan *interface* yang mudah dimengerti. Berikut untuk lebih jelasnya :
1. 
2. 


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
2. 
3. https://indrakusuma.web.id/2017/11/30/mengapa-saya-menggunakan-hexo-framework/
4. https://raniaamina.id/membuat-blog-dengan-hexo/
5. 
