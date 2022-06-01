# Lab9Web
| Nama      | Muhammad Choeruman Syah |
| ----------- | ------------------ |
| NIM      | 312010031             |
| Kelas    | TI. 20. A. 1            |

## Langkah-langkah praktikum 8
# 1. Buat file dengan nama header.php
[img1](/sslab9web/sslab9web1.png)

# 2. Buat file dengan nama footer.php
[img2](/sslab9web/sslab9web2.png)

# 3. Buat file dengan nama home.php
[img3](/sslab9web/sslab9web3.png)

# 4 Buat file dengan nama about.php
[img4](/sslab9web/sslab9web4.png)

# 5. Output
    * Halaman Home
[img5](/sslab9web/sslab9web5.png)
    * Halaman About
[img6](/sslab9web/sslab9web6.png)

# Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama.

Lab9_php_database
    ├── config
│   ├── hapus.php
│   ├── koneksi.php
│   ├── tambah.php
│   └── ubah.php
├── layouts
│   ├── footer.php
│   ├── head-static.php
│   ├── header.php
│   ├── main.php
│   ├── tambah.php
│   └── ubah.php
├── static
│   ├── css
│   │   └── style.css
│   └── img
├── index.php
├── tambah.php
└── ubah.php

# Config
Dalam folder tersebut menyimpan file khusus php yang nanti akan dieksekusi
- koneksi.php
[img7](/sslab9web/sslab9web20koneksi.png)

- tambah.php
[img8](/sslab9web/sslab9web8config.png)

- ubah.php
[img9](/sslab9web/sslab9web9config.png)
[img10](/sslab9web/sslab9web10config.png)

# hapus.php
[img11](/sslab9web/sslab9web11config.png)

## Layouts
Untuk menyimpan tampilan utama pada website, dan dibagi pada beberapa file
- head-static.php
[img12](/sslab9web/sslab9web12layouts.png)

- header.php
[img13](/sslab9web/sslab9web13layouts.png)

- main.php
[img14](/sslab9web/sslab9web14layouts.png)

- footer.php
[img15](/sslab9web/sslab9web15layouts.png)

## Static
Untuk menyimpan file yang diperlukan seperti css, js, gambar

- style.css
[img16](/sslab9web/sslab9web16static.png)

## index.php, tambah.php, ubah.php
File utama dan berfungsi sebagai wadah untuk memanggil sub-file di beberapa direktori
- index.php
[img17](/sslab9web/sslab9web17.png)

- tambah.php
[img18](/sslab9web/sslab9web18.png)

- ubah.php
[img2](/sslab9web/sslab9web19.png)

