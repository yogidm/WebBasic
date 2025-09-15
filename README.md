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


# Materi HTML Lanjutan

## 1. Pendahuluan
Setelah memahami dasar HTML, tahap berikutnya adalah mempelajari elemen lanjutan yang sering digunakan dalam pembuatan website modern.  
Materi ini akan mencakup **elemen teks, tombol, formulir, multimedia, layout, background, dan interaktivitas** menggunakan CSS serta JavaScript sederhana.  

---

## 2. Elemen Teks Lanjutan
Selain `<p>` dan `<h1>` sampai `<h6>`, HTML memiliki beberapa elemen untuk memformat teks:

```html
<p><b>Teks Tebal</b></p>
<p><strong>Teks Penting</strong></p>
<p><i>Teks Miring</i></p>
<p><em>Teks Ditekankan</em></p>
<p><u>Teks Bergaris Bawah</u></p>
<p><mark>Teks dengan Highlight</mark></p>
<p><small>Teks Kecil</small></p>
<p><del>Teks Dicoret</del></p>
<p><ins>Teks Disisipkan</ins></p>
<marquee>Contoh teks berjalan</marquee>
```

---

## 3. Tombol (Button)
Tombol digunakan untuk interaksi pengguna.  
Jenis tombol:
- Tombol biasa: `<button>`
- Tombol kirim form: `<input type="submit">`
- Tombol reset: `<input type="reset">`

```html
<button>Klik Saya</button>
<input type="submit" value="Kirim">
<input type="reset" value="Reset">
```

### Mengubah Warna Tombol (CSS)
```html
<button style="background-color: blue; color: white; padding: 10px;">Tombol Biru</button>
<button style="background-color: green; color: white; padding: 10px;">Tombol Hijau</button>
```

---

## 4. Formulir (Form)
Digunakan untuk mengambil input dari pengguna.

```html
<form>
    Nama: <input type="text" name="nama"><br><br>
    Password: <input type="password" name="pass"><br><br>
    Jenis Kelamin:
    <input type="radio" name="gender" value="L"> Laki-laki
    <input type="radio" name="gender" value="P"> Perempuan <br><br>
    Hobi:
    <input type="checkbox" name="hobi" value="Membaca"> Membaca
    <input type="checkbox" name="hobi" value="Olahraga"> Olahraga <br><br>
    <input type="submit" value="Kirim">
</form>
```

---

## 5. Multimedia (Gambar, Audio, Video)
HTML mendukung elemen multimedia:

```html
<img src="https://raw.githubusercontent.com/yogidm/Binarization/refs/heads/master/Python/CitraRGB.png" alt="Contoh Gambar">

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Browser Anda tidak mendukung audio.
</audio>

<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Browser Anda tidak mendukung video.
</video>
```

Tambahkan file audio/video sesuai dengan filename di folder path yang sama dengan kode diatas. atau Anda juga bisa menambahkan subfolder seperti kode berikut.

```html
<video controls width="400">
  <source src="assets/video/film.mp4" type="video/mp4">
</video>
```

---

## 6. Elemen Layout (Div, Span)
- `<div>` digunakan untuk mengelompokkan elemen dalam blok.  
- `<span>` digunakan untuk mengelompokkan teks secara inline.

```html
<div style="background-color: lightgray; padding: 10px;">
    <h2>Ini dalam DIV</h2>
    <p>Teks dalam div</p>
</div>

<p>Ini teks <span style="color: red;">dengan warna merah</span>.</p>
```

---

## 7. Mengubah Background
Menggunakan CSS untuk mengganti warna atau gambar latar belakang.

```html
<body style="background-color: lightblue;">
    <h1>Latar Belakang Biru Muda</h1>
</body>

<body style="background-image: url('https://raw.githubusercontent.com/yogidm/Binarization/refs/heads/master/Python/SutetCat.jpg'); background-size: cover;">
    <h1>Latar Belakang Gambar</h1>
</body>
```

---

## 8. Web Reaktif dengan JavaScript
JavaScript memungkinkan halaman menjadi interaktif.

### Mengubah Warna Tombol Saat Diklik
```html
<button id="btn">Klik Saya</button>

<script>
    document.getElementById("btn").onclick = function() {
        this.style.backgroundColor = "red";
        this.style.color = "white";
        this.textContent = "Warna Berubah!";
    }
</script>
```

### Mengubah Background Halaman
```html
<button onclick="document.body.style.backgroundColor='lightyellow'">
    Ubah Background
</button>
```

---

## 9. Contoh Halaman Lengkap
```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Lanjutan</title>
    <style>
        body {
            background-color: #f9f9f9;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        button {
            padding: 10px 20px;
            margin: 5px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        .blue-btn { background-color: blue; color: white; }
        .green-btn { background-color: green; color: white; }
    </style>
</head>
<body>
    <h1><marquee>Materi HTML Lanjutan</marquee></h1>

    <p><b>Tebal</b>, <i>Miring</i>, <u>Bergaris Bawah</u>, <mark>Highlight</mark></p>

    <button class="blue-btn" id="btnChange">Ubah Background</button>
    <button class="green-btn">Tombol Hijau</button>

    <form>
        <h2>Formulir</h2>
        Nama: <input type="text"><br><br>
        <input type="submit" value="Kirim">
    </form>

    <h2>Multimedia</h2>
    <img src="https://raw.githubusercontent.com/yogidm/Binarization/refs/heads/master/Python/SutetCat.jpg" alt="Contoh Gambar"><br><br>

    <script>
        document.getElementById("btnChange").onclick = function() {
            document.body.style.backgroundColor = "lightblue";
        }
    </script>
</body>
</html>
```

---


> **Tugas Latihan:**  
> Buat halaman `html_lanjutan.html` yang berisi:  
> - Minimal 2 tombol dengan gaya berbeda  
> - Efek teks (bold, italic, underline, mark, del)  
> - Formulir sederhana (input text, password, checkbox, submit)  
> - Multimedia (gambar + video)  
> - JavaScript sederhana untuk mengubah background dan teks tombol (bisa menggunakan format warna Hexa) seperti:

- `#FF0000` = Merah penuh  
- `#00FF00` = Hijau penuh  
- `#0000FF` = Biru penuh  
- `#000000` = Hitam  
- `#FFFFFF` = Putih  
- `#808080` = Abu-abu  
- `#FFFF00` = Kuning  
- `#FFA500` = Oranye  
- `#800080` = Ungu  
- `#00FFFF` = Cyan / Aqua  
- `#FFC0CB` = Pink  
- `#A52A2A` = Cokelat  
- `#008000` = Hijau tua  
- `#ADD8E6` = Biru muda (*Sky Blue*)  
- `#32CD32` = Lime hijau terang  
- `#FFD700` = Emas (*Gold*)  
- `#C0C0C0` = Perak (*Silver*)  
- `#F5F5DC` = Beige  
- `#FA8072` = Salmon  
- `#2F4F4F` = Abu tua (*Dark Slate Gray*)


---
