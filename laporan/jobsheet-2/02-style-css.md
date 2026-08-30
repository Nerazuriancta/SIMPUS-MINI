## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# 2. PENJELASAN `style.css`
CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mengatur tampilan dan desain halaman HTML. Dengan CSS, tampilan website dapat dibuat lebih rapi, seperti mengatur warna, ukuran teks, jarak, posisi, tabel, tombol, dan tata letak halaman.

Pada project SIMPUS-Mini, CSS digunakan untuk mengatur tampilan halaman beranda, daftar buku, tambah buku, daftar anggota, dan tambah anggota.

CSS dihubungkan dengan HTML menggunakan tag `<link>` pada bagian `<head>`.

Pada index.html digunakan:
```html
<link rel="stylesheet" href="assets/css/style.css">
```
Sedangkan pada file yang berada di dalam folder buku dan anggota digunakan:
```html
<link rel="stylesheet" href="../assets/css/style.css">
```
Perbedaan tersebut disebabkan oleh lokasi file HTML yang berbeda. ../ digunakan untuk kembali satu folder sebelum menuju folder assets.


## 2.1 Reset & Base

### 2.1.1 `* {` 
Disebut selector Universal.
Artinya: aturan di dalam {} berlaku untuk semua elemen HTML.
Misalnya:
```html
<h1>
<p>
<table>
<button>
<form>
```
semuanya terkena aturan ini.

### 2.1.2 `box-sizing: border-box;`
Mengatur cara browser menghitung ukuran elemen.
Sederhanaya ukuran `widht`, dan `height` akan sudah termasuk padding dan border.
Ini biasanya dibuat supaya ukuran elemen lebih mudah dikontrol.

### 2.1.3 `margin: 0;`
Menghilangkan jarak luar bawaan dari semua elemen
Misalnya `<h1>` secara default punya jarak teretenu. Dengan ini, jarak tersebut dihapus.

### 2.1.4 `padding: 0;`
Menghilangkan jarak dalam bawaan dari semua elemen

### 2.1.5 `}`
Menutup aturan `*`


## 2.2 Body

### 2.2.1 `body {`
body adalah bagian utama yang menampung isi halaman HTML.

### 2.2.2 `font-family: "Segoe UI", Arial, sans-serif;`
Mengatur jenis tulisan.
Browser akan mencoba menggunakan:
1. Segoe UI
2. kalau tidak ada -> Arial
3. kalau tidak aa -> sans-serif

### 2.2.3 `color: #2b2b2b;`
Mengatur warna teks secara umum.
`#2b2b2b` adalah kode warna abu-abu gelap.

### 2.2.4 `background-color: #f5f6f8;`
Mengatur warna background halaman.
sekarang warnanya abu-abu sangatt muda.

### 2.2.5 `line-height: 1.5;`
Mengatur jarak antarbaris tulisan.
`1.5` berarti tinggi baris sekitar 1,5 kali ukuran font.

### 2.2.6 `}`
Menutup pengaturan body


## 2.3 Link `<a>`

### 2.3.1 `a {`
`a` digunakan untuk memilih semua tag:
```html
<a href="...">...</a>
```
jadi ini mengatur semua link.

### 2.3.2 `color: #1d5b8a;`
Mengubah warna link menjadi biru.

### 2.3.3 `text-decoration: none;`
Menghilangkan garis bawah link.

### 2.3.4 `}`
Menutup aturan link


## 2.4 `a:hover {`
`:hover` berarti ketika mouse diarahkan ke elemen

### 2.4.1 `text-decoration: underline;`
ketika mouse diarahkan ke link, garis bawah akan muncul


## 2.5 Header

### 2.5.1 `header {`
mengatur bagian `<header>` pada website, bagian ini adalah area yang berisi:
SIMPUS-MINI | Beranda | Daftar Buku | Tambah Buku | Daftar Anggota

### 2.5.2 `background-color: #1d5b8a;`
Memberikan background biru pada header.

### 2.5.3 `color: #fff;`
Mengatur warna teks menjadi putih.

### 2.5.4 `padding: 1rem 1.5rem;`
Memberikan jarak bagian dalam header.
Ada dua nilai:
- 1rem   -> atas&bawah
- 1.5rem -> kiri & kanan

### 2.5.5 `display: flex;`
Mengaktifkan Flexbox.
Dengan Flexbox, elemen di dalam header di dalam header lebih mudah diatur secara horizontal/vertikal.

### 2.5.6 `align-items: center;`
Mengatur posisi elemen secara vertikal di tengah.

### 2.5.7 `justify-content: space-between;`
Memberikan jarak antara elemen kiri dan kanan.

### 2.5.8 `flex-wrap: wrap;`
Kalau layar terlalu kecil, elemen boleh turun ke baris berikutnya daripada dipaksakan satu baris.


## 2.6 Judul Header

### 2.6.1 `header h1 {`
Artinya: pilih `<h1>` yang berada di dalam `<header>`.

### 2.6.2 `font-size: 1.4rem;`
Mengatur ukuran tulisan.
Semakin besar angkanya -> semakin besar tulisan.


## 2.7 Menu Navigasi

### 2.7.1 `header nav ul {`
Artinya mengatur `<ul>` yang ada di dalam `<nav>` dan `<header>`.
Kode HTML:
```html
<header>
    <nav>
        <ul>
            <li>...</li>
        </ul>
    </nav>
</header>
```

### 2.7.2 `list-style: none;`
Menghilangkan tanda bullet.
Tanpa ini:
- Beranda
- Daftar Buku
- Tambah Buku

### 2.7.3 `display: flex;`
Membuat menu berjajar.

### 2.7.4 `gap: 1.25rem;`
Mengatur jarak antar menu.


## 2.8 Link di Header

### 2.8.1 `header nav a {`
Mengatur link `<a>` yang berada di dalam navigasi header.

### 2.8.2 `color: #fff;`
Warna tulisan menu menjadi putih.

### 2.8.3 `font-weight: 500;`
Mengatur ketebalan tulisan.


## 2.9 Main

### 2.9.1 `main {`
Mengatur bagian `<main>`

### 2.9.2 `max-width: 1000px;`
Menentukan lebar maksimal isi website.
Jadi isi tidak akan melebar lebih dari 1000px.

### 2.9.3 `margin: 2rem auto;`
2rem  -> jarak atas dan bawah.
auton -> kiri dan kanan otomatis.
Efeknya membuat konten berasa di tengah halaman

### 2.9.4 `padding: 0 1.5rem;`
0      -> padding atas dan bawah.
1.5rem -> padding kiri dan kanan.


## 2.10 Section

### 2.10.1 `section {`
Mengatur semua `<section>`

### 2.10.2 `background-color: #fff;`
Background seciton menjadi putih

### 2.10.3 `border-radius: 8px;`
Membuat sudut kotak menjadi bulat.

### 2.10.4 `padding: 1.5rem;`
Memberikan jarak antara isi section dengan pinggir kotak.

### 2.10.5 `margin-bottom: 1.5rem;`
Memberikan jarak dibawah section.

### 2.10.6 `box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08);`
Memberikan bayangan tipis pada kotak.
Kalau dihapus kotaknya akan terlihat lebih datar


## 2.11 Judul Section

### 2.11.1 `section h2 {`
Mengatur `<h2>` yang ebrada di dalam section.

### 2.11.2 `margin-bottom: 1rem;`
Memberikan jarak antara judul dengan isi dibawahnya.

### 2.11.3 `color: #1d5b8a;`
Warna judul menjadi biru.


## 2.12 Kartu Statistik

### 2.12.1 `main section:nth-of-type(2) {`
Artinya: Pilih `<section>` kedua yang ada di dalam `<main>`.
Di `index.html` ada:
```html
<section>
    <h2>Selamat Datang...</h2>
</section>

<section>
    <h2>Ringkasan</h2>
    ...
</section>
```
Jadi yang dipilih adalah **section Ringkasan.**

### 2.12.2 `display: grid;`
Mengaktifkan CSS Grid.
```html
CSS Grid adalah fitur di CSS yang digunakan untuk mengatur elemen dalam bentuk baris dan kolom (grid).

Gampangnya, bayangkan seperti tabel/kotak-kotak. Kamu bisa menentukan berapa kolom yang ingin dibuat dan seberapa besar jaraknya.
```

### 2.12.3 `grid-template-columns: repeat(3, 1fr);`
Membuat 3 kolom dengan ukuran sama.

### 2.12.4 `gap: 1rem;`
Memberikan jarak antar kartu.


## 2.13 Kartu Statistik

### 2.13.1 `main section:nth-of-type(2) article {`
Mengatur setiap `<article>` yang ada di section kedua.
Misalnya:
```html
<article>
    <h3>Total Buku</h3>
    <p>10</p>
</article>
```

### 2.13.2 `background-color: #eef4fa;`
Memberikan background biru muda.

### 2.13.3 `border-radius: 8px;`
Membuat sudut kartu membulat.

### 2.13.4 `padding: 1.25rem;`
Memberikan ruang di dalam kartu.

### 2.13.5 `text-align: center;`
Membuat teks berada di tengah.

## 2.14 Judul Kartu

### 2.14.1 `main section:nth-of-type(2) article h3 {`
Memilih `<h3>` pada kartu section kedua.

### 2.14.2 `font-size: 0.95rem;`
Mengatur ukuran tulisan judul kartu.

### 2.14.3 `color: #55677a;`
Mengatur warna judul.

### 2.14.4 `margin-bottom: 0.5rem;`
Memberikan jarak antara judul dan angka.


## 2.15 Angka Statistik

### 2.15.1 `main section:nth-of-type(2) article p {`
Mengatur angka: 10, 8, 3

### 2.15.2 `font-size: 1.8rem;`
Membuat angka besar.

### 2.15.3 `font-weight: 700;`
Membuat angka tebal.

### 2.15.4 `color: #1d5b8a;`
Membuat angka berwanfa biru.


## 2.16 Tabel

### 2.16.1 `table {`
Mengatur semua tabel.

### 2.16.2 `width: 100%;`
Tabel memenuhi seluruh lebar area yang tersedia.

### 2.16.3 `border-collapse: collapse;`
Membuat garis tabel menyatu sehingga tampil lebih rapi.


## 2.17 `th` dan `td`

### 2.17.1 `th, td {`
Artinya aturan ini berlaku untuk:
- th -> kepala tabel
- td -> isi tabel

### 2.17.2 `text-align: left;`
Teks rata kiri.

### 2.17.3 `padding: 0.65rem 0.75rem;`
Memberikan ruang di dalam sel tabel.

### 2.17.4 `border-bottom: 1px solid #e2e6ea;`
Memberikan garis tipis dibawah setiap sel.


## 2.18 Header Tabel

### 2.18.1 `thead {`
Mengatur bagian `<thead>`

### 2.18.2 `background-color: #1d5b8a;`
Background header tabel biru.

### 2.18.3 `color: #fff;`
Tulisan putih.


## 2.19 Warna Baris Selang-Seling

### 2.19.1 `tbody tr:nth-child(even) {`
Memilih baris genap pada tabel.

### 2.19.2 `background-color: #f7f9fb;`
Memberikan warna abu-abu sangat muda.


## 2.20 Saat Mouse di Tabel

### 2.20.1 `tbody tr:hover {`
Ketika mouse diarahkan ke baris tabel...

### 2.20.2 `background-color: #eef4fa;`
...background baris berubah menjadi biru muda.


## 2.21 Tombol Edit & Hapus

### 2.21.1 `td button {`
Mengatur semua tombol yang ada di dalam tabel.

### 2.21.2 `padding: 0.35rem 0.7rem;`
Memberikan ruang di dalam tombol.

### 2.21.3 `margin-right: 0.35rem;`
Memberikan jarak antar tombol.

### 2.21.4 `border: none;`
Menghilangkan garis tepi tombol bawaan.

### 2.21.5 `border-radius: 4px;`
Menghilangkan garis tepi tombol bawaan.

### 2.21.6 `cursor: pointer;`
Ketika mouse diarahkan ke tombol, cursor berubah menjadi tangan.

### 2.21.7 `font-size: 0.85rem;`
Mengatur ukuran tulisan tombol.


## 2.22 Tombol Edit

### 2.22.1 `td button:first-of-type {`
Memilih tombol pertama.
Dalam kasus ini Edit dan Hapus, jadi yang dipilih adalah **Edit**

### 2.22.2 `background-color: #f0ad4e;` `color: #fff;`
Edit menjadi warna oranye dan tulisan putih.


## 2.23 Tombol Hapus

### 2.23.1 `td button:last-of-type {`
Memilih tombol terakhir, yaitu **Hapus**

### 2.23.2 `background-color: #d9534f;` `color: #fff;`
Hapus menjadi warna merah dan tulisan putih.


## 2.24 Form

### 2.24.1 `form p {`
Mengatur `<p>` yang berada di dalam form.

### 2.24.2 `margin-bottom: 1rem;`
Mmberikan jarak antar bagian form.


## 2.25 Label

### 2.25.1 `form label {`
Mengatur label.
```html
<label for="judul">Judul</label><br>
```

### 2.25.2 `display: block;`
Membuat label berada daam satu baris sendiri.

### 2.25.3 `margin-bottom: 0.35rem;`
Memberikan jarak antara label dan input.

### 2.25.4 `font-weight: 600;`
Membuat label agak tebal.

### 2.25.5 `color: #444;`
Warna label abu-abu gelap.


## 2.26 Inpus & Select

### 2.26.1 `form input, form select {`
Aturan ini berlaku untuk `<input>` dan `<select>`

### 2.26.2 `width: 100%;`
Lebar input menjadi 100% dari area yang tersedia.

### 2.26.3 `max-width: 400px;`
Tetapi maximal hanya400px.
Jadi walaupun layar besar, input tidak akan terlalu panjang.

### 2.26.4 `padding: 0.55rem 0.7rem;`
Memberikann ruang di dalam input.

### 2.26.5 `border: 1px solid #cdd4da;`
Memberikan garis tepi tipis.

### 2.26.6 `border-radius: 4px;`
Mmebuat sudut input sedikit membulat.

### 2.26.7 `font-size: 1rem;`
Mengatur ukuran tulisan dalam input.


## 2.27 FTombol Simpan

### 2.27.1 `form button[type="submit"] {`
Ini memilih button yang mempunyai `type="submit"`

### 2.27.2 `background-color: #1d5b8a;`
Background tombol biru.

### 2.27.3 `color: #fff;`
Tulisan putih

### 2.27.4 `border: none;`
Tidak ada garis tepi.

### 2.27.5 `padding: 0.6rem 1.5rem;`
Mengatur ukuran bagian dalam tombol.

### 2.27.7 `border-radius: 4px;`
Sudut tombol sedikit membulat.

### 2.27.8 `font-size: 1rem;`
Ukuran tulisan tombol.

### 2.27.9 `cursor: pointer;`
Cursor menjadi tangan ketika diarahkan ke tombol.


## 2.28 Hover Tombol Simpan

### 2.28.1 `form button[type="submit"]:hover {`
Artinya ketika mouse diarahkan ke tombol **Simpan**.

### 2.28.2 `background-color: #164869;`
Warna tombol berubah menjadi biru yang lebih gelap.


## 2.29 Footer

### 2.29.1 `footer {`
Mengatur `<footer>`

### 2.29.2 `text-align: center;`
Tulisan berada di tengahh.

### 2.29.3 `padding: 1.25rem;`
Memberikan ruang di dalam footer.

### 2.29.4 `color: #7a8794;`
Warna teks footer menjadi abu-abu.

### 2.29.5 `font-size: 0.9rem;`
Ukuran tulisan sedikit lebih kecil