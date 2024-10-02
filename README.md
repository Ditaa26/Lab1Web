# Lab1Web
Dita Tiara Putri (312310131)

# Langkah-langkah pembuatan tab dasar
Buat file baru dengan nama lab1_tag_dasar.html   
```sh
<title>Tag HTML Dasar</title>
```    
Kemudian, buka file tersebut pada web browser  

![image](https://github.com/user-attachments/assets/1da2a34b-f0cb-406f-9da0-b8edacb999b1)

# Langkah 1
Selanjutnya membuat paragraf sederhana
```sh
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
        Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
        adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
        HTML.</p>  
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
        mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
        tag dasar html.</p>
```
![Screenshot (313)](https://github.com/user-attachments/assets/5e9fae16-82d3-4d56-bada-baa7e8846a59)
![Screenshot (314)](https://github.com/user-attachments/assets/23b97db8-8650-4419-a1b2-c7ab759279d1)

# Langkah 2
Selanjutnya menambahkan judul
h1= untuk paragraf pertama  
h2= untuk paragraf kedua  
```sh
<h1>Belajar Dasar HTML</h1>
<h2>Paragraf pada HTML</h2>
```
![Screenshot (316)](https://github.com/user-attachments/assets/c9b075eb-6c54-4ace-b8e0-6c6870e5bfe0)
![Screenshot (317)](https://github.com/user-attachments/assets/9adcb2ee-9bf7-4bb0-8bce-0d70200f5b7a)

# Langkah 3
Selanjutnya Memformat teks
mark : untuk meng-highlight teks  
<b : untuk menebalkan (bold)  
<i : mengubah menjadi font miring (italic)  
<u : untuk menggaris bawahi teks  
```sh
<p>Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi
        <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat
        adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
        HTML.</p>
```
![Screenshot (321)](https://github.com/user-attachments/assets/f294b0ec-430a-4700-9901-a260970ca133)

# Langkah 4
Selanjutnya Menyisipkan Gambar
```sh
<img src="Logo-Universitas-Pelita-Bangsa.png" width="200" title="Logo Universitas Pelita Bangsa" alt="Logo Universitas Pelita Bangsa"
```
![Screenshot (322)](https://github.com/user-attachments/assets/dc4e2fd3-be53-4ff0-bad9-e98898fcfdee)

# Langkah 5
Selanjutnya Menambahkan Hyperlink
```sh
   <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="halaman2.html">halaman 2</a>
        <a href="http://www.google.com">halaman Web Eksternal Google</a>
    </nav>
```
![Screenshot (327)](https://github.com/user-attachments/assets/2a65742e-a9ad-46a3-aaf1-4337c0c183ca)

# Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag?  
  Jawab  
  akan terjadi eror jika code tidak sama dengan yang seharusnya, contoh:
  ![image](https://github.com/user-attachments/assets/1c43cfce-ff0b-46c2-9437-75ed1b186c5c)
  contoh yang salah:
  ```sh
  <h2>Paragraf pada HTML</h3>
  ```
  contoh yang benar:
  ```sh
  <h2>Paragraf pada HTML</h2>
  ```

2. Apa perbedaan dari tag ``<p>`` dengan tag ``<br>``, berikan penjelasannya!  
   Jawab  
   •	Dalam kode HTML, tag ``<p>`` mendefinisikan paragraf. Secara default, browser memberikan spasi atau jarak vertikal sebelum dan sesudah tag ``<p>``, yang membuat teks dalam paragraf terlihat lebih terorganisir.  
   •	Tag ``<br>`` membuat baris baru di dalam teks tanpa memulai paragraf baru; tag ini hanya memindahkan teks ke baris berikutnya tanpa memberikan jarak vertikal tambahan. Tag ``<br>`` juga bersifat self-closing, artinya tidak memerlukan tag penutup.  
   •	Tag ``<p>`` menciptakan paragraf baru dengan jarak vertikal di antara paragraf, sementara tag ``<br>`` hanya menyisipkan baris baru tanpa jarak tambahan.  

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!  
   Jawab  
   •	Atribut alt berfungsi untuk memberikan teks alternatif yang akan ditampilkan jika gambar tidak dapat dimuat, seperti ketika file gambar hilang atau rusak, atau ketika pengguna menggunakan browser berbasis teks. Tujuan utama alt atribut adalah untuk membuat gambar lebih mudah diakses bagi pengguna yang mengalami gangguan penglihatan dan memberikan informasi penting jika gambar tidak muncul. Teks dalam alt atribut biasanya menjelaskan isi gambar atau fiturnya.  
   •	Atribut title memberikan teks keterangan yang muncul sebagai tooltip ketika pengguna mengarahkan kursor mouse ke atas gambar. Teks dalam atribut title dapat memberikan informasi tambahan, tetapi tidak menggantikan fungsi aksesibilitas seperti alt. Tooltip ini bersifat opsional dan hanya muncul ketika gambar tersedia dan dilihat dengan browser yang mendukung tooltip.  
   •	Atribut alt digunakan untuk teks alternatif yang ditampilkan saat gambar tidak bisa dimuat, dan penting untuk aksesibilitas.  
   •	Atribut title memberikan tooltip sebagai informasi tambahan yang muncul ketika gambar dilihat dengan kursor, tetapi tidak penting untuk aksesibilitas atau penggantian gambar yang hilang.  

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
   proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!  
   Jawab  
   •	Untuk menjaga tampilan gambar tetap proporsional, sebaiknya tidak mengisi kedua atribut width dan height secara bersamaan kecuali jika Anda memastikan bahwa rasio aspek (perbandingan lebar dan tinggi) gambar tetap sama.  
   •	Untuk mencegah distorsi gambar, sehingga gambar tetap terlihat proporsional, browser secara otomatis menyesuaikan atribut lain, misalnya lebar, secara proporsional berdasarkan rasio aspek asli gambar.  
   •	Jika Anda mengisi kedua atribut width dan height, browser akan memaksakan gambar untuk memenuhi ukuran yang ditentukan. Namun, rasio aspek gambar aslinya mungkin berbeda, yang dapat menyebabkan distorsi.

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
   _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?  
   Jawab  
   •	_blank: Membuka halaman terkait di tab baru atau jendela baru (tergantung pada pengaturan browser).  
   •	_self: Membuka halaman yang terkait di tab atau jendela yang diklik.  
      Ini adalah nilai default, sehingga browser akan menggunakan _self secara otomatis jika target tidak ditentukan.  
   •	_top: Membuka halaman terkait di frame teratas dari keseluruhan   halaman, menggantikan seluruh isi halaman dengan halaman baru. Ini berguna jika Anda bekerja dengan nested frames atau iframe, dan Anda ingin memastikan bahwa halaman baru menggantikan seluruh halaman, bukan hanya frame yang berisi link.  
   •	_parent: Membuka halaman terkait di frame induk dari frame atau iframe yang berisi link tersebut. Jika tidak ada frame induk, maka ini akan bekerja seperti _self.  

   








