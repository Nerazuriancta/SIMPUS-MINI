## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# 2. PENJELASAN `buku/list.html`
File [buku/list.html](../../buku/list.html) merupakan halaman yang digunakan untuk menampilkan daftar buku pada website SIMPUS-Mini. Di dalam file ini terdapat tabel yang berisi data buku seperti judul, pengarang, tahun, stok, dan aksi.

## 2.1 Fungsi Per-Baris

### 1. `<!DOCTYPE html>`
Menentukan bahwa dokumen menggunakan HTML5.
### 2. `<html lang='id'>`
Menjadi pembungkus seluruh kode HTML dan menunjukkan bahasa halaman adalah Bahasa Indonesia
### 3. `<head>`
Membuka bagian yang berisi informasi halaman
### 4. `<meta charset="UTF-8">`
Menentukan format karakter yang digunakan agar teks dapat ditampilkan dengan baik
### 5. `<title>SIMPUS-Mini | Daftar Buku</title>`
Menentukan judul yang muncul pada tab browser.
### 6. `</head>`
Menutup bagian head.
### 7. `<body>`
Membuka bagian isi halaman yang akan ditampilkan di browser.
### 8. `<header>`
Membuka bagian atas halaman.
### 9. `<h1>SIMPUS-Mini</h1>`
Menampilkan nama aplikasi sebagai judul utama.
### 10. `<nav>`
Membuka bagian menu navigasi.
### 11. `<ul>`
Membuat daftar menu.
### 12. `<li><a href="../index.html">Beranda</a></li>`
Membuat menu Beranda yang mengarah ke halaman utama.
### 13. `<li><a href="list.html">Daftar Buku</a></li>`
Membuat menu Daftar Buku yang mengarah ke halaman yang sedang dibuka.
### 14. `<li><a href="tambah.html">Tambah Buku</a></li>`
Membuat menu untuk menuju halaman tambah buku.
### 15. `<li><a href="../anggota/list.html">Daftar Anggota</a></li>`
Membuat menu untuk menuju halaman daftar anggota.
### 16. `</ul>`
Menutup daftar menu
### 17. `</nav>`
Menutup bagian navigasi
### 18. `</header>`
Menutup bagian header
### 19. `<main>`
Membuka halaman bagian utama
### 20. `<section>`
Membuka bagian yang berisi daftar buku.
### 21. `<h2>Daftar Buku</h2>`
Menampilkan judul bagian yaitu Daftar Buku.
### 22. `<table>`
Membuat tabel untuk menampilkan data buku.
### 23. `<thead>`
Membuka bagian kepala tabel
### 24. `<tr>`
Membuat satu baris pada tabel
### 25. `<th>Judul</th>`
Membuat kolom judul buku
### 26. `<th>Pengarang</th>`
Membuat kolom nama pengarang
### 27. `<th>Tahun</th>`
Membuat kolom tahun terbit buku
### 28. `<th>Stok</th>`
Membuat kolom jumlah stok buku
### 29. `<th>Aksi</th>`
Membuat kolom tombol aksi
### 30. `</tr>`
Menutup baris judul tabel
### 31. `</thead>`
Menutup bagian kepala tabel
### 32. `<tbody>`
Membuka isi bagian tabel yang berisi data buku
### 33. `<tr>`
Membuat baris untuk data buku 
### 34. `<td>Laskar Pelangi</td>`
Menampilkan judul buku Laskar Pelangi
### 35. `<td>Andrea Hirata</td>`
Menampilkan nama pengarang buku
### 36. `<td>2005</td>`
Menampilkan tahun terbit buku
### 37. `<td>4</td>`
Menampilkan jumlah stok buku sebanyak 4
### 38. `<td>`
Membuka kolom untuk tombol aksi
### 39. `<button type="button">Edit</button>`
Membuat tombol Edit untuk data buku
### 40. `<button type="button">Hapus</button>`
Membuat tombol Edit untuk data buku
### 41. `</td>`
Menutup kolom aksi
### 42. `</tr>`
Menutup baris data buku

Untuk data berikutnya, strukturnya sama. Setiap `<tr>` digunakan untuk membuat satu baris buku, sedangkan `<td>` digunakan untuk mengisi data pada setiap kolom.

## 2.2 Kesimpulan
File `buku/list.html` digunakan untuk menampilkan data buku dalam bentuk tabel. Tabel tersebut berisi judul, pengarang, tahun, stok, serta tombol Edit dan Hapus. Tombol Edit dan Hapus pada program ini masih berupa tampilan dan belum dapat digunakan untuk mengubah atau menghapus data.