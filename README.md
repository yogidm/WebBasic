# Materi HTML Dasar

## 1. Apa itu HTML?
HTML (*HyperText Markup Language*) adalah bahasa standar untuk menyusun struktur halaman web.  
HTML menggunakan *tag* (ditulis dengan tanda kurung sudut `< >`) untuk menentukan jenis konten seperti teks, gambar, tautan, tabel, dan lainnya.  

---

## 2. Struktur Penulisan HTML
Setiap halaman web berbasis HTML memiliki struktur dasar berikut:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Judul Halaman</title>
</head>
<body>
    <h1>Ini Judul Utama</h1>
    <p>Ini adalah sebuah paragraf.</p>
</body>
</html>
```

**Penjelasan:**
- `<!DOCTYPE html>` : Menandakan bahwa dokumen menggunakan HTML5.  
- `<html>` : Elemen root yang membungkus seluruh isi halaman.  
- `<head>` : Berisi metadata (judul, style, script, dsb).  
- `<title>` : Judul halaman yang tampil di tab browser.  
- `<body>` : Berisi konten yang akan terlihat oleh pengguna di halaman web.  

---

## 3. Elemen Dasar HTML
Berikut beberapa elemen HTML yang umum digunakan beserta contohnya:

### a. Heading
Digunakan untuk membuat judul dengan ukuran berbeda (`<h1>` sampai `<h6>`).  
```html
<h1>Judul Utama</h1>
<h2>Sub Judul</h2>
<h3>Judul Tingkat 3</h3>
```

### b. Paragraf
Untuk menuliskan teks dalam bentuk paragraf.  
```html
<p>Ini adalah sebuah paragraf dalam HTML.</p>
```

### c. Tautan (Link)
Untuk membuat hyperlink ke halaman lain atau situs web.  
```html
<a href="https://github.com/yogidm">Kunjungi Website</a>
```

### d. Gambar
Untuk menampilkan gambar pada halaman.  
```html
<img src="https://raw.githubusercontent.com/yogidm/Binarization/refs/heads/master/Python/SutetCat.jpg" alt="Contoh Gambar">
```

### e. Daftar (List)
- **Unordered List** (bullet):  
```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

- **Ordered List** (berurutan):  
```html
<ol>
    <li>Pemrograman Web</li>
    <li>Database</li>
    <li>Jaringan</li>
</ol>
```

### f. Tabel
Untuk menampilkan data dalam bentuk tabel.  
```html
<table border="1">
    <tr>
        <th>Nama</th>
        <th>NIM</th>
    </tr>
    <tr>
        <td>Ani</td>
        <td>12345</td>
    </tr>
    <tr>
        <td>Budi</td>
        <td>67890</td>
    </tr>
</table>
```

### g. Garis Horizontal & Pindah Baris
```html
<p>Teks pertama</p>
<hr>
<p>Teks kedua setelah garis</p>
<br>
<p>Teks setelah pindah baris</p>
```

---

## 4. Contoh Halaman Lengkap
Berikut contoh penggabungan semua elemen dasar dalam satu halaman HTML:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Halaman Belajar HTML</title>
</head>
<body>
    <h1>Selamat Datang di Pemrograman Web</h1>
    <p>Ini adalah halaman web pertama saya menggunakan HTML.</p>
    
    <h2>Contoh Tautan</h2>
    <a href="https://github.com/yogidm">Kunjungi Situs Contoh</a>
    
    <h2>Contoh Gambar</h2>
    <img src="https://raw.githubusercontent.com/yogidm/Binarization/refs/heads/master/Python/SutetCat.jpg" alt="Gambar Contoh">

    <h2>Contoh Daftar</h2>
    <ul>
        <li>Belajar Struktur HTML</li>
        <li>Mengenal Tag Dasar</li>
        <li>Praktik Menulis Kode</li>
    </ul>

    <h2>Contoh Tabel</h2>
    <table border="1">
        <tr>
            <th>Mata Kuliah</th>
            <th>SKS</th>
        </tr>
        <tr>
            <td>Pemrograman Web</td>
            <td>3</td>
        </tr>
        <tr>
            <td>Basis Data</td>
            <td>2</td>
        </tr>
    </table>
</body>
</html>
```

---


> **Tugas Latihan 1 :**  
> Buat halaman HTML dengan nama `latihan.html` yang berisi:  
> - Judul halaman  
> - Heading nama dan NIM  
> - Paragraf tentang diri Anda  
> - Tautan menuju situs favorit atau blog Anda
> - Satu gambar bebas dari internet atau foto Anda 
> - Satu tabel berisi minimal 2 baris data nama hewan yang dianggap langka/hampir punah.

---

