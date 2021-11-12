# Pertemuan 9
## Data Storage
Pada data storage terdapat beberapa jenis yaitu : 
- Shared Preferences => Data primitif pribadi dalam pasangan key-value.
- Internal Storage => Data pribadi pada memori perangkat.
- External Storage => Data publik pada perangkat atau penyimpanan eksternal.
- SQLite Databases => Data terstruktur dalam database pribadi.
- Content Providers => Simpan secara pribadi dan sediakan secara publik.

Penyimpanan data diluar Android : 
- Network Connection => Di web dengan server Anda sendiri.
- Cloud Backup => Mencadangkan data aplikasi dan pengguna di cloud.
- Firebase Realtime Database => Menyimpan dan menyinkronkan data dengan database cloud NoSQL di seluruh klien secara realtime

## Shared Preferences
Shared Preferences adalah Membaca dan menulis sejumlah kecil data primitif sebagai pasangan kunci / nilai ke file pada penyimpanan perangkat

### Creating Shared Preferences
- Hanya perlu satu file Shared Preferences per aplikasi 
- Beri nama dengan nama paket aplikasi Anda —unik dan mudah dikaitkan dengan aplikasi
- Argumen MODE untuk getSharedPreferences() adalah untuk kompatibilitas mundur — gunakan hanya MODE_PRIVATE agar aman 

### Saving Shared Preferences
- SharedPreferences.Editor interface
- Menangani semua operasi file
- menempatkan metode overwrite jika key ada
- apply() menyimpan secara asinkron dan aman

### Restoring Shared Preferences
- Restore dalam onCreate() pada Activity
- Dapatkan metode mengambil dua argumen — key, dan nilai default jika key tidak dapat ditemukan
- Gunakan argumen default sehingga Anda tidak perlu menguji apakah preferensi ada dalam file

### Clearing
- Panggil clear() di SharedPreferences.Editor dan terapkan perubahan
- Anda dapat menggabungkan panggilan untuk menempatkan dan membersihkan. Namun, ketika Anda apply(), clear() selalu dilakukan terlebih dahulu, terlepas dari urutan

## SQLite Primer
### SQLite Database 
- Menyimpan data dalam tabel baris dan kolom (spreadsheet...)
- Field = intersection dari baris dan kolom
- Field berisi data, referensi ke field lain, atau referensi ke tabel lain
- Baris diidentifikasi oleh ID unik
- Nama kolom unik per tabel

## Room, LiveData, and ViewModel
### Architecture Components
Satu set Android libraries untuk penataan aplikasi Anda dengan cara yang kuat, dapat diuji, dan dapat dipertahankan.

### Room overview
- Room adalah pemetaan objek SQL. 
- Menghasilkan kode SQLite Android
- Menyediakan API sederhana untuk database Anda

Komponen dari Room : 
Entity => Mendefinisikan skema tabel database.
DAO => Database Access Object, mendefinisikan operasi read / write untuk database.
Database => Database holder. Digunakan untuk membuat atau menyambungkan ke database.

### LiveData
LiveData secara otomatis menjalankan kueri secara asinkron pada utas latar belakang bila diperlukan.

### ViewModel
ViewModel adalah objek yang menyediakan data untuk komponen UI dan bertahan dalam perubahan konfigurasi.