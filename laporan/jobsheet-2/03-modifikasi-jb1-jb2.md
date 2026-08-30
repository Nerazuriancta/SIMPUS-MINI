## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# MODIFIKASI PADA JOBSHEET 1
## A. Pada [index.html](index.html)
1. saya menambahkan emoticon, yang awalnya hanya SIMPUS-MINI menjadi SIMPUS-MINI 📚
2. saya menambahkan emoticon lagi, yang awalnya Selamat Datang di Sistem Perpustakaan Mini menjadi Selamat Datang di Sistem Perpustakaan Mini 🙌
3. saya menambahkan 1 section berisi hadits tentang membaca

## B. Pada [buku/list.html](../SIMPUS-MINI/buku/list.html)
1. saya hanya menambahkan emoticon pada SIMPUS-MINI menjadi SIMPUS-MINI 📚

## C. Pada [buku/tambah.html](../SIMPUS-MINI/buku/tambah.html)
1. saya hanya menambahkan emoticon pada SIMPUS-MINI menjadi SIMPUS-MINI 📚
2. saya menghapus menu Tambah Buku di `<header>`
3. saya juga menghapus `<br>` pada `<label for="judul">Judul</label>`yang awalnya `<label for="judul">Judul</label><br>`, karena itu membuat jarak antara Judul dan kotak inputnya

## D. Pada [anggota/list.html](../SIMPUS-MINI/anggota/list.html)
1. saya hanya menambahkan emoticon pada SIMPUS-MINI menjadi SIMPUS-MINI 📚

# MODIFIKASI PADA JOBSHEET 2
1. saya mengganti tema menjadi coklat
2. saya mengubah `background-color: #f5f6f8;` menjadi `background-color: #ddad9c;` pada bagian `<body>`
3. di bagian `header{}` saya mengubah `background-color: #1d5b8a;` menjadi `background-color: #5a2e25;`
4. masih di bagian `header{}`, saya menambahkan 
```css
position: sticky;
top: 0;
z-index: 1000;
```
agar saat di scroll ke bawah bagian `<header>` masih kelihatan.
5. kemudian pada bagian `<section{}` saya mengubah `box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08);` menjadi `box-shadow: 0 1px 3px rgba(79, 61, 53, 0.8);`
6. pada bagian `section h2{}` saya mengubah `color: #1d5b8a;` menjadi `color: #4f3d35;`
7. saya juga menambahkan 
```css
main section:nth-of-type(2) h2 {
    grid-column: 1 / -1;
}
```
Kode ini saya tambahkan karena sebelumnya judul "Ringkasan" ikut masuk ke dalam susunan CSS Grid. Akibatnya kartu statistik menjadi tidak sejajar. `grid-column: 1 / -1` digunakan agar judul menggunakan seluruh kolom, sehingga tiga kartu statistik dapat berada dalam satu baris.
8. di bagian `main section:nth-of-type(2) article {}`, saya mengubah warnanya menjadi
`background-color: #ebd7d4;`
9. saya juga menambahkan kode
```css
main section:nth-of-type(2) article:hover {
    background-color: #dbc4bc;
    box-shadow: 0 1px 3px rgba(79, 61, 53, 0.8);
}
```
agar ada hovernya saat cursor di 3 kotak ringkasan
10. di bagian `main section:nth-of-type(2) article h3 {}`, saya mengubah warna text menjadi `color: #b46258;`
11. di bagian `main section:nth-of-type(2) article p {}` saya ubah lagi warnya textnya menjadi `color: #fca47c;`
12. di bagian thead saya mengubah background pada kepala tabel nya menjadi warna `background-color: #5a2e25;`
13. di bagian `tbody tr:nth-child(even) {}` warna isi tabel genap saya ubah menjadi `background-color: #f1efee;`
14. saat mouse di tabel juga saya ubah warnanya menjadi `background-color: #f7ebe3;`
pada button submit saya ubah juga warna backgroundnya menjadi `background-color: #5a2e25;`
kemudian saat cursor diarahkan ke tombol submit saya juga ganti warnanya yang awalnya biru menjadi `background-color: #954c1e;`
kemudian yang terakhir pada footer saya mengubah warna text nya menjadi `color: #b24f0d;`

Sumber: 
- [W3Schools](https://www.w3schools.com/)
- [Github/Dimas1984/PemrogramanWeb2026](https://github.com/dimas1984/PemogramanWeb2026/tree/main)

kok readme saya ga rapi ya gimana