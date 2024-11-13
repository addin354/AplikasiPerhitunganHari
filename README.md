# Aplikasi Penghitung Hari

Aplikasi ini digunakan untuk menghitung jumlah hari dalam sebuah bulan berdasarkan input bulan dan tahun yang diberikan oleh pengguna. Aplikasi ini menggunakan Java Swing untuk antarmuka grafis pengguna (GUI).

## Identitas
- Nama  : Addin Husnan Nadhari
- Npm   : 2210010037
- Kelas : 5B Nonreg Banjarmasin

## Fitur
- Pengguna dapat memilih bulan dari dropdown list.
- Pengguna dapat memasukkan tahun melalui spinner.
- Menampilkan jumlah hari pada bulan yang dipilih dan tahun yang diberikan.
- Terdapat tombol untuk keluar dari aplikasi.

## Cara Penggunaan
1. Pilih bulan yang diinginkan dari dropdown list.
2. Masukkan tahun yang sesuai menggunakan spinner.
3. Klik tombol **Hitung** untuk melihat jumlah hari pada bulan dan tahun yang dipilih.
4. Hasil jumlah hari akan ditampilkan di bawah tombol **Hitung**.
5. Klik tombol **Keluar** untuk menutup aplikasi.

## Prasyarat
- Java Development Kit (JDK) 8 atau versi yang lebih baru.
- IDE seperti NetBeans, IntelliJ IDEA, atau Eclipse untuk menjalankan aplikasi Java Swing.

## Menjalankan Aplikasi
1. Pastikan Anda telah menginstal JDK dan IDE pilihan Anda.
2. Salin kode sumber `PerhitunganHariFrame.java` ke dalam proyek Java Anda.
3. Jalankan aplikasi dan antarmuka pengguna akan muncul.
4. Ikuti instruksi pada aplikasi untuk memilih bulan dan tahun, lalu klik **Hitung** untuk menghitung jumlah hari.

## Struktur Program
- **PerhitunganHariFrame.java**: Kelas utama yang berisi logika untuk menghitung jumlah hari dan menangani interaksi pengguna.
  - **cmbBulan**: ComboBox untuk memilih bulan.
  - **spnTahun**: Spinner untuk memasukkan tahun.
  - **btnHitung**: Tombol untuk memulai perhitungan jumlah hari.
  - **lblHasil**: TextField untuk menampilkan jumlah hari hasil perhitungan.

## Desain GUI
Aplikasi ini menggunakan layout sederhana dengan elemen-elemen berikut:
- **ComboBox** untuk memilih bulan.
- **Spinner** untuk memasukkan tahun.
- **TextField** untuk menampilkan hasil jumlah hari.
- **Tombol** untuk menghitung dan keluar dari aplikasi.

## Contoh Hasil
Jika pengguna memilih bulan **Februari** dan tahun **2024**, hasil yang akan ditampilkan adalah:
Jumlah Hari: 29


