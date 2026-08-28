## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# PENJELASAN index.html

File index.html merupakan halaman utama dari website SIMPUS-Mini. Di dalam file ini terdapat tampilan awal aplikasi, menu untuk berpindah halaman, ringkasan data perpustakaan, dan bagian footer.

## 2.1 Kode Program
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>SIMPUS-Mini | Beranda</title>
</head>
<body>
    <header>
        <h1>SIMPUS-Mini</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Beranda</a></li>
                    <li><a href="buku/list.html">Daftar Buku</a></li>
                    <li><a href="buku/tambah.html">Tambah Buku</a></li>
                    <li><a href="anggota/list.html">Daftar Anggota</a></li>
                </ul>
            </nav>
    </header>

    <main>
        <section>
            <h2>Selamat Datang di Sistem Perpustakaan Mini</h2>
            <p>Aplikasi sederhana untuk mengelola data buku dan anggota perpustakaan.</p>
        </section>

        <section>
            <h2>Ringkasan</h2>
            <article>
                <h3>Total Buku</h3>
                <p>10</p>
            </article>
            <article>
                <h3>Total Anggota</h3>
                <p>8</p>
            </article>
            <article>
                <h3>Sedang Dipinjam</h3>
                <p>3</p>
            </article>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p>
    </footer>
</body>
</html>
```

## 2.2 Penjelasan Program

### Bagian `<head>`
 ```html
 <head>
    <meta charset="UTF-8">
    <title>SIMPUS-Mini | Beranda</title>
 </head>
 ```
- `<head>` digunakan untuk memberikan informasi pada halaman. 
- `<meta charset="UTF-8">` digunakan agar karakter pada halaman dapat terbaca dengan baik. 
- `<title>` digunakan untuk memberikan nama yang muncul pada tab browser.

### Bagian `<header>` - Kepala Halaman
 ```html
 <header>
        <h1>SIMPUS-Mini</h1>
        <nav>...</nav>
 </header>
 ```
- `<h1>SIMPUS-Mini</h1>` adalah judul utama aplikasi. Setiap halaman HTML sebaiknya hanya punya **satu** `<h1>` — ini heading level tertinggi.
- Di dalam `<header>` ada `<nav>` yang berisi menu navigasi ke 4 halaman: Beranda, Daftar Buku, Tambah Buku, dan Daftar Anggota.

### Bagian `<nav>` — Menu Navigasi
```html
<nav>
    <ul>
        <li><a href="index.html">Beranda</a></li>
        <li><a href="buku/list.html">Daftar Buku</a></li>
        <li><a href="buku/tambah.html">Tambah Buku</a></li>
        <li><a href="anggota/list.html">Daftar Anggota</a></li>
    </ul>
</nav>
```

- `<ul>` (unordered list / daftar tak berurutan) membungkus daftar menu.
- Tiap `<li>` (list item) adalah satu item menu, berisi satu tautan `<a>`.
- `href` pada setiap `<a>` menentukan halaman tujuan. 

### Bagian `<main>` — Konten Utama

Berisi dua `<section>`:

**Section 1 — Sambutan**
```html
<section>
    <h2>Selamat Datang di Sistem Perpustakaan Mini</h2>
    <p>Aplikasi sederhana untuk mengelola data buku dan anggota perpustakaan.</p>
</section>
```
Sekadar teks sambutan: satu `<h2>` (judul sub-bagian, satu level di bawah
`<h1>`) dan satu paragraf `<p>`.

**Section 2 — Ringkasan Statistik**
```html
<section>
    <h2>Ringkasan</h2>
    <article>
        <h3>Total Buku</h3>
        <p>10</p>
    </article>
    <article>
        <h3>Total Anggota</h3>
        <p>8</p>
    </article>
    <article>
        <h3>Sedang Dipinjam</h3>
        <p>3</p>
    </article>
</section>
```
- <section> digunakan untuk mengelompokkan bagian-bagian tertentu dalam satu halaman HTML berdasarkan topik atau isi yang sama
- Setiap `<article>` di sini mewakili satu "kartu" statistik yang berdiri sendiri: judul kecil (`<h3>`, satu level di bawah `<h2>`) + angka (`<p>`).
- Angka `10`, `8`, `3` di sini **hanya data contoh (dummy)**, diketik manual. Belum ada logika yang menghitung dari data asli — itu akan dipelajari saat masuk ke pemrograman sisi server/JavaScript.
- Kenapa dipilih `<article>` dan bukan `<div>`? Karena tiap kartu bisa "berdiri sendiri" secara makna — kalau dipindah ke halaman lain pun, informasinya tetap utuh dan masuk akal (misalnya "Total Buku: 10").

### Bagian `<footer>` - Kaki Halaman
```html
<footer>
   <p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p>
</footer>
```
- Bagian `<footer>` digunakan untuk bagian paling bawah halaman. Pada program ini digunakan untuk menampilkan tahun, nama aplikasi, dan keterangan Jobsheet 1.
- `&copy;` adalah **HTML entity** (kode karakter khusus) untuk simbol `©`.
- `&mdash;` adalah entity untuk tanda pisah panjang `—` (em dash). Entity dipakai karena beberapa karakter simbol tidak selalu bisa/aman diketik langsung di HTML, jadi ditulis dalam bentuk kode ini.

## 2.3 KESIMPULAN
File index.html digunakan sebagai halaman beranda dari aplikasi SIMPUS-Mini. Di dalamnya terdapat menu navigasi, informasi singkat mengenai aplikasi, serta ringkasan data perpustakaan. Data yang ditampilkan pada ringkasan masih berupa data yang ditulis langsung pada HTML dan belum terhubung dengan database.