## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# MODIFIKASI PADA JOBSHEET 1

## A. Pada [index.html](index.html)

1. Saya menambahkan emoticon, yang awalnya hanya `SIMPUS-MINI` menjadi `SIMPUS-MINI 📚`.

2. Saya menambahkan emoticon lagi, yang awalnya `Selamat Datang di Sistem Perpustakaan Mini` menjadi `Selamat Datang di Sistem Perpustakaan Mini 🙌`.

3. Saya menambahkan 1 section yang berisi hadits tentang membaca.

## B. Pada [buku/list.html](../SIMPUS-MINI/buku/list.html)

1. Saya hanya menambahkan emoticon pada `SIMPUS-MINI` menjadi `SIMPUS-MINI 📚`.

## C. Pada [buku/tambah.html](../SIMPUS-MINI/buku/tambah.html)

1. Saya hanya menambahkan emoticon pada `SIMPUS-MINI` menjadi `SIMPUS-MINI 📚`.

2. Saya menghapus menu `Tambah Buku` di bagian `<header>`.

3. Saya juga menghapus `<br>` pada `<label for="judul">Judul</label>` yang awalnya:

```html
<label for="judul">Judul</label><br>
```

menjadi:

```html
<label for="judul">Judul</label>
```

Saya menghapus `<br>` karena itu membuat jarak antara Judul dan kotak input terlalu jauh.

## D. Pada [anggota/list.html](../SIMPUS-MINI/anggota/list.html)

1. Saya hanya menambahkan emoticon pada `SIMPUS-MINI` menjadi `SIMPUS-MINI 📚`.

# MODIFIKASI PADA JOBSHEET 2

1. Saya mengganti tema website menjadi warna coklat.

2. Saya mengubah:

`background-color: #f5f6f8;`

menjadi:

`background-color: #ddad9c;`

pada bagian `<body>`.

3. Di bagian `header {}`, saya mengubah:

`background-color: #1d5b8a;`

menjadi:

`background-color: #5a2e25;`

4. Masih di bagian `header {}`, saya menambahkan:

```css
position: sticky;
top: 0;
z-index: 1000;
```

agar saat di-scroll ke bawah bagian `<header>` masih tetap terlihat.

5. Kemudian pada bagian `section {}`, saya mengubah:

`box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08);`

menjadi:

`box-shadow: 0 1px 3px rgba(79, 61, 53, 0.8);`

6. Pada bagian `section h2 {}`, saya mengubah:

`color: #1d5b8a;`

menjadi:

`color: #4f3d35;`

7. Saya juga menambahkan:

```css
main section:nth-of-type(2) h2 {
        grid-column: 1 / -1;
    }
```

Kode ini saya tambahkan karena sebelumnya judul "Ringkasan" ikut masuk ke dalam susunan CSS Grid. Akibatnya kartu statistik menjadi tidak sejajar. `grid-column: 1 / -1` digunakan agar judul menggunakan seluruh kolom, sehingga tiga kartu statistik dapat berada dalam satu baris.

8. Di bagian `main section:nth-of-type(2) article {}`, saya mengubah warnanya menjadi:

`background-color: #ebd7d4;`

9. Saya juga menambahkan kode:

```css
main section:nth-of-type(2) article:hover {
    background-color: #dbc4bc;
    box-shadow: 0 1px 3px rgba(79, 61, 53, 0.8);
}
```

agar ada efek hover saat cursor diarahkan ke 3 kotak ringkasan.

10. Di bagian `main section:nth-of-type(2) article h3 {}`, saya mengubah warna teks menjadi:

`color: #b46258;`

11. Di bagian `main section:nth-of-type(2) article p {}`, saya mengubah warna teks menjadi:

`color: #fca47c;`

12. Di bagian `thead`, saya mengubah background pada kepala tabel menjadi:

`background-color: #5a2e25;`

13. Di bagian `tbody tr:nth-child(even) {}`, warna isi tabel genap saya ubah menjadi:

`background-color: #f1efee;`

14. Saat mouse diarahkan ke tabel, saya mengubah warnanya menjadi:

`background-color: #f7ebe3;`

15. Pada button submit, saya mengubah warna background menjadi:

`background-color: #5a2e25;`

16. Kemudian saat cursor diarahkan ke tombol submit, saya mengganti warnanya yang awalnya biru menjadi:

`background-color: #954c1e;`

17. Terakhir, pada bagian footer saya mengubah warna teks menjadi:

`color: #b24f0d;`

# Sumber

- [W3Schools](https://www.w3schools.com/)
- [GitHub/Dimas1984/PemrogramanWeb2026](https://github.com/dimas1984/PemogramanWeb2026/tree/main)