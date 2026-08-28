## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# 3. PENJELASAN `buku/tambah.html`
File [buku/tambah.html](../../buku/tambah.html) merupakan halaman yang digunakan untuk menambahkan data buku pada website SIMPUS-Mini. Pada halaman ini terdapat form yang dapat digunakan untuk mengisi data buku seperti judul, pengarang, tahun terbit, ISBN, stok, dan kategori.

## 3.1 Fungsi Per-Baris

### 1. `<!DOCTYPE html>`
Menentukan bahwa dokumen menggunakan HTML5.
### 2. `<html lang='id'>`
Menjadi pembungkus seluruh kode HTML dan menunjukkan bahasa halaman adalah Bahasa Indonesia
### 3. `<head>`
Membuka bagian yang berisi informasi halaman
### 4. `<meta charset="UTF-8">`
Menentukan format karakter yang digunakan agar teks dapat ditampilkan dengan baik
### 5. `<title>SIMPUS-Mini | Tambah Buku</title>`
Menentukan judul yang ditampilkan pada tab browser.
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
### 11.	`<ul>`
Membuat daftar menu.
### 12.	`<li><a href="../index.html">Beranda</a></li>`
Membuat menu Beranda yang mengarah ke halaman utama.
### 13.	`<li><a href="list.html">Daftar Buku</a></li>`
Membuat menu Daftar Buku yang mengarah ke halaman daftar buku.
### 14.	`<li><a href="tambah.html">Tambah Buku</a></li>`
Membuat menu Tambah Buku yang mengarah ke halaman tambah buku.
### 15.	`<li><a href="../anggota/list.html">Daftar Anggota</a></li>`
Membuat menu Daftar Anggota yang mengarah ke halaman daftar anggota.
### 16.	`</ul>`	
Menutup daftar menu.
### 17.	`</nav>`	
Menutup bagian navigasi.
### 18.	`</header>`	
Menutup bagian header.
### 19.	`<main>`	
Membuka bagian utama halaman.
### 20.	`<section>`	
Membuka bagian yang berisi form tambah buku.
### 21.	`<h2>Tambah Buku</h2>`	
Menampilkan judul bagian yaitu Tambah Buku.
### 22.	`<form>`	
Membuka form yang digunakan untuk memasukkan data buku.
### 23.	`<p>`	
Membuka paragraf untuk mengelompokkan input judul.
### 24.	`<label for="judul">Judul</label><br>`	
Menampilkan keterangan Judul dan <br> digunakan untuk pindah ke baris berikutnya.
### 25.	`<input type="text" id="judul" name="judul" required>`	
Membuat tempat untuk memasukkan judul buku dalam bentuk teks. required membuat input wajib diisi.
### 26.	`</p>`	
Menutup paragraf input judul.
### 27.	`<p>`	
Membuka paragraf untuk input pengarang.
### 28.	`<label for="pengarang">Pengarang</label>`	
Menampilkan keterangan untuk input nama pengarang.
### 29.	`<input type="text" id="pengarang" name="pengarang" required>`	
Membuat tempat untuk memasukkan nama pengarang dan wajib diisi.
### 30.	`</p>`	
Menutup paragraf input pengarang.
### 31.	`<p>`	
Membuka paragraf untuk input tahun terbit.
### 32.	`<label for="tahun">Tahun Terbit</label>`	
Menampilkan keterangan untuk input tahun terbit.
### 33.	`<input type="number" id="tahun" name="tahun" min="1900" max="2026" required>`	
Membuat input angka untuk tahun terbit. Nilai yang diperbolehkan dari 1900 sampai 2026 dan wajib diisi.
### 34.	`</p>`	
Menutup paragraf input tahun.
### 35.	`<p>`	
Membuka paragraf untuk input ISBN.
### 36.	`<label for="isbn">ISBN</label>`	
Menampilkan keterangan untuk input ISBN.
### 37.	`<input type="text" id="isbn" name="isbn">`	
Membuat tempat untuk memasukkan ISBN dalam bentuk teks.
### 38.	`</p>`	
Menutup paragraf input ISBN.
### 39.	`<p>`	
Membuka paragraf untuk input stok.
### 40.	`<label for="stok">Stok</label>`	
Menampilkan keterangan untuk input jumlah stok.
### 41.	`<input type="number" id="stok" name="stok" min="0" required>`	
Membuat input angka untuk jumlah stok. Nilai paling kecil adalah 0 dan wajib diisi.
### 42.	`</p>`	
Menutup paragraf input stok.
### 43.	`<p>`	
Membuka paragraf untuk pilihan kategori.
### 44.	`<label for="kategori">Kategori</label>`	
Menampilkan keterangan untuk pilihan kategori buku.
### 45.	`<select id="kategori" name="kategori">`	
Membuat menu pilihan untuk kategori buku.
### 46.	`<option value="fiksi">Fiksi</option>`	
Membuat pilihan kategori Fiksi.
### 47.	`<option value="non-fiksi">Non-Fiksi</option>`	
Membuat pilihan kategori Non-Fiksi.
### 48.	`<option value="referensi">Referensi</option>`	
Membuat pilihan kategori Referensi.
### 49.	`</select>`	
Menutup menu pilihan kategori.
### 50.	`</p>`	
Menutup paragraf kategori.
### 51.	`<p>`	
Membuka paragraf untuk tombol simpan.
### 52.	`<button type="submit">Simpan</button>`	
Membuat tombol Simpan untuk mengirim data dari form.
### 53.	`</p>`	
Menutup paragraf tombol.
### 54.	`</form>`	
Menutup form.
### 55.	`</section>`	
Menutup bagian form tambah buku.
### 56.	`</main>`	
Menutup bagian utama halaman.
### 57.	`<footer>`	
Membuka bagian paling bawah halaman.
### 58.	`<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p>`	
Menampilkan copyright, tahun, nama aplikasi, dan keterangan Jobsheet 1.
### 59.	`</footer>`	
Menutup bagian footer.
### 60.	`</body>`	
Menutup bagian isi halaman.
### 61.	`</html>`	
Menutup seluruh dokumen HTML.

## 3.2 KESIMPULAN
File `buku/tambah.html` digunakan untuk membuat halaman form penambahan data buku. Form tersebut memiliki input untuk judul, pengarang, tahun terbit, ISBN, stok, dan kategori. Pada halaman ini juga terdapat tombol Simpan, tetapi tombol tersebut belum terhubung dengan database sehingga data belum dapat disimpan secara permanen.