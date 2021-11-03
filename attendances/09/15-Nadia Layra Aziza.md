# Pertemuan 09

## Rangkuman Bab 09 dan 10 

## A. Data Storage
Pada Pertemuan 9 ini, membahas tentang Data Storage. Adapun jenis-jenis dari data storage antara lain :
- Shared Preferences : Data primitif private dalam pasangan key-value.
- Internal Storage : Data private di memori device.
- External Storage : Data publik pada device atau penyimpanan eksternal.
- SQLite Database : Structured data in a private database private.
- Content Providers : Simpan secara pribadi dan sediakan untuk umum. Penerapan yang paling umum adalah aplikasi contact (berbagi data antar aplikasi contact dengan whatsapp).

Selain itu juga ada Data Storage di luar android, diantaranya yaitu :
- Network Connection : Di web dengan server kita sendiri
- Cloud Backup : Back up aplikasi dan data pengguna di cloud
- Firebase Realtime Database : Simpan dan sinkronkan data dengan database cloud NoSQL di seluruh klien secara realtime

## B. Shared Preferences
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

## C. SQLite Primer
Untuk mengakses SQLite itu memiliki banyak cara, namun pengembangan dari Jetpack direkomentasikan menggunakan room. Jika tidak menggunakan room, maka akan menggunakan suatu SQL yang mana jika databasenya menggunakan RDBMS itu hampir sama terutama dibagian query, hanya saja berbeda pada tipe data nya. Perbedaanya adalah penulisan statement tidak dilakukan secara langsung seperti penulisan query pada database, namun dalam penulisannya dibutuhkan penyimpanan pada variabel. 

Query selalu me-return object Cursor. Cursor adalah object interface yang menyediakan akses random read-write ke kumpulan result yang dikembalikan/di-return oleh query database. Cursor bisa dianggap sebagai penunjuk ke baris tabel.

## D. Room, LiveData, and ViewModel
Jika dibandingkan dengan SQLite, sebenarnya lebih mudah menggunakan room karena tidak terlalu memperhatikan query nya. Room adalah library pemetaan object SQL yang kuat, me-generate kode Android SQLite menggunakan annotation, dan menyediakan API sederhana untuk database kita. 

Adapun komponen dalam Room yang perlu diketahui adalah :
- Entity : Mendefinisikan skema tabel database
- DAO (Database Access Object) : Mendefinisikan operasi read/write untuk database
- Database : Database holder => Digunakan untuk create atau connect ke database

ViewModel adalah objek yang menyediakan data untuk komponen UI dan bertahan dari perubahan konfigurasi. Kita juga dapat menggunakan ViewModel untuk berbagi data antar fragment. 

LiveData adalah class pemegang data yang mengetahui peristiwa lifecycle. LiveData menyimpan nilai dan memungkinkan nilai ini untuk diamati. Gunakan LiveData untuk selalu memperbarui UI kita dengan data terbaru dan terbaik. Gunakan LiveData dengan Room, yang mana Room akan me-generate semua kode untuk memperbarui LiveData saat database diperbarui. 








