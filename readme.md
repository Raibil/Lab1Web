# Lab1Web

# JAWABAN 10 PERTANYAAN
# 1. Apa fungsi deklarasi <!DOCTYPE html> pada dokumen HTML?

Deklarasi <!DOCTYPE html> berfungsi untuk menyatakan bahwa dokumen HTML menggunakan standar HTML5. Deklarasi ini ditulis pada bagian paling awal dokumen HTML.

Contoh:

[<!DOCTYPE html>]

Deklarasi tersebut membantu browser mengetahui standar dokumen HTML yang digunakan.

# 2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?

Tag adalah penanda yang digunakan dalam HTML untuk menunjukkan suatu bagian atau jenis elemen. Tag biasanya ditulis menggunakan tanda kurung siku < >.

Contoh:

<p>

Elemen merupakan bagian HTML yang umumnya terdiri dari tag pembuka, isi, dan tag penutup.

Contoh:

<p>Ini adalah sebuah paragraf.</p>

Atribut merupakan informasi tambahan yang diberikan kepada sebuah elemen. Atribut biasanya ditulis pada tag pembuka.

Contoh:

<a href="https://www.google.com">Google</a>

Pada contoh tersebut, href merupakan atribut yang menentukan tujuan hyperlink.

Jadi, secara sederhana:

Tag = penanda HTML.
Elemen = tag beserta isi dan tag penutupnya.
Atribut = informasi tambahan pada elemen.

# 3. Apa perbedaan <p> dengan <br>? Jelaskan penggunaannya.

Tag <p> digunakan untuk membuat sebuah paragraf.

Contoh:

<p>Ini adalah paragraf pertama.</p>
<p>Ini adalah paragraf kedua.</p>

Sedangkan tag <br> digunakan untuk membuat perpindahan baris.

Contoh:

Baris pertama<br>
Baris kedua

Dengan demikian, <p> digunakan untuk membuat paragraf, sedangkan <br> digunakan untuk berpindah ke baris berikutnya.

# 4. Apa fungsi atribut href pada tag <a>?

Atribut href digunakan untuk menentukan alamat atau tujuan dari sebuah hyperlink.

Contoh:

<a href="https://www.google.com">Google</a>

Ketika teks Google diklik, browser akan menuju alamat yang terdapat pada atribut href.

href juga dapat digunakan untuk menghubungkan halaman dalam satu website.

Contoh:

<a href="halaman2.html">Halaman 2</a>

# 5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?

Hyperlink internal adalah hyperlink yang mengarah ke halaman lain yang masih berada dalam website atau proyek yang sama.

Contoh:

<a href="halaman2.html">Halaman 2</a>

Pada contoh tersebut, halaman2.html merupakan halaman lain dalam proyek HTML yang sama.

Sedangkan hyperlink eksternal adalah hyperlink yang mengarah ke website atau halaman yang berada di luar proyek atau website tersebut.

Contoh:

<a href="https://www.google.com">Google</a>

Jadi, perbedaannya terletak pada tujuan hyperlink. Hyperlink internal mengarah ke halaman dalam proyek yang sama, sedangkan hyperlink eksternal mengarah ke website lain.

# 6. Apa fungsi atribut src dan alt pada tag <img>?

Atribut src digunakan untuk menentukan lokasi atau path file gambar yang akan ditampilkan pada halaman web.

Contoh:

<img src="images/profil.jpg">

Pada contoh tersebut, browser akan mencari gambar profil.jpg di dalam folder images.

Sedangkan atribut alt digunakan untuk memberikan deskripsi atau teks alternatif mengenai gambar.

Contoh:

<img src="images/profil.jpg" alt="Foto profil mahasiswa">

Jadi:

src = menentukan lokasi gambar.
alt = memberikan deskripsi mengenai gambar.

# 7. Apa perbedaan penggunaan <ul> dan <ol>?

Tag <ul> digunakan untuk membuat unordered list, yaitu daftar yang tidak menggunakan urutan angka.

Contoh:

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>

Sedangkan <ol> digunakan untuk membuat ordered list, yaitu daftar yang memiliki urutan.

Contoh:

<ol>
    <li>Belajar HTML</li>
    <li>Belajar CSS</li>
    <li>Belajar JavaScript</li>
</ol>

Dengan demikian:

<ul> = daftar tanpa nomor.
<ol> = daftar berurutan atau bernomor.
<li> = item atau isi dari daftar.

# 8. Apa yang terjadi jika path gambar pada atribut src salah?

Jika path gambar pada atribut src salah, browser tidak dapat menemukan file gambar yang dimaksud sehingga gambar tidak dapat ditampilkan dengan benar.

Misalnya struktur folder:

Lab1Web/
├── index.html
└── images/
    └── profil.jpg

Maka penulisan yang benar adalah:

<img src="images/profil.jpg">

Jika ditulis:

<img src="gambar/profil.jpg">

padahal folder gambar tidak tersedia, maka browser tidak dapat menemukan file tersebut.

Oleh karena itu, path pada atribut src harus sesuai dengan lokasi file gambar.

# 9. Mengapa struktur heading h1 sampai h6 perlu digunakan secara terstruktur?

Heading digunakan untuk membuat judul dan subjudul pada halaman web.

HTML menyediakan enam tingkat heading, yaitu:

<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

<h1> merupakan heading tingkat utama, kemudian dilanjutkan dengan <h2>, <h3>, dan seterusnya.

Penggunaan heading secara terstruktur membantu menyusun isi halaman berdasarkan tingkat judul dan subjudul sehingga struktur informasi pada halaman menjadi lebih jelas.

Contoh:

<h1>Profil Mahasiswa</h1>

<h2>Data Diri</h2>

<h2>Keahlian</h2>

<h3>Keahlian Pemrograman</h3>

Dengan struktur tersebut, pembagian informasi pada halaman menjadi lebih terorganisasi.

# 10. Apa fungsi komentar <!-- ... --> dalam kode HTML?

Komentar HTML digunakan untuk memberikan keterangan atau penanda pada kode HTML.

Komentar tidak ditampilkan pada halaman web ketika dokumen HTML dibuka menggunakan browser.

Contoh:

<!-- Bagian Profil Mahasiswa -->
<h2>Profil Mahasiswa</h2>

Komentar dapat membantu programmer memahami bagian-bagian kode dan memberikan informasi tambahan mengenai kode yang dibuat.

Komentar HTML ditulis menggunakan format:

<!-- Isi komentar -->

## Praktikum 1 - HTML Dasar

### Identitas Mahasiswa

Nama: Nama Mahasiswa

Program Studi: Teknik Informatika

Mata Kuliah: Pemrograman Web

---

## Tujuan Praktikum

Praktikum ini bertujuan untuk memahami struktur dasar HTML, memahami tag-tag dasar HTML, dan membuat dokumen HTML.

## 1. Struktur Dasar HTML

Pada tahap pertama dibuat file `index.html` dengan struktur dasar HTML yang terdiri dari `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>`.

Screenshot:

![Hasil Struktur](images/01struktur.jpg)

## 2. Membuat Paragraf

Pada tahap ini dibuat beberapa paragraf menggunakan tag `<p>`.

Screenshot:

![Hasil Paragraf](images/02paragraf.jpg)

## 3. Menambahkan Judul

Heading ditambahkan menggunakan tag `<h1>` dan `<h2>` untuk membuat judul utama dan subjudul.

Screenshot:

![Hasil Judul](images/03judul.jpg)

## 4. Memformat Teks

Pada tahap ini digunakan beberapa tag pemformatan teks seperti `<b>`, `<i>`, `<strong>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, dan `<sup>`.

Screenshot:

![Hasil Format Teks](images/04formatteks.jpg)

## 5. Menambahkan Gambar

Gambar ditambahkan menggunakan tag `<img>` dengan atribut `src`, `width`, `alt`, dan `title`.

Screenshot:

![Hasil Gambar](images/05tambahgambar.jpg)

## 6. Mengubah Ukuran Gambar

Untuk mengatur ukuran gambar dapat digunakan atribut `width` dan `height`.

Screenshot:

![Hasil Ukuran Gambar](images/06ubahukurangambar.jpg)

## 7. Menambahkan Hyperlink

Dibuat hyperlink internal menuju `halaman2.html` dan hyperlink eksternal menuju website lain.

Screenshot:

![Hasil Hyperlink](images/07hyperlink.jpg)

## 8. Membuat List

Dibuat unordered list menggunakan `<ul>` dan ordered list menggunakan `<ol>`.

Screenshot:

![Hasil List](images/08list.jpg)

## 9. Menambahkan Komentar

Komentar HTML ditambahkan menggunakan sintaks `<!-- komentar -->`.

Screenshot:

![Hasil Komentar](images/09komentar.jpg)

## 10. Menggabungkan Semua Elemen

Semua elemen HTML yang telah dipelajari digabungkan menjadi halaman Profil Mahasiswa.

Screenshot:

![Hasil Menggabungkan Semua Elemen](images/10saeluruhelemen1.jpg)
![Hasil Menggabungkan Semua Elemen](images/10saeluruhelemen2.jpg)

## Kesimpulan

Praktikum HTML Dasar memberikan pemahaman mengenai struktur dokumen HTML, tag, atribut, heading, paragraf, pemformatan teks, gambar, hyperlink, list, dan komentar. Melalui praktikum ini, halaman web sederhana dapat dibuat dan ditampilkan menggunakan browser.
