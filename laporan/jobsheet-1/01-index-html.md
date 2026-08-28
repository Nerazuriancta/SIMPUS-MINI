## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# 1. PENJELASAN `index.html`

File [index.html](../../index.html) merupakan halaman utama dari website SIMPUS-Mini. Di dalam file ini terdapat tampilan awal aplikasi, menu untuk berpindah halaman, ringkasan data perpustakaan, dan bagian footer.

## 1.1 Fungsi Per-Baris

### 1. `<!DOCTYPE html>`
Menentukan bahwa dokumen menggunakan HTML5.
### 2. `<html lang='id'>`
Menjadi pembungkus seluruh kode HTML dan menunjukkan bahasa halaman adalah Bahasa Indonesia
### 3. `<head>`
Membuka bagian yang berisi informasi halaman
### 4. `<meta charset="UTF-8">`
Menentukan format karakter yang digunakan agar teks dapat ditampilkan dengan baik
### 5. `<title>SIMPUS-Mini | Beranda</title>`
Menentukan judul yang tampil pada tab browser
### 6. `</head>`
Menutup bagian `<head>`
### 7. `<body>`
Membuka bagian yang berisi isi halaman yang akan ditampilkan di browser
### 8. `<header>`
Membuka bagian kepala halaman
### 9. `<h1>SIMPUS-Mini</h1>`
Menampilkan judul utama atau nama aplikasi
### 10. `<nav>`
Membuka bagian menu navigasi
### 11. `<ul>`
Membuat daftar menu dalam bentuk daftar tidak berurutan.
### 12. `<li><a href="index.html">Beranda</a></li>`
Membuat menu Beranda yang mengarah ke index.html.
### 13. `<li><a href="buku/list.html">Daftar Buku</a></li>`
Membuat menu Daftar Buku yang mengarah ke halaman daftar buku.
### 14. `<li><a href="buku/tambah.html">Tambah Buku</a></li>`
Membuat menu Tambah Buku yang mengarah ke halaman tambah buku.
### 15. `<li><a href="anggota/list.html">Daftar Anggota</a></li>`
Membuat menu Daftar Anggota yang mengarah ke halaman daftar anggota.
### 16. `</ul>`
Menutup daftar menu
### 17. `</nav>`
Menutup bagian navigasi.
### 18. `</header>`
Menutup bagian kepala halaman.
### 19. `<main>`
Membuka bagian utama halaman.
### 20. `<section>` pertama
Membuka bagian untuk mengelompokkan isi halaman yang berisi `<h2>` dam `<p>`
### 21. `<h2>Selamat Datang di Sistem Perpustakaan Mini</h2>`
Menampilkan judul bagian sambutan.
### 22. `<p>Aplikasi sederhana untuk mengelola data buku dan anggota perpustakaan.</p>`
Menampilkan paragraf yang menjelaskan aplikasi.
### 23. `</section>`
Menutup bagian sambutan.
### 24. `<section>` kedua
Membuka bagian ringkasan data.
### 25. `<h2>Ringkasan</h2>`
Menampilkan judul bagian ringkasan.
### 26. `<article>`
Membuka bagian untuk data Total Buku.
### 27. `<h3>Total Buku</h3>`
Menampilkan judul data Total Buku.
### 28. `<p>10</p>`
Menampilkan jumlah buku, yaitu 10.
### 29. `</article>`
Menutup bagian data Total Buku.
### 30. `<article>`
Membuka bagian untuk data Total Anggota
### 31. `<h3>Total Anggota</h3>`
Menampilkan judul data Total Anggota.
### 32. `<p>8</p>`
Menampilkan jumlah anggota, yaitu 8.
### 33. `</article>`
Menutup bagian data Total Anggota.
### 34. `<article>`
Membuka bagian untuk data buku yang sedang dipinjam.
### 35. `<h3>Sedang Dipinjam</h3>`
Menampilkan judul data buku yang sedang dipinjam.
### 36. `<p>3</p>`
Menampilkan jumlah buku yang sedang dipinjam, yaitu 3.
### 37. `</article>`
Menutup bagian data buku yang sedang dipinjam.
### 38. `</section>`
Menutup bagian ringkasan.
### 39. `</main>`
Menutup bagian utama halaman.
### 40. `<footer>`
Membuka bagian paling bawah halaman.
### 41. `<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p>`
Menampilkan informasi copyright, tahun, nama aplikasi, dan Jobsheet 1.
### 42. `</footer>`
Menutup bagian footer.
### 43. `</body>`
Menutup bagian isi halaman.
### 44. `</html>`
Menutup seluruh dokumen HTML.

## 1.3 KESIMPULAN
File index.html digunakan sebagai halaman beranda dari aplikasi SIMPUS-Mini. Di dalamnya terdapat menu navigasi, informasi singkat mengenai aplikasi, serta ringkasan data perpustakaan. Data yang ditampilkan pada ringkasan masih berupa data yang ditulis langsung pada HTML dan belum terhubung dengan database.