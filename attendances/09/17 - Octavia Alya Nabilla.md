Pertemuan 9

TI3C - 17 - Octavia Alya Nabilla

Pada pertemuan ini membahas tentang Preferences dan Settings

Yang pertama yaitu data storage. Dalam data storage terdapat option, yaitu :

1. Storing data yang berisikan:
- Preferensi Bersama = Data primitif pribadi dalam pasangan nilai key.
- Penyimpanan Internal = Data pribadi di memori perangkat.
- Penyimpanan Eksternal = Data publik di perangkat atau penyimpanan eksternal.
- Database SQLite = Data terstruktur dalam database pribadi.
- Penyedia Konten = Simpan secara pribadi dan sediakan untuk umum.

2. Storing data diluar android:
- Koneksi Jaringan = Di web dengan server Anda sendiri.
- Cloud Backup = Mencadangkan aplikasi dan data pengguna di cloud.
- Firebase Realtime Database = Menyimpan dan menyinkronkan data dengan database cloud NoSQL di seluruh klien secara realtime.

Kemudian ada Files, dimana terdapat:
1. Penyimpanan eksternal = Direktori publik
2. Penyimpanan internal = Direktori pribadi hanya untuk aplikasi Anda

Nantinya Aplikasi dapat menelusuri struktur direktori. Struktur dan operasinya mirip dengan Linux dan java.io

Kemudian ada SQLite Database, yaitu 
1. Ideal untuk data berulang atau terstruktur, seperti kontak
2. Android menyediakan database seperti SQL
3. Tercakup dalam bab dan praktik seperti:
    - SQLite Primer
    - Pengantar Database SQLite
    - Penyimpanan Data SQLite Praktis
    - Mencari Secara Praktis Database SQLite


Yang kedua ada Shared Preferences, yaitu :

1. Membaca dan menulis sejumlah kecil data primitif sebagai pasangan kunci/nilai ke file di penyimpanan perangkat
2. Kelas SharedPreference menyediakan API untuk membaca, menulis, dan mengelola data ini
3. Simpan data di onPause()
4. Memulihkan di onCreate()

Creating Shared Performance :
1. Hanya perlu satu file Preferensi Bersama per aplikasi
2. Beri nama dengan nama paket aplikasi Anda unik dan mudah dikaitkan dengan aplikasi
3. Argumen MODE untuk getSharedPreferences() adalah untuk kompatibilitas mundur—gunakan hanya MODE_PRIVATE agar aman


Kemudian yang ketiga yaitu SQLite Primer.
Pada bagian ini mengasumsikan bahwa Anda sudah familiar dengan,
1. Database secara umum
2. Database SQL 
3. Bahasa kueri SQL

Dalam SQL Database, terdapat:
1. Penyimpan data dalam tabel baris dan kolom (spreadsheet…)
2. Field = perpotongan antara baris dan kolom
3. Field berisi data, referensi ke bidang lain, atau referensi ke tabel lain
4. Rows diidentifikasi oleh ID unik
5. Nama kolom unik per tabel

Mengimplementasikan mesin database SQL yaitu,
1. mandiri (tidak memerlukan komponen lain)
2. tanpa server (tidak memerlukan backend server)
3. zero-configuration (tidak perlu dikonfigurasi untuk aplikasi Anda)
4. transaksional (perubahan dalam satu transaksi di SQLite terjadi sepenuhnya atau tidak sama sekali)


Yang Keempat yaitu Room, LiveData, dan ViewModel.

1. Room = Room adalah perpustakaan pemetaan objek SQL yang kuat, Menghasilkan kode Android SQLite, dan Menyediakan API sederhana untuk database Anda.
2. ViewModel = objek yang menyediakan data untuk komponen UI dan bertahan dari perubahan konfigurasi. Melakukan penyediakan data ke UI lalu bertahan dari perubahan konfigurasi lalu juga dapat menggunakan ViewModel untuk berbagi data antar fragmen.
3. LiveData = LiveData adalah kelas pemegang data yang mengetahui peristiwa siklus hidup. Itu menyimpan nilai dan memungkinkan nilai ini untuk diamati. LiveData adalah data yang dapat diamati dan akan memberi tahu pengamat saat data berubah. Gunakan LiveData untuk menjaga UI Anda tetap up to date dengan data terbaru dan terbaik.