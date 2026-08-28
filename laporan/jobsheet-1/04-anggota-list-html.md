## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# 2. PENJELASAN `anggota/list.html`
File [list.html](../anggota/list.html) merupakan halaman yang digunakan untuk menampilkan daftar anggota pada website SIMPUS-Mini. Pada halaman ini terdapat tabel yang berisi nomor anggota, nama, alamat, nomor HP, serta tombol aksi berupa Edit dan Hapus.

## 2.1 Kode Program
### 1. `<!DOCTYPE html>`
Menentukan bahwa dokumen menggunakan HTML5.
### 2. `<html lang="id">`	
Membuka dokumen HTML dan menentukan bahasa halaman adalah Bahasa Indonesia.
### 3. `<head>`	
Membuka bagian head yang berisi informasi halaman.
### 4. `<meta charset="UTF-8">`	
Mengatur karakter yang digunakan agar tulisan dapat ditampilkan dengan baik.
### 5. `<title>SIMPUS-Mini | Daftar Anggota</title>`	
Menentukan judul yang muncul pada tab browser.
### 6. `</head>`	
Menutup bagian head.
### 7. `<body>`	
Membuka bagian isi halaman yang ditampilkan pada browser.
### 8. `<header>`	
Membuka bagian atas halaman.
### 9. `<h1>SIMPUS-Mini</h1>`	
Menampilkan nama aplikasi sebagai judul utama.
### 10.	`<nav>`	
Membuka bagian menu navigasi.
### 11.	`<ul>`	
Membuat daftar menu.
### 12.	`<li><a href="../index.html">Beranda</a></li>`	
Membuat menu Beranda yang mengarah ke halaman utama.
### 13.	`<li><a href="../buku/list.html">Daftar Buku</a></li>`	
Membuat menu Daftar Buku yang mengarah ke halaman daftar buku.
### 14.	`<li><a href="list.html">Daftar Anggota</a></li>`	
Membuat menu Daftar Anggota yang mengarah ke halaman yang sedang dibuka.
### 15.	`<li><a href="tambah.html">Tambah Anggota</a></li>`
Membuat menu Tambah Anggota yang mengarah ke halaman tambah anggota.
### 16.	`</ul>`	
Menutup daftar menu.
### 17.	`</nav>`	
Menutup bagian navigasi.
### 18.	`</header>`	
Menutup bagian header.
### 19.	`<main>`	
Membuka bagian utama halaman.
### 20.	`<section>`	
Membuka bagian yang berisi daftar anggota.
### 21.	`<h2>Daftar Anggota</h2>`	
Menampilkan judul bagian yaitu Daftar Anggota.
### 22.	`<table>`	
Membuat tabel untuk menampilkan data anggota.
### 23.	`<thead>`	
Membuka bagian kepala tabel.
### 24.	`<tr>`	
Membuat baris pada tabel.
### 25.	`<th>No. Anggota</th>`	
Membuat kolom nomor anggota.
### 26.	`<th>Nama</th>`	
Membuat kolom nama anggota.
### 27.	`<th>Alamat</th>`	
Membuat kolom alamat anggota.
### 28.	`<th>No. HP</th>`	
Membuat kolom nomor HP anggota.
### 29.	`<th>Aksi</th>`	
Membuat kolom untuk tombol aksi.
### 30.	`</tr>`	
Menutup baris judul tabel.
### 31.	`</thead>`	
Menutup bagian kepala tabel.
### 32.	`<tbody>`	
Membuka bagian isi tabel yang berisi data anggota.
### Struktur kode tersebut digunakan kembali untuk menampilkan data anggota lainnya, yaitu A002 sampai A008 dengan data yang berbeda.

## 2.2 Kesimpulan
File `anggota/list.html` digunakan untuk menampilkan data anggota dalam bentuk tabel. Tabel tersebut berisi nomor anggota, nama, alamat, nomor HP, serta tombol Edit dan Hapus. Tombol Edit dan Hapus pada program ini masih berupa tampilan dan belum dapat digunakan untuk mengubah atau menghapus data.