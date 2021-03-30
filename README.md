# Praktikum 1 - Pemrograman Web
Nama  : Scipio Rifky Yulianto

NIM   : 311910396

Kelas : TI.19.A.2

Universitas Pelita Bangsa

# LANGKAH 1
# Buka VS Code dan buat file HTML baru. Setelah itu buat struktur dasar HTML
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
![Lab1](https://user-images.githubusercontent.com/56240851/112970340-f0bfdd00-9102-11eb-84e5-e953eb6036b1.png)

# LANGKAH 2
# Membuat 2 buah paragraf dan atur atribut paragraf (Rata Kiri / Rata Kanan / Rata Tengah / Sama Rata)
```
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="justify">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
```
![lab2](https://user-images.githubusercontent.com/56240851/112970563-2c5aa700-9103-11eb-85d5-87d4392963e1.png)

# LANGKAH 3
# Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![lab3](https://user-images.githubusercontent.com/56240851/112970592-354b7880-9103-11eb-91d5-1dfab4a7aab4.png)

# LANGKAH 4
# Memformat Teks menggunakan format-format teks yang ada seperti <b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>,dan <sup>
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
    
![Lab4](https://user-images.githubusercontent.com/56240851/112970606-38deff80-9103-11eb-8acb-7e2bd5498604.png)
    
# LANGKAH 5
# Menyisipkan Gambar dan mengatur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu bersama dengan gambar yg akan disisipkan.
![lab5](https://user-images.githubusercontent.com/56240851/112970627-3e3c4a00-9103-11eb-95fd-1ce447c08242.png)
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
![lab6](https://user-images.githubusercontent.com/56240851/112970650-4300fe00-9103-11eb-8686-88e155a27850.png)

# LANGKAH 6
# Menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
![lab7](https://user-images.githubusercontent.com/56240851/112970664-47c5b200-9103-11eb-8b61-3c418916b904.png)
```
# LANGKAH 7
# Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakana Hyperlink.
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<p align="justify">Ini adalah halaman kedua.</p>

</body>
</html>
```

![Lab8](https://user-images.githubusercontent.com/56240851/112970672-4ac0a280-9103-11eb-95da-ee048bc4ad90.png)

# Jawab Pertanyaan Berikut
```
1. Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
Tidak Ada

2. Apa perbedaan dari tag <p> dengan tag <br> berikan penjelasannya!
perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan dengan tag <p> yg jarak enter nya tidak terlalu jauh.

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
atribut tittle pada tag <img> digunakan untuk memberi judul pada gambar yg disisipkan, sedangkan
atribut alt pada tag <img> digunakan untuk memberi deskripsi pada gambar yg disisipkan

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
Untuk mempertahankan proporsi gambar, namun tetap membuat gambar menjadi besar/kecil, cantumkan
hanya salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misalkan
jika kita menetapkan atribut width=200px (tanpa mencantumkan height), maka web browser akan
menampilkan gambar dengan lebar 200px, dan menghitung secara otomatis tinggi gambar agar gambar
tetap proporsional.

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai antribut tersebut?

Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
```
