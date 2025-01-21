# Pemograman-Orientasi-Objek-UAS

# Video Penjelasan 

https://youtu.be/Z9GiRWHICM0?si=L6Sk16JrFi9LrGUO

Proyek ini adalah aplikasi CRUD Mahasiswa yang dibangun menggunakan Java, dengan menerapkan arsitektur MVC (Model-View-Controller). Program ini juga terhubung dengan MySQL sebagai sistem manajemen basis data untuk menyimpan dan memanipulasi data mahasiswa dan nilai mereka.

# Deskripsi Proyek
Proyek ini dibuat untuk memenuhi tugas akhir mata kuliah Pemrograman Berorientasi Objek (OOP) dengan menerapkan konsep dasar CRUD (Create, Read, Update, Delete). CRUD digunakan untuk mengelola data mahasiswa melalui antarmuka berbasis Java yang terhubung dengan MySQL untuk penyimpanan data. Program ini memanfaatkan pola desain MVC untuk memisahkan antara tampilan pengguna, logika bisnis, dan pengelolaan data.

# Arsitektur MVC
Berikut adalah penjelasan setiap komponen MVC:

* Model: Komponen ini bertanggung jawab untuk mengelola data aplikasi. Model mengakses database dan melakukan operasi CRUD, seperti menambahkan, mengedit, atau menghapus data mahasiswa.

* View: Bagian ini berfungsi sebagai antarmuka pengguna. View menampilkan informasi kepada pengguna dan menerima input dari mereka. Antarmuka ini dapat berupa form-form untuk input data mahasiswa dan nilai.

* Controller: Controller berfungsi untuk menghubungkan Model dan View. Ia menangani interaksi pengguna, memproses data yang dimasukkan, dan memerintahkan Model untuk melakukan operasi tertentu (seperti menambah, memperbarui, atau menghapus data). Setelah itu, Controller memberi perintah kepada View untuk menampilkan hasilnya.

  # Alur Kerja Program
Berikut adalah langkah-langkah alur kerja dari program ini:

* Menjalankan Program: Program dimulai dengan menjalankan file Main.java, yang menjadi titik awal eksekusi.
* Instansiasi View dan Controller: Instance dari View dan Controller akan dibuat untuk memulai proses interaksi dengan pengguna.
* Inisialisasi Model: Controller akan menginisialisasi Model yang akan bertugas dalam manipulasi data.
* Interaksi Pengguna: View akan menampilkan antarmuka kepada pengguna untuk memasukkan data mahasiswa dan nilai.
* Proses Input: Pengguna akan memasukkan data melalui form yang disediakan oleh View.
* Pemrosesan Data: Controller akan memproses data yang dimasukkan dan memberikan perintah kepada Model.
* Operasi Database: Model akan berinteraksi dengan MySQL untuk melakukan operasi sesuai perintah (misalnya menambah atau menghapus data).
* Menampilkan Hasil: Setelah operasi selesai, View akan menampilkan hasilnya kembali kepada pengguna.

# Fitur Program
Program ini menyediakan beberapa fitur utama untuk pengelolaan data mahasiswa dan nilai mereka, antara lain:

1. Create: Menambahkan data mahasiswa dan nilai baru ke dalam database.
2. Read: Menampilkan data mahasiswa dan nilai yang sudah ada dalam database.
3. Update: Memperbarui data mahasiswa atau nilai yang sudah ada.
4. Delete: Menghapus data mahasiswa atau nilai yang dipilih dari database.

   # Dokumentasi Output
Berikut adalah beberapa tampilan output dari program ini:

* Form Mahasiswa: Form untuk memasukkan data mahasiswa yang mencakup informasi seperti nama, NIM, jurusan, dan lainnya.
* Form Nilai: Form untuk memasukkan nilai mata kuliah mahasiswa yang mencakup kolom untuk kode mata kuliah, nilai, dan lainnya.
* Create Nilai: Tampilan form untuk menambahkan nilai baru bagi mahasiswa.
* Update Nilai: Tampilan form untuk memperbarui nilai yang sudah ada untuk mahasiswa tertentu.

  ![Screenshot 2025-01-21 103755](https://github.com/user-attachments/assets/f09addd1-820d-473d-b464-28185bf39762)

