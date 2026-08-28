## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# PENJELASAN anggota/tambah.html
File [anggota/tambah.html](../../anggota/tambah.html) merupakan halaman yang digunakan untuk menambahkan data anggota pada website SIMPUS-Mini. Pada halaman ini terdapat form untuk memasukkan nama, nomor anggota, alamat, dan nomor HP.

## 2.2 Fungsi Setiap Baris

### 1. `<!DOCTYPE html>` 
Menentukan bahwa dokumen menggunakan HTML5.
### 2. `<html lang="id">` 
Membuka dokumen HTML dan menentukan bahasa yang digunakan adalah Bahasa Indonesia.
### 3. `<head>` 
Membuka bagian head yang berisi informasi halaman.
### 4. `<meta charset="UTF-8">`
Mengatur karakter agar tulisan dapat ditampilkan dengan baik. 
### 5. `<title>SIMPUS-Mini | Tambah Anggota</title>` 
Menentukan judul yang muncul pada tab browser. 
### 6. `</head>`  
Menutup bagian head. 
### 7. `<body>` 
Membuka bagian isi halaman yang ditampilkan pada browser. 
### 8. `<header>`
Membuka bagian atas halaman. 
### 9. `<h1>SIMPUS-Mini</h1>` 
Menampilkan nama aplikasi sebagai judul utama. 
### 10.  `<nav>` 
Membuka bagian menu navigasi. 
### 11.  `<ul>` 
Membuat daftar menu. 
### 12.  `<li><a href="../index.html">Beranda</a></li>`
Membuat menu Beranda yang mengarah ke halaman utama. 
### 13.  `<li><a href="../buku/list.html">Daftar Buku</a></li>`
Membuat menu Daftar Buku yang mengarah ke halaman daftar buku. 
### 14.  `<li><a href="list.html">Daftar Anggota</a></li>`
Membuat menu Daftar Anggota yang mengarah ke halaman daftar anggota. 
### 15.  `<li><a href="tambah.html">Tambah Anggota</a></li>` 
Membuat menu Tambah Anggota yang mengarah ke halaman tambah anggota. 
### 16.  `</ul>`
Menutup daftar menu. 
### 17.  `</nav>` 
Menutup bagian navigasi. 
### 18.  `</header>` 
Menutup bagian header. 
### 19.  `<main>` 
Membuka bagian utama halaman. 
### 20.  `<section>`
Membuka bagian yang berisi form tambah anggota. 
### 21.  `<h2>Tambah Anggota</h2>` 
Menampilkan judul bagian yaitu Tambah Anggota. 
### 22.  `<form>` 
Membuka form yang digunakan untuk memasukkan data anggota. 
### 23.  `<p>` 
Membuka paragraf untuk mengelompokkan input nama. 
### 24.  `<label for="nama">Nama</label>` 
Menampilkan keterangan untuk kolom nama. 
### 25.  `<input type="text" id="nama" name="nama" required>` 
Membuat tempat untuk memasukkan nama anggota dalam bentuk teks. `required` membuat kolom wajib diisi. 
### 26.  `</p>` 
Menutup bagian input nama. 
### 27.  `<p>` 
Membuka paragraf untuk input nomor anggota. 
### 28.  `<label for="no_anggota">No. Anggota</label><br>` 
Menampilkan keterangan nomor anggota. `<br>` digunakan untuk membuat baris baru. 
### 29.  `<input type="text" id="no_anggota" name="no_anggota" required>` 
Membuat tempat untuk memasukkan nomor anggota dan wajib diisi. 
### 30.  `</p>` 
Menutup bagian input nomor anggota. 
### 31.  `<p>` 
Membuka paragraf untuk input alamat.
### 32.  `<label for="alamat">Alamat</label>` 
Menampilkan keterangan untuk kolom alamat. 
### 33.  `<input type="text" id="alamat" name="alamat">` 
Membuat tempat untuk memasukkan alamat anggota. 
### 34.  `</p>` 
Menutup bagian input alamat. 
### 35.  `<p>` 
Membuka paragraf untuk input nomor HP. 
### 36.  `<label for="no_hp">No. HP</label>` 
Menampilkan keterangan untuk kolom nomor HP. 
### 37.  `<input type="text" id="no_hp" name="no_hp">` 
Membuat tempat untuk memasukkan nomor HP anggota dalam bentuk teks. 
### 38.  `</p>` 
Menutup bagian input nomor HP. 
### 39.  `<p>` 
Membuka paragraf untuk tombol simpan. 
### 40.  `<button type="submit">Simpan</button>` 
Membuat tombol Simpan untuk mengirim data dari form. 
### 41.  `</p>` 
Menutup bagian tombol. 
### 42.  `</form>` 
Menutup form. 
### 43.  `</section>` 
Menutup bagian form tambah anggota. 
### 44.  `</main>` 
Menutup bagian utama halaman. 
### 45.  `<footer>` 
Membuka bagian paling bawah halaman. 
### 46.  `<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p>` 
Menampilkan copyright, tahun, nama aplikasi, dan keterangan Jobsheet 1. 
### 47.  `</footer>` 
Menutup bagian footer. 
### 48.  `</body>` 
Menutup bagian isi halaman. 
### 49.  `</html>` 
Menutup seluruh dokumen HTML. 

## 2.3 KESIMPULAN
File `anggota/tambah.html` digunakan untuk membuat halaman form penambahan data anggota. Form tersebut memiliki input untuk nama, nomor anggota, alamat, dan nomor HP. Terdapat juga tombol Simpan untuk mengirim data, tetapi pada program ini belum terhubung dengan database sehingga data belum dapat disimpan secara permanen.