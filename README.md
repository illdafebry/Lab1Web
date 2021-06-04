# Praktikum 9

Illda Febryawan Budiono - 311910749 - TI.19.A.2

### LANGKAH-LANGKAH
#### 1. Buka VS Code dan buat file HTML baru dengan nama `lab1_tag_dasar`. Setelah itu buat struktur dasar HTML nya
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
![1](https://user-images.githubusercontent.com/85242560/120760463-58007000-c53e-11eb-898b-35ef0a618c5a.png)
#### 2. Buat 2 buah paragraf dan atur atribut paragraf (Rata Kiri / Rata Kanan / Rata Tengah / Sama Rata). Coding didalam `<body>`
```
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
```
![2](https://user-images.githubusercontent.com/85242560/120760633-8716e180-c53e-11eb-87bf-6e71d13ceff0.png)
#### 3. Tambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![3](https://user-images.githubusercontent.com/85242560/120760741-ad3c8180-c53e-11eb-94f0-aa9d739d821d.png)
#### 4. Format Teks menggunakan format-format teks yang ada seperti `<b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>, dan <sup>.`
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
![4](https://user-images.githubusercontent.com/85242560/120760930-deb54d00-c53e-11eb-9cf9-e857f0bfc7da.png)
#### 5. Sisipkan Gambar dan atur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu bersama dengan gambar yg akan disisipkan.
![5](https://user-images.githubusercontent.com/85242560/120761081-02789300-c53f-11eb-8931-b3e763bcdb56.png)
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="LOGO_UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
![6](https://user-images.githubusercontent.com/85242560/120761152-145a3600-c53f-11eb-81e9-62d3f73d905c.png)
#### 6. Tambahkan hyperlink pada dokumen sebelum heading.
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
![7](https://user-images.githubusercontent.com/85242560/120761260-3489f500-c53f-11eb-8bcd-c03140459f57.png)
#### 7. Buat halaman kedua agar terhubung dengan halaman pertama menggunakana Hyperlink.
```
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
![8](https://user-images.githubusercontent.com/85242560/120761419-5c795880-c53f-11eb-8634-3b4c9c4a52fe.png)

### Tugas
1. Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
```
Ada error ketika saya salah coding Hyperlink <nav> tidak ditutup dengan </nav> jadi tidak terjadi perubahan.
```
2. Apa perbedaan dari tag `<p>` dengan tag `<br>` berikan penjelasannya!
```
Perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan dengan tag <p> yg jarak enter nya tidak terlalu jauh.
```
3. Apa perbedaan atribut `title` dan `alt` pada tag `<img>`, berikan penjelasannya!
```
atribut tittle pada tag <img> digunakan untuk memberi judul pada gambar yg disisipkan, sedangkan atribut alt pada tag <img> digunakan untuk memberi deskripsi pada gambar yg disisipkan
```
4. Untuk mengatur ukuran gambar, digunakan atribut `width` dan `height`. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Agar gambar proporsional, cantumkan salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misalkan jika kita menetapkan atribut width=200px (tanpa mencantumkan height), maka web browser akan menampilkan gambar dengan lebar 200px, dan menghitung secara otomatis tinggi gambar agar gambar
tetap proporsional.
```
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi `(_blank, _self, _top, _parent)`, apa yang terjadi pada masing-masing nilai antribut tersebut?
```
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
```
