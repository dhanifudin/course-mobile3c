# RANGKUMAN PERTEMUAN 9

Pada pertemuan 9 ini membahasa seputar storage yang ada pada Android. Diantaranya seperti dibawah ini:

## A. DATA STORAGE

Didalam data storage ini terdapat jenis-jenis data, diantaranya:

- Shared Preferences => Bersama—Data primitif pribadi dalam pasangan nilai kunci
- Internal => Data pribadi di memori perangkat
- External => Data publik di perangkat atau penyimpanan eksternal
- SQLite Databases => Data terstruktur dalam database pribadi
- Content Providers =>Simpan secara pribadi dan sediakan untuk umum

Selain itu juga ada Data Storage di luar android, diantaranya yaitu :

- Network Connection => Storage yang terletak pada web dengan server kita sendiri
- Cloud Backup => Back up aplikasi dan data pengguna di cloud
- Firebase Realtime Database => Simpan dan sinkronkan data dengan database cloud NoSQL di seluruh klien secara realtime

## B. SHARED PREFERENCES

Shared preferences adalah membaca dan menulis sejumlah kecil data primitif sebagai pasangan kunci/nilai ke file di penyimpanan perangkat.
Kelas SharedPreference menyediakan API untuk membaca, menulis, dan mengelola data ini. Dan Simpan data di onPause() pulihkan di onCreate()

## C. SQLITE PRIMER

- Menyimpan data dalam tabel baris dan kolom (spreadsheet…)
- Field = perpotongan antara baris dan kolom
- Bidang berisi data, referensi ke bidang lain, atau referensi ke tabel lain
- Baris diidentifikasi oleh ID unik
- Nama kolom unik per tabel

## D. ROOM, LIVE DATA, DAN VIEW MODEL

Room adalah perpustakaan pemetaan objek SQL yang kuat. Room dapat menghasilkan kode Android SQLite serta menyediakan API sederhana untuk database Anda
