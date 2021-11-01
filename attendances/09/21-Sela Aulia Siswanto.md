<h1>Rangkuman Minggu-09</h1>
Pada pertemuan ini memiliki bebarapa pembahasan tentang storage yang ada di Android, seperti berikut ini:

<h2>A. Data Storage</h2>
Didalam data storage ini terdapat jenis-jenis data, diantaranya:

- Shared Preferences => Bersama—Data primitif pribadi dalam pasangan nilai kunci
- Internal => Data pribadi di memori perangkat.
- External => Data publik di perangkat atau penyimpanan eksternal.
- SQLite Databases => Data terstruktur dalam database pribadi
- Content Providers =>Simpan secara pribadi dan sediakan untuk umum
Selain itu juga ada Data Storage di luar android, diantaranya yaitu :

- Network Connection => Storage yang terletak pada web dengan server kita sendiri
- Cloud Backup => Back up aplikasi dan data pengguna di cloud
- Firebase Realtime Database => Simpan dan sinkronkan data dengan database cloud NoSQL di seluruh klien secara realtime

<h2>B. Shared Preferences</h2>
Shared Preferences adalah read and write sejumlah kecil data primitif sebagai pasangan key-value ke file di penyimpanan device. Class SharedPreference menyediakan API untuk reading, writing, dan mengelola data. Method onPause() digunakan untuk menyimpan data. Sedangkan onCreate() untuk restore data.

1. Cara membuat (Create) Shared Preferences
    - Hanya butuh satu file Shared Preferences tiap aplikasi
    - Beri nama dengan nama package aplikasi yang unik dan mudah dikaitkan dengan aplikasi
    - Argumen MODE untuk getSharedPreferences() adalah untuk backwards compatibility, hanya gunakan MODE_PRIVATE agar aman
2. Cara menyimpan (Saving) Shared Preferences
    - SharedPreferences.Editor interface
    - Menangani semua operasi file
    - Menempatkan methods overwrite jika key telah ada
    - apply() menyimpan secara asinkron dan aman
3. Cara memulihkan (Restoring) Shared Preferences
    - Restore di onCreate() pada Activity
    - Dapatkan methods mengambil dua argumen—key, dan nilai default jika key tidak dapat ditemukan
    - Gunakan argumen default sehingga kita tidak perlu menguji apakah preference ada di file
4. Cara membersihkan (Clearing) Shared Preferences
    - Panggil method clear() pada SharedPreferences.Editor dan terapkan perubahan
    - Kita dapat menggabungkan put dan clear. Namun, saat kita apply(), clear() selalu dilakukan terlebih dahulu, apa pun urutannya.

<h2>C. SQLITE Primer</h2>

- Menyimpan data dalam tabel baris dan kolom (spreadsheet…)
- Field = perpotongan antara baris dan kolom
- Bidang berisi data, referensi ke bidang lain, atau referensi ke tabel lain
- Baris diidentifikasi oleh ID unik
Nama kolom unik per tabel

<h2>D. Room, LiveData, and ViewModel</h2>
Room adalah library pemetaan object SQL yang kuat, me-generate kode Android SQLite menggunakan annotation, dan menyediakan API sederhana untuk database kita.

Adapun komponen dalam Room yang perlu diketahui adalah :

- Entity : Mendefinisikan skema tabel database
- DAO (Database Access Object) : Mendefinisikan operasi read/write untuk database
- Database : Database holder => Digunakan untuk create atau connect ke database

ViewModel adalah objek yang menyediakan data untuk komponen UI dan bertahan dari perubahan konfigurasi. Kita juga dapat menggunakan ViewModel untuk berbagi data antar fragment.

LiveData adalah class pemegang data yang mengetahui peristiwa lifecycle. LiveData menyimpan nilai dan memungkinkan nilai ini untuk diamati. Gunakan LiveData untuk selalu memperbarui UI kita dengan data terbaru dan terbaik. Gunakan LiveData dengan Room, yang mana Room akan me-generate semua kode untuk memperbarui LiveData saat database diperbarui.