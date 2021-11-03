# Rangkuman Pertemuan 08 Pemrograman Mobil
Pada minggu ini membahas tentang beberapa storage yang ada di android 
## Data Storage
Jenis-jenis data storage antara lain:
<li>Shared Preferences
<li>Internal Storage
<li>External Storage
<li>SQLite Databases
<li>Content Providers
<li>Network Connection
<li>Cloud Backup
<li>Firebase Realtime Database

## Shared Preferences
Shared Preferences adalah read and write sejumlah kecil data primitif sebagai pasangan key-value ke file di penyimpanan device. Class SharedPreference menyediakan API untuk reading, writing, dan mengelola data. Method onPause() digunakan untuk menyimpan data. Sedangkan onCreate() untuk restore data.

## SQLite Database
<li>Menyimpan data dalam tabel baris dan kolom (spreadsheet…)
<li>Field = perpotongan antara baris dan kolom
<li>Bidang berisi data, referensi ke bidang lain, atau referensi ke tabel lain
<li>Baris diidentifikasi oleh ID unik Nama kolom unik per tabel

## Room, LiveData, and ViewModel
Room adalah perpustakaan pemetaan objek SQL yang kuat, menghasilkan kode Android SQLite, menyediakan API sederhana untuk database anda

Komponen penting dari Room antara lain:
<li>Entity: Mendefinisikan skema tabel database.
<li>DAO: Objek Akses Basis Data Mendefinisikan operasi baca/tulis untuk basis data.
<li>Database: Sebuah pemegang database. Digunakan untuk membuat atau menghubungkan ke database

## ViewModel 
ViewModel adalah objek yang menyediakan data untuk komponen UI dan bertahan dari perubahan konfigurasi. Kita juga dapat menggunakan ViewModel untuk berbagi data antar fragment.

## LiveData 
LiveData adalah class pemegang data yang mengetahui peristiwa lifecycle. LiveData menyimpan nilai dan memungkinkan nilai ini untuk diamati. Gunakan LiveData untuk selalu memperbarui UI kita dengan data terbaru dan terbaik. Gunakan LiveData dengan Room, yang mana Room akan me-generate semua kode untuk memperbarui LiveData saat database diperbarui.

