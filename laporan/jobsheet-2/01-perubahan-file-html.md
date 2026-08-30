## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# PERUBAHAN FILE HTML

Setelah membuat file CSS [style.css](../../assets/css/style.css), saya menambahkan kode untuk menghubungkan CSS tersebut ke beberapa file HTML agar tampilan website menjadi lebih rapi.

## 1. Perubahan pada `index.html`

Pada bagian `<head>` file `index.html`, ditambahkan:

```html
<link rel="stylesheet" href="assets/css/style.css">
```

## 2. Perubahan pada `buku/list.html` dan `buku/tambah.html`

Pada bagian `<head>` saya tambahkan kode:

```html
<link rel="stylesheet" href="../assets/css/style.css">
```
Penggunaan `../` digunakan karena kedua file berada di dalam folder buku, sehingga perlu naik 1 tingkat terlebih dahulu sebelum menuju folder `assets/css`.

## 3. Perubahan pada `anggota/list.html` dan `anggota/tambah.html`

Pada bagian `<head>` saya tambahkan kode:
```html
<link rel="stylesheet" href="../assets/css/style.css">
```
Sama seperti folder `buku`, penggunaan `../` diperlukan karena file HTML berada di dalam folder anggota.

## 4. Hasil Perubahan
Setelah File HTML dihubungkan dengan [style.css](../../assets/css/style.css), tampilan website mengakami perubahan. Beberapa bagian yang mendapatkan pengaturan CSS yaitu:
- Header dan menu navigasi
- Tampilan halaman utama
- Kartu statistik pada halaman beranda
- Tabel daftar buku dan anggota
- Tombol Edit dan Hapus
- Form tambah buku dan anggota
- Footer

Dengan perubahan tersebut, semua halaman pada website SIMPUS-Mini memiliki tampilan yang lebih rapi dan menggunakan style yang sama.

## 5. Kesimpulan
Penambahan kode `<link rel="stylesheet">` pada file HTML digunakan untuk menghubungkan halaman HTML dengan file style.css. Karena letak file HTML berbeda, penulisan lokasi CSS juga disesuaikan. Setelah CSS berhasil dihubungkan, tampilan setiap halaman dapat mengikuti aturan yang sudah dibuat pada file style.css.