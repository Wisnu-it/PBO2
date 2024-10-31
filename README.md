# PBO2
# Latihan 2 PBO - Wisnu Setia Budi (2210010293)

Aplikasi Penghitung Umur

Aplikasi Penghitung Umur adalah sebuah aplikasi berbasis Java Swing yang memungkinkan pengguna untuk menghitung umur dan mengetahui tanggal ulang tahun berikutnya. Aplikasi ini juga dapat menampilkan peristiwa-peristiwa penting pada tanggal ulang tahun pengguna berdasarkan data yang diambil dari API eksternal.
Fitur

    Hitung Umur: Menghitung umur secara detail berdasarkan tanggal lahir pengguna.
    Tanggal Ulang Tahun Berikutnya: Menampilkan hari ulang tahun berikutnya.
    Peristiwa Penting: Mengambil dan menampilkan peristiwa penting yang terjadi pada tanggal ulang tahun pengguna.

Struktur Proyek

Proyek ini terdiri dari dua file utama:

    PenghitungUmur.java: File utama yang mengatur antarmuka aplikasi dan menghubungkan komponen UI dengan logika aplikasi.
    PenghitungUmurHelper.java: File helper yang berisi logika untuk menghitung umur, menentukan tanggal ulang tahun berikutnya, dan mengambil data peristiwa penting dari API eksternal.

Cara Menggunakan Aplikasi

    Unduh atau Clone Repository: Unduh atau clone repositori ini ke dalam komputer Anda.

    bash

    git clone https://github.com/Wisnu-it/PenghitungUmur.git

    Jalankan Aplikasi:
        Buka aplikasi di IDE Java (misalnya, NetBeans atau IntelliJ).
        Jalankan file PenghitungUmur.java sebagai aplikasi Java.

    Masukkan Tanggal Lahir:
        Pilih tanggal lahir Anda di bagian "Pilih Tanggal Lahir".
        Klik tombol "Hitung Umur" untuk menghitung umur Anda.

    Lihat Hasil:
        Umur Anda akan ditampilkan pada kolom "Umur Anda".
        Tanggal ulang tahun berikutnya beserta harinya akan ditampilkan pada kolom "Hari Ulang Tahun Berikutnya".
        Bagian "Peristiwa Penting" akan menampilkan daftar peristiwa penting yang terjadi pada tanggal tersebut.

    Keluar dari Aplikasi: Klik tombol "Keluar" untuk menutup aplikasi.

API yang Digunakan

Aplikasi ini menggunakan dua API eksternal:

    On This Day API: Digunakan untuk mendapatkan peristiwa penting berdasarkan tanggal.
    Lingva Translate API: Digunakan untuk menerjemahkan deskripsi peristiwa dari bahasa Inggris ke bahasa Indonesia.

Catatan: Koneksi internet diperlukan untuk mengambil data dari API.
