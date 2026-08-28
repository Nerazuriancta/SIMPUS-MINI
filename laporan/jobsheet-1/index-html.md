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
 - Bagian `<head>`
 ```html
 <head>
    <meta charset="UTF-8">
    <title>SIMPUS-Mini | Beranda</title>
 </head>
 ```
Bagian `<head>` digunakan untuk memberikan informasi pada halaman. `<meta charset="UTF-8">` digunakan agar karakter pada halaman dapat terbaca dengan baik. Sedangkan `<title>` digunakan untuk memberikan nama yang muncul pada tab browser.

 - Bagian `<header>`
 ```html
 <header>
        <h1>SIMPUS-Mini</h1>
            ...
 </header>
 ```
 Bagian `<header>` digunakan untuk bagian atas halaman. Pada bagian ini terdapat nama aplikasi yaitu SIMPUS-Mini menggunakan tag `<h1>`.

 - Bagian Menu Navigasi
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
 Bagian `<nav>` digunakan untuk membuat menu yang dapat digunakan untuk berpindah halaman.

 Tag `<ul>` digunakan untuk membuat daftar, sedangkan `<li>` digunakan untuk setiap pilihan menu. Tag `<a>` digunakan untuk membuat link ke halaman lain.

 Pada halaman ini terdapat 4 menu yaitu **Beranda, Daftar Buku, Tambah Buku, dan Daftar Anggota**.

 - Bagian `<main>`
 ```html
 <main>
    ...
 </main>
 ```
 Tag `<main>` digunakan untuk menampung isi utama dari halaman. Di dalamnya terdapat bagian sambutan dan ringkasan data perpustakaan.
 
 Pada bagian sambutan terdapat judul:
 ```html
 <h2>Selamat Datang di Sistem Perpustakaan Mini</h2>
 ```
 dan paragraf yang menjelaskan fungsi sederhana dari aplikasi.

 - Bagian Ringkasan
 ```html
 <section>
    <h2>Ringkasan</h2>
    <article>
        <h3>Total Buku</h3>
        <p>10</p>
    </article>
        ...
 </section>
 ```

 Bagian ini digunakan untuk menampilkan ringkasan data perpustakaan.
 Terdapat tiga data yang ditampilkan, yaitu:
 - Total Buku: 10
 - Total Anggota: 8
 - Sedang Dipinjam: 3

 Data tersebut masih berupa data contoh dan belum mengambil data secara langsung dari database.

 - Bagian `<footer>`
 ```html
 <footer>
    <p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p>
 </footer>
 ```
 Bagian `<footer>` digunakan untuk bagian paling bawah halaman. Pada program ini digunakan untuk menampilkan tahun, nama aplikasi, dan keterangan Jobsheet 1.

## 2.3 KESIMPULAN
File index.html digunakan sebagai halaman beranda dari aplikasi SIMPUS-Mini. Di dalamnya terdapat menu navigasi, informasi singkat mengenai aplikasi, serta ringkasan data perpustakaan. Data yang ditampilkan pada ringkasan masih berupa data yang ditulis langsung pada HTML dan belum terhubung dengan database.