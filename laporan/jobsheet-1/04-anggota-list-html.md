## Nama  : Nerazuriancta Purnama Syah Putri
## NIM   : 254107020117
## Kelas : TI-2D

# 2. PENJELASAN `anggota/list.html`

File [list.html](../anggota/list.html) merupakan halaman yang digunakan untuk menampilkan daftar anggota pada website SIMPUS-Mini. Pada halaman ini terdapat tabel yang berisi nomor anggota, nama, alamat, nomor HP, serta tombol aksi berupa Edit dan Hapus.

## 2.1 Kode Program
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>SIMPUS-Mini | Daftar Anggota</title>
</head>
<body>
    <header>
        <h1>SIMPUS-Mini</h1>
        <nav>
            <ul>
                <li><a href="../index.html">Beranda</a></li>
                <li><a href="../buku/list.html">Daftar Buku</a></li>
                <li><a href="list.html">Daftar Anggota</a></li>
                <li><a href="tambah.html">Tambah Anggota</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Daftar Anggota</h2>
            <table>
                <thead>
                    <tr>
                        <th>No. Anggota</th>
                        <th>Nama</th>
                        <th>Alamat</th>
                        <th>No. HP</th>
                        <th>Aksi</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>A001</td>
                        <td>Siti Aminah</td>
                        <td>Malang</td>
                        <td>08123456789</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                    <tr>
                        <td>A002</td>
                        <td>Budi Santoso</td>
                        <td>Batu</td>
                        <td>08678898739</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                    <tr>
                        <td>A003</td>
                        <td>Nerazuriancta</td>
                        <td>Probolinggo</td>
                        <td>087981783657</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                    <tr>
                        <td>A004</td>
                        <td>Sarah Geiza</td>
                        <td>Probolinggo</td>
                        <td>0819308291</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                    <tr>
                        <td>A005</td>
                        <td>Findi Findoy</td>
                        <td>Malang</td>
                        <td>0867317397</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                    <tr>
                        <td>A006</td>
                        <td>Firstyara Hilma</td>
                        <td>Batam</td>
                        <td>0891839738</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                    <tr>
                        <td>A007</td>
                        <td>Ayunda</td>
                        <td>Probolinggo</td>
                        <td>0875671928</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                    <tr>
                        <td>A008</td>
                        <td>Ahmad Rizky</td>
                        <td>Malang</td>
                        <td>081234567625</td>
                        <td>
                            <button type="button">Edit</button>
                            <button type="button">Hapus</button>
                        </td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>
</body>
</html>
```

## 2.2 Penjelasan Program

### Bagian `<head>`
```html
<head>
    <meta charset="UTF-8">
    <title>SIMPUS-Mini | Daftar Anggota</title>
</head>
```
- Bagian `<head>` digunakan untuk memberikan informasi pada halaman `<metacharset="UTF-8">` digunakan agar karakter dapat terbaca dengan baik.
- Bagian `<title>` digunaan untuk memberikan judul yang munculpada tab browser.

### Bagian `<header>` - Kepala Halaman
```html
<header>
        <h1>SIMPUS-Mini</h1>
        <nav>
            ....
        </nav>
    </header>
```