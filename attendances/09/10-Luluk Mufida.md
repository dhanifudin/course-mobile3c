Rangkuman Mobile Pertemuan 9

Pada petemuan kali ini yang menjadi pembahasan utama yakni Data Storage adalah sebuah perangkat yang digunakan untuk menyimpan data atau informasi. 
Pada perangkat Android ,database yang digunakan adalah SQLite. Sqlite adalah sebuah software RDBMS(Relational Database Management System)  yang mendukung 
secara native (asli) untuk perangkat Android. Sqlite merupakan suatu sistem manajemen database ,yang mempunyai sifat ACID-compliant, yang diprogram dengan 
bahasa C, dan mempunyai  size atau ukuran memori yang relatif kecil. Karna Sqlite termasuk database engine yang embedded (tersemat),jadi perintah Sqlite  
yang bisa digunakan hanya perintah-perintah standar saja. Serta Sqlite hanya mendukung tipe data seperti NUMERIC, DATETIME,TEXT ,dan lain-lain. 

Jenis-Jenis Data Storage pada Android 
- Internal Storage : Menyimpan file atau data secara langsung, pada perangkat memori internal. File atau data akan disimpan pada memori internal secara private  pada Aplikasi, dan Aplikasi lain tidak dapat mengaksesnya termasuk juga untuk user (pengguna).  
- External Storage : File atau data akan disimpan pada memori external (seperti micro SD ) atau internal (non -removable) secara publik , serta dapat diakses dan dimodifikasi oleh user (pengguna).
- Shared preferences : Sebuah framework (kerangka) umum ,yang memungkinkan user (pengguna ) menyimpan data secara private , dalam bentuk key- value pairs (kunci nilai berpasangan ) dari tipe data primitif. Contoh tipe data primitif seperti :booleans, floats, ints, longs, and strings dll.
- Sqlite Database : File atau data akan disimpan terstruktur di database secara private.
- Network Connection :  File atau data akan diambil dari web , menggunakan jaringan server.
- Cloud Backup: penyimpanan data dilakukan dengan melakukan pencadangan data aplikasi dan pengguna di dalam Cloud
- Firebase Realtime Database: menyimpan dan mensinkronisasi data dengan basis data cloud NoSQL. Dengan menggunakan opsi ini, data disinkronisasi secara realtime di semua klien, sehingga meskipun aplikasi sedang mati, data tersebut akan tetap tersedia.
- Content Providers : Disiimpan secara pribadi dan sediakan untuk umum

Adapun hal lain yang dibahas saat petemuan yakni :
- Room digunakan untuk mempermudah Sqlite
- Sqlite lebih kompleks daripada room
- Perbedaan query di database mobile menggunakan sebuah variabel untuk penyimpanan
- Untuk membuat kolom konsep room menggunakan model
- Adapun komponen room yakni entity(model), DAO (digunakan untuk CRUD), database (berisi isi entity)
- Tidak akan ditemukan query sperti select dan lainnya pada room
- Untuk menuliskan query jangan lupa menambahkan @DAO
- Singleton untuk memastikan ada 1 instance yang terkoneksi dengan database
- Kelebihan memakai room adalah jika ada statement yang salah maka tidak di-compile (berbeda dengan sqlite yang tetap di compile), tidak menjalannkan main thread
- View model dibutuhkan untuk perubahan orientasi pada mobile agar tidak menggambil data ulang, jadi tidak perlu mengmabil ulang dari data set
- View model menyimpan data di UI, Data tersebut bisa dari room atau sumber lain seperti API
- Insert data dilakukan melalui repository
- Repository semacam layer yang digunakan insert dan update ke model
- Room akan men-generate live data ketika database mengalami update
- Setiap framework mempunyai pattern yang berbeda
