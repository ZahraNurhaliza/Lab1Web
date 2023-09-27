# Lab1Web

## Langkah-langkah Praktikum
Persiapan membuka VSCode dan Browser.
Kemudian buat file baru dengan nama lab1_tag_dasar.html dan tambahkan tag dasar dokumen HTML.
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.png)

![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.1.png)


Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.2.png)


1. Membuat Paragraf
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut
```html
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>
```
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.3.png)


• Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.4.png)


Kemudian atur atribut paragraf seperti berikut, dan amati perubahanya.
```html
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p align=”right”>
```
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.5.png)

• Simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser.
Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat
perbedaan lainnya.

![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.6.png)


2. Menambahkan Judul
Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
```html
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.7.png)


• Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.8.png)


3. Memformat teks
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada
penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
```html
<!-- Ini adalah paragraf pertama -->
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
    <p align="center">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi
    Teknik Informatika <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
    HTML.</p>
<!-- Ini adalah paragraf kedua -->
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
    <p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
    tag dasar html.</p>
```
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.9.png)


• Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.10.png)


4. Menyisipkan Gambar
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian
simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan
gambar dari website external.
Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
```html
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo_UPB.png" title="Logo Univeritas Pelita Bangsa">
```
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.11.png)


• Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.12.png)


Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran
gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.
```html
<!-- menambahkan gambar pada dokumen -->
<img src="Logo_UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.13.png)


• Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.14.png)


5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
```html
<!-- menambahkan link navigasi -->
<nav>
<a href="lab1_tag_dasar.html">Dasar HTML</a>
<a href="lab1_halaman2.html">Halaman 2</a>
<a href="http://www.google.com">Halaman Web Eksternal Google</a>
</nav>
<hr>
```
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.15.png)


• Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser
![image](https://github.com/ZahraNurhaliza/Lab1Web/blob/main/screenshot/ss.16.png)


## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag?
• Akan terjadi eror, sebab tag yang dimasukkan tidak sesuai

2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
• Tag paragraph <p> dimulai dan diakhiri dengan tag penutup </p> sebagai akhir dari sebuah paragraph dan akan memasuki baris baru. Sedangkan pada tag <br>, untuk berpindah ke baris selanjutnya

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
• Teks dalam atribut title biasanya lebih panjang daripada deskripsi singkat dalam atribut alt.
alt="Deskripsi singkat gambar" title="Keterangan tambahan tentang gambar"

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
• width (Ukuran lebar gambar), height (ukuran tinggi gambar)
Untuk mengatur ukuran gambar dalam HTML, kita dapat menggunakan atribut width dan height. Namun, sebaiknya mengisi salah satu atribut (biasanya width) dan membiarkan atribut yang lainnya kosong. Ini akan memungkinkan tampilan gambar tetap seimbang

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
• Jika nilai atribut di ganti akan ada perubahan di cara membuka tautan dan pemilihan nilai atribut ini memengaruhi cara tautan dibuka dan cara interaksi antara halaman web saat ini dengan halaman yang ditautkan,pastikan untuk memilih nilai yang sesuai dengan kebutuhan desain.

## SELESAI
