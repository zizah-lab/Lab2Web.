# Lab2Web: Praktikum 2 HTML Lanjutan

Mata kuliah: Pemrograman Web
Nama: Azizah Rachmatania
NIM: 312510159

Repository ini berisi hasil Praktikum 2 (HTML Lanjutan). Materi yang dikerjakan meliputi tabel, form dan berbagai jenis input, semantic HTML, multimedia, dan validasi form dasar. Semua kode ditulis di Visual Studio Code dan dicek hasilnya di browser setiap selesai mengubah file. Screenshot dokumentasi ada di folder `Dokumentasi`.

## Struktur Folder

```
Lab2Web/
├── index.html
├── biodata.html
├── media/
│   ├── audio.mp3
│   └── video.mp4
├── Dokumentasi/
└── README.md
```

## Langkah 1: Membuat Tabel Data Mahasiswa

Langkah pertama adalah membuat tabel sederhana dengan `<table border="1">`. Baris judul dibuat dengan `<th>` (NIM, Nama, Program Studi), sedangkan isi datanya memakai `<td>`. Data mahasiswa yang ditampilkan ditambah sampai minimal tiga baris.

**1. Membuat Tabel Data Mahasiswa**

![1. Membuat Tabel Data Mahasiswa](<Dokumentasi/1. Membuat Tabel Data Mahasiswa.png>)

**1. Membuat Tabel Data Mahasiswa (hasil)**

![1. Membuat Tabel Data Mahasiswa (hasil)](<Dokumentasi/1.Membuat Tabel Data Mahasiswa (hasil).png>)

## Langkah 2: Mengembangkan Tabel dengan thead, tbody, dan tfoot

Tabel dari langkah 1 dikembangkan supaya lebih terstruktur. Ditambahkan `<caption>` sebagai judul tabel, `<thead>` untuk bagian header, `<tbody>` untuk isi data, dan `<tfoot>` untuk baris rata-rata. Pada `<tfoot>` dipakai atribut `colspan="2"` untuk menggabungkan dua kolom sehingga tulisan "Rata-rata" berada di satu sel yang lebar.

**2. Mengembangkan Tabel dengan thead, tbody, dan tfoot**

![2. Mengembangkan Tabel dengan thead, tbody, dan tfoot](<Dokumentasi/2. Mengembangkan Tabel dengan thead, tbody, dan tfoot.png>)

**2. Mengembangkan Tabel dengan thead, tbody, dan tfoot (hasil)**

![2. Mengembangkan Tabel dengan thead, tbody, dan tfoot (hasil)](<Dokumentasi/2.Mengembangkan Tabel dengan thead, tbody, dan tfoot (hasil).png>)

## Langkah 3: Membuat Form Registrasi Mahasiswa

Form dibuat dengan tag `<form>` dan berisi input nama (`text`), email (`email`), password (`password`), dan tanggal lahir (`date`). Setiap input punya `<label>` yang terhubung lewat atribut `for` dan `id`. Di bagian bawah ada dua tombol, yaitu Daftar (`submit`) dan Reset (`reset`).

**3. Membuat Form Registrasi Mahasiswa**

![3. Membuat Form Registrasi Mahasiswa](<Dokumentasi/3. Membuat Form Registrasi Mahasiswa.png>)

**3. Membuat Form Registrasi Mahasiswa (hasil)**

![3. Membuat Form Registrasi Mahasiswa (hasil)](<Dokumentasi/3.Membuat Form Registrasi Mahasiswa (hasil).png>)

## Langkah 4: Radio Button dan Checkbox

Radio button dipakai untuk pilihan jenis kelamin. Kedua radio memakai `name="jk"` yang sama sehingga hanya satu yang bisa dipilih. Checkbox dipakai untuk keahlian (HTML, CSS, JavaScript), dan pengguna boleh memilih lebih dari satu.

**4. Radio Button dan Checkbox**

![4. Radio Button dan Checkbox](<Dokumentasi/4. Radio Button dan Checkbox.png>)

**4. Radio Button dan Checkbox (hasil)**

![4. Radio Button dan Checkbox (hasil)](<Dokumentasi/4.Radio Button dan Checkbox(hasil).png>)

## Langkah 5: Select dan Textarea

Pada langkah ini ditambahkan `<select>` untuk memilih program studi dan `<textarea>` untuk mengisi alamat. Opsi pertama pada select dikosongkan dengan teks "-- Pilih Prodi --" sebagai petunjuk. Ukuran textarea diatur dengan `rows="5"` dan `cols="40"`.

**5. Select dan Textarea**

![5. Select dan Textarea](<Dokumentasi/5. Select dan Textarea.png>)

## Langkah 6: Validasi Form Dasar

Validasi dasar ditambahkan langsung lewat atribut HTML. Input nama memakai `required` dan `minlength="3"`, input email memakai `required` dengan `type="email"`, dan input umur memakai `min="17"`, `max="60"`, dan `required`. Saat tombol Kirim ditekan dengan form kosong atau isi yang tidak sesuai, browser menampilkan pesan peringatan dan data tidak terkirim.

**6. Validasi Form Dasar**

![6. Validasi Form Dasar](<Dokumentasi/6. Validasi Form Dasar .png>)

**5. dan 6. (hasil)**

![5. dan 6. (hasil)](<Dokumentasi/5. dan 6. (hasil).png>)

## Langkah 7: Membuat Halaman Semantic HTML

Halaman portal mahasiswa disusun memakai elemen semantic. `<header>` berisi judul, `<nav>` berisi menu navigasi, `<main>` berisi konten utama yang dibagi lagi dengan `<section>` dan `<article>`, `<aside>` berisi informasi tambahan, dan `<footer>` berisi hak cipta. Dengan begitu struktur halaman lebih jelas dibanding memakai `<div>` saja.

**7. Membuat Halaman Semantic HTML**

![7. Membuat Halaman Semantic HTML](<Dokumentasi/7. Membuat Halaman Semantic HTML.png>)

**7. Membuat Halaman Semantic HTML (hasil)**

![7. Membuat Halaman Semantic HTML (hasil)](<Dokumentasi/7.Membuat Halaman Semantic HTML (hasil) .png>)

## Langkah 8: Menambahkan Multimedia

File audio dan video disimpan di folder `media`, lalu dipanggil dengan elemen `<audio>` dan `<video>`. Keduanya memakai atribut `controls` supaya ada tombol putar, dan `<source>` untuk menunjuk file. Teks di dalam tag akan tampil kalau browser tidak mendukung elemen tersebut.

**8. Menambahkan Multimedia**

![8. Menambahkan Multimedia](<Dokumentasi/8. Menambahkan Multimedia.png>)

**8. Menambahkan Multimedia (hasil)**

![8. Menambahkan Multimedia (hasil)](<Dokumentasi/8.Menambahkan Multimedia (hasil) .png>)

## Langkah 9: Proyek Mini Form Biodata Mahasiswa

Proyek mini menggabungkan semua materi sebelumnya dalam satu halaman, yaitu `biodata.html`. Isinya:

- Struktur semantic: `header`, `nav`, `main`, `section`, dan `footer`.
- Tabel identitas mahasiswa (NIM, nama, program studi).
- Form biodata dengan input nama, email, select program studi, dan textarea alamat.
- Validasi dasar memakai atribut `required` pada semua isian.
- Satu elemen multimedia.

**9.1 Proyek Mini Form Biodata Mahasiswa**

![9.1 Proyek Mini Form Biodata Mahasiswa](<Dokumentasi/9.1 Proyek Mini — Form Biodata Mahasiswa .png>)

**9.2 Proyek Mini Form Biodata Mahasiswa**

![9.2 Proyek Mini Form Biodata Mahasiswa](<Dokumentasi/9.2 Proyek Mini — Form Biodata Mahasiswa.png>)

**9. Hasil**

![9. Hasil](<Dokumentasi/9.Hasil.png>)

## Cara Menjalankan

1. Clone atau download repository ini.
2. Buka file `index.html` atau `biodata.html` di browser.
3. Pastikan file `audio.mp3` dan `video.mp4` ada di folder `media` supaya multimedia bisa diputar.
