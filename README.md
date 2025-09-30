# Instruksi Penggunaan

## 1. Buka Notepad atau Notepad++
- **Notepad (bawaan Windows):** cukup cari di *Start Menu*.  
- **Notepad++ (jika terinstal):** gunakan ini karena lebih nyaman, mendukung pewarnaan sintaks.  Dapat didownload di: `https://notepad-plus-plus.org/downloads/` 


## 2. Tulis Kode HTML dari Tutorial
- Ketik ulang atau salin kode HTML dari materi tutorial.  
- Misalnya: struktur dasar HTML, elemen teks, button, CSS, atau JavaScript sederhana.  


## 3. Simpan File dengan Ekstensi `.html`
- Klik **File → Save As...**  
- Pilih folder kerja, misalnya `D:\BelajarHTML`  
- Pada **Save as type**, pilih **All Files**  
- Beri nama file, misalnya `index.html` (bukan `index.html.txt`).  


## 4. Buka File dengan Browser
- Cari file `index.html` di folder kerja.  
- Klik kanan → **Open With** → pilih **Google Chrome** (atau Edge/Firefox).  
- Setiap kali Anda mengubah kode:  
  - Simpan kembali file (**Ctrl+S**)  
  - **Refresh browser** `Tekan F5` untuk melihat hasil perubahan.

 
---


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


> **Tugas Latihan 2:**  
> Buat halaman `html_lanjutan.html` yang berisi:  
> - Minimal 2 tombol dengan gaya berbeda  
> - Efek teks (bold, italic, underline, mark, del)  dengan konten mengenai perlunya perlindungan bawah air raja ampat.
> - Formulir sederhana dengan fitur (input text nama-NIM, checkbox gender, tombol submit)  
> - Multimedia (gambar + video)  pendukung artikel
> - JavaScript sederhana untuk mengubah background dan teks tombol (bisa menggunakan format warna Hexa) seperti:
> 
> | Preview | Hex Code | Nama / Keterangan        |
> |---------|----------|--------------------------|
> | 🟥 | `#FF0000` | Merah penuh             |
> | 🟩 | `#00FF00` | Hijau penuh             |
> | 🟦 | `#0000FF` | Biru penuh              |
> | ⬛ | `#000000` | Hitam                   |
> | ⬜ | `#FFFFFF` | Putih                   |
> | ◼️ | `#808080` | Abu-abu                 |
> | 🟨 | `#FFFF00` | Kuning                  |
> | 🟧 | `#FFA500` | Oranye                  |
> | 🟪 | `#800080` | Ungu                    |
> | 🟦 | `#00FFFF` | Cyan / Aqua             |
> | 🌸 | `#FFC0CB` | Pink                    |
> | 🟫 | `#A52A2A` | Cokelat                 |
> | 🟩 | `#008000` | Hijau tua               |
> | 🌐 | `#ADD8E6` | Biru muda (*Sky Blue*)  |
> | 💚 | `#32CD32` | Lime hijau terang       |
> | ⭐ | `#FFD700` | Emas (*Gold*)           |
> | ⚪ | `#C0C0C0` | Perak (*Silver*)        |
> | 🤍 | `#F5F5DC` | Beige                   |
> | 🍣 | `#FA8072` | Salmon                  |
> | 🌑 | `#2F4F4F` | Abu tua (*Dark Slate Gray*) |


---


Selamat mengerjakan :)

------------------------------------------------------------------------

# Panduan Dasar PHP

------------------------------------------------------------------------

## Pengenalan PHP

**Apa itu PHP?**\
PHP merupakan bahasa pemrograman server-side yang digunakan secara luas untuk membangun aplikasi web dinamis. Bahasa ini populer karena mudah dipelajari, didukung oleh hampir semua layanan hosting, serta memiliki integrasi yang baik dengan sistem basis data seperti MySQL. Untuk memulai, cukup menuliskan perintah sederhana seperti `echo "Hello World!";` yang akan menampilkan teks ke layar. Dengan contoh singkat ini, pembaca dapat merasakan bagaimana PHP bekerja secara langsung.


**Hello World sederhana**

``` php
<?php
echo "Hello World!";
?>
```

**Petunjuk penggunaan:**  
Simpan kode di atas dengan nama `hello.php`, lalu jalankan melalui browser dengan mengakses `http://localhost/hello.php` setelah menyalakan server lokal (misalnya XAMPP).

![Start XAMPP](https://github.com/yogidm/WebBasic/blob/main/images/XAMPP.jpg)

![Direktori htdoc](https://github.com/yogidm/WebBasic/blob/main/images/lokasi_htdocs.jpg)

![Start php di browser](https://github.com/yogidm/WebBasic/blob/main/images/loadLocalhost.jpg)

------------------------------------------------------------------------

## Struktur Dasar File PHP

Struktur file PHP ditandai dengan tag pembuka `<?php ... ?>`. Hal menarik dari PHP adalah kemampuannya untuk digabungkan langsung dengan HTML. Sebagai contoh, sebuah halaman HTML dapat menyisipkan skrip PHP untuk menampilkan teks tertentu. Hal ini menunjukkan fleksibilitas PHP yang memungkinkan pengembang menambahkan logika pemrograman ke dalam halaman web tanpa memisahkan file secara kaku.

``` php
<!DOCTYPE html>
<html>
<body>
  <h1>Belajar PHP</h1>
  <?php
    echo "Ini kode PHP di dalam HTML.";
  ?>
</body>
</html>
```



**Petunjuk penggunaan:**  
Simpan dengan nama `index.php` dan letakkan di folder `htdocs` (jika menggunakan XAMPP). Akses melalui browser untuk melihat hasil kombinasi HTML dan PHP.

------------------------------------------------------------------------

## Variabel dan Tipe Data

Untuk mengelola data, PHP menyediakan variabel yang selalu diawali dengan tanda `$`. Tidak perlu mendeklarasikan tipe data secara eksplisit karena PHP akan menyesuaikan dengan nilai yang diberikan. Misalnya `$nama = "Andi";` menyimpan teks, `$umur = 20;` menyimpan bilangan bulat, dan `$aktif = true;` menyimpan nilai logika. Data yang tersimpan dapat ditampilkan kembali atau diolah sesuai kebutuhan, menjadikan PHP cukup sederhana untuk pemula namun tetap fleksibel.

``` php
<?php
$nama = "Andi";       // String
$umur = 20;           // Integer
$tinggi = 1.75;       // Float
$aktif = true;        // Boolean

echo "Nama: $nama, Umur: $umur";
?>
```

**Petunjuk penggunaan:**  
Buat file `variabel.php`, jalankan di browser, dan amati bagaimana data dari berbagai tipe ditampilkan.


------------------------------------------------------------------------

## Operator
Kemampuan mengolah data semakin kuat dengan adanya operator. Operator aritmetika memungkinkan penjumlahan atau pengurangan nilai, operator perbandingan digunakan untuk mengevaluasi hubungan antarvariabel, sementara operator logika membantu menggabungkan berbagai kondisi. Dengan kombinasi ini, PHP mampu menangani perhitungan maupun evaluasi logika secara efisien.

-   Aritmetika: `+`, `-`, `*`, `/`, `%`\
-   Perbandingan: `==`, `!=`, `<`, `>`\
-   Logika: `&&`, `||`, `!`

``` php
<?php
$a = 10;
$b = 3;

echo $a + $b; // 13
echo $a > $b; // true
?>
```

**Petunjuk penggunaan:**  
Jalankan file `operator.php` untuk menguji berbagai operator. Ubah nilai variabel `$a` dan `$b` untuk mencoba hasil lain.

------------------------------------------------------------------------

## Percabangan
Keputusan dalam program dapat dikendalikan melalui percabangan `if`, `elseif`, dan `else`. Contohnya, sebuah nilai ujian dapat dinilai dengan kondisi tertentu: jika nilai lebih dari 80 maka hasilnya A, jika di atas 70 maka B, selain itu C. Logika semacam ini membuat aplikasi menjadi dinamis, karena dapat beradaptasi dengan berbagai kemungkinan input.

``` php
<?php
$nilai = 75;

if ($nilai >= 80) {
    echo "A";
} elseif ($nilai >= 70) {
    echo "B";
} else {
    echo "C";
}
?>
```

**Petunjuk penggunaan:**  
Simpan file `ifelse.php`, lalu ubah nilai variabel `$nilai` untuk melihat hasil yang berbeda.

------------------------------------------------------------------------

## Perulangan
Selain percabangan, program juga sering membutuhkan pengulangan. PHP menyediakan perulangan seperti `for` untuk mengulang berdasarkan jumlah langkah tertentu dan `while` untuk mengulang selama kondisi masih terpenuhi. Dengan teknik ini, kode yang sama tidak perlu dituliskan berulang, sehingga program menjadi lebih ringkas dan efisien.

``` php
<?php
// for
for ($i = 1; $i <= 5; $i++) {
    echo "Nomor: $i <br>";
}

// while
$x = 1;
while ($x <= 3) {
    echo "Ulang ke-$x <br>";
    $x++;
}
?>
```

**Petunjuk penggunaan:**  
Simpan file `loop.php` dan jalankan. Perhatikan bagaimana perulangan menghasilkan output berulang sesuai kondisi.

------------------------------------------------------------------------

## Array

Untuk menyimpan banyak data sekaligus, PHP menggunakan array. Array indeks digunakan untuk menyimpan daftar nilai yang dapat diakses berdasarkan nomor urut, seperti daftar buah. Ada juga array asosiatif yang menggunakan kunci berupa string, misalnya menyimpan informasi siswa dengan pasangan “nama” dan “umur”. Struktur data ini memudahkan pengorganisasian dan pengaksesan data yang lebih kompleks.

``` php
<?php
$buah = ["Apel", "Jeruk", "Mangga"];
echo $buah[1]; // Jeruk

// Array asosiatif
$siswa = ["nama" => "Budi", "umur" => 18];
echo $siswa["nama"];
?>
```

**Petunjuk penggunaan:**  
Simpan file `array.php` lalu jalankan. Coba tambahkan elemen baru ke dalam array untuk melihat perbedaannya.

------------------------------------------------------------------------

## Fungsi
Agar kode lebih terstruktur, PHP mendukung pembuatan fungsi. Fungsi adalah sekumpulan perintah yang didefinisikan sekali lalu bisa digunakan berkali-kali. Sebagai contoh, fungsi `sapa($nama)` bisa dipanggil untuk menyapa siapa pun tanpa perlu menuliskan ulang logika yang sama. Pendekatan modular seperti ini membuat kode lebih mudah dibaca dan dipelihara.

``` php
<?php
function sapa($nama) {
    return "Halo, $nama!";
}

echo sapa("Siti");
?>
```

**Petunjuk penggunaan:**  
Simpan file `fungsi.php` dan jalankan. Ubah parameter nama pada fungsi untuk mencoba output lain.

------------------------------------------------------------------------

## Form dan Input

Interaktivitas web semakin terasa ketika PHP dipadukan dengan formulir HTML. Sebuah form dapat mengirimkan data ke file PHP untuk diproses. Misalnya, pengguna mengisi nama pada form, lalu PHP menerima input tersebut melalui `$_POST` dan menampilkannya kembali ke layar. Agar lebih aman, data input dapat difilter dengan fungsi seperti `htmlspecialchars` untuk mencegah penyalahgunaan.

**form.html**

``` html
<form action="proses.php" method="post">
  Nama: <input type="text" name="nama">
  <button type="submit">Kirim</button>
</form>
```

**proses.php**

``` php
<?php
$nama = $_POST['nama'];
echo "Halo, " . htmlspecialchars($nama);
?>
```

**Petunjuk penggunaan:**  
Simpan dua file, `form.html` dan `proses.php`, dalam folder yang sama. Buka `form.html` di browser, isi data, lalu klik Kirim.


------------------------------------------------------------------------

## Koneksi Database (MySQL)

Tahap berikutnya adalah menghubungkan PHP dengan basis data. Dengan bantuan PDO, PHP dapat membuka koneksi ke MySQL dan mengeksekusi perintah SQL, misalnya menyimpan data pengguna baru ke tabel. Proses ini memungkinkan data tidak hanya ditampilkan sementara di layar, tetapi juga disimpan secara permanen dalam sistem basis data, yang menjadi dasar bagi aplikasi web berskala besar dan modern.

**db.php**

``` php
<?php
$pdo = new PDO("mysql:host=localhost;dbname=demo_db", "root", "");
$pdo->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
?>
```

**insert.php**

``` php
<?php
require 'db.php';
$stmt = $pdo->prepare("INSERT INTO users (nama,email) VALUES (?, ?)");
$stmt->execute(["Andi", "andi@mail.com"]);
echo "Data tersimpan";
?>
```

**Petunjuk penggunaan:**  
Buat database `demo_db` dan tabel `users` dengan kolom `nama` dan `email`. Simpan file `db.php` dan `insert.php`, lalu jalankan `insert.php` di browser untuk menambahkan data ke database.


------------------------------------------------------------------------

# Tugas

## Aplikasi Profil Mahasiswa Interaktif dengan PHP dan MySQL

## Deskripsi
Buatlah sebuah aplikasi web sederhana berbasis PHP yang menampilkan profil mahasiswa lengkap serta memungkinkan input data tambahan melalui form dan penyimpanan ke database. Aplikasi ini bersifat personal (unik untuk setiap mahasiswa) dengan menampilkan identitas asli (nama, NIM, foto).

## Tujuan Pembelajaran
Mahasiswa mampu memahami dan mengimplementasikan konsep dasar PHP meliputi:
- Variabel dan operator  
- Percabangan dan perulangan  
- Array dan fungsi  
- Form input dan pemrosesan data  
- Koneksi PHP ke database MySQL  

## Spesifikasi Teknis

### Halaman Utama (`index.php`)
- Menampilkan nama, NIM, foto pribadi (foto disimpan dengan nama sesuai NIM).  
- Menggunakan variabel untuk menyimpan data pribadi (nama, tahun lahir, NIM).  
- Hitung umur mahasiswa secara otomatis dengan operator aritmetika.  
- Gunakan percabangan untuk menampilkan kategori usia:  
  -  Kurang dari 20 = *Remaja*  
  - 20 sampai 25    = *Dewasa Muda*  
  -   Lebih dari 25 = *Dewasa*
- Buat fungsi `sapaMahasiswa($nama, $nim)` yang mengembalikan kalimat sambutan.  

### Perulangan
- Gunakan `for` untuk mencetak angka 1–10.  
- Gunakan `while` untuk mencetak huruf A–J.  

### Array
- Buat array berisi minimal 5 mata kuliah favorit.  
- Tampilkan seluruh isi array menggunakan perulangan.  

### Form Input
- Buat form (`form.html`) untuk menerima input: nama teman, hobi, dan kota asal.  
- Proses data dengan `proses.php` dan tampilkan hasilnya dalam format naratif:  
  > "Halo [nama teman], hobi kamu adalah [hobi] dan kamu berasal dari [kota asal]."  

### Koneksi Database (MySQL)
- Buat database `praktikum_php` dengan tabel `mahasiswa` (kolom: `id`, `nama`, `nim`, `foto`, `motto`).  
- Buat `insert.php` untuk menyimpan data mahasiswa (gunakan data diri sendiri).  
- Buat `read.php` untuk menampilkan seluruh data mahasiswa yang tersimpan.  

## Ketentuan Unik
- Data identitas (nama, NIM, foto) bisa dummy bisa asli sesuai mahasiswa.  
- Foto harus diberi nama sesuai NIM, misalnya `220101001.jpg`.  
- Kolom *motto* diisi dengan kalimat motivasi pribadi.  
- Setiap mahasiswa menghasilkan aplikasi dengan ciri khas unik sesuai identitas masing-masing.  

--------------------------------------



