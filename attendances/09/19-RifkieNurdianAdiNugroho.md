Pertemuan 9

Jenis-Jenis Data Storage pada Android

Internal Storage : Menyimpan file atau data secara langsung, pada perangkat memori internal. File atau data akan disimpan pada memori internal secara private pada Aplikasi, dan Aplikasi lain tidak dapat mengaksesnya termasuk juga untuk user (pengguna).
External Storage : File atau data akan disimpan pada memori external (seperti micro SD ) atau internal (non -removable) secara publik , serta dapat diakses dan dimodifikasi oleh user (pengguna).
Shared preferences : Sebuah framework (kerangka) umum ,yang memungkinkan user (pengguna ) menyimpan data secara private , dalam bentuk key- value pairs (kunci nilai berpasangan ) dari tipe data primitif. Contoh tipe data primitif seperti :booleans, floats, ints, longs, and strings dll.
Sqlite Database : File atau data akan disimpan terstruktur di database secara private.
Network Connection : File atau data akan diambil dari web , menggunakan jaringan server.
Cloud Backup: penyimpanan data dilakukan dengan melakukan pencadangan data aplikasi dan pengguna di dalam Cloud
Firebase Realtime Database: menyimpan dan mensinkronisasi data dengan basis data cloud NoSQL. Dengan menggunakan opsi ini, data disinkronisasi secara realtime di semua klien, sehingga meskipun aplikasi sedang mati, data tersebut akan tetap tersedia.
Content Providers : Disiimpan secara pribadi dan sediakan untuk umum
Adapun hal lain yang dibahas saat petemuan yakni :

Room digunakan untuk mempermudah Sqlite
Sqlite lebih kompleks daripada room
Perbedaan query di database mobile menggunakan sebuah variabel untuk penyimpanan
Untuk membuat kolom konsep room menggunakan model
Adapun komponen room yakni entity(model), DAO (digunakan untuk CRUD), database (berisi isi entity)
Tidak akan ditemukan query sperti select dan lainnya pada room
Untuk menuliskan query jangan lupa menambahkan @DAO
Singleton untuk memastikan ada 1 instance yang terkoneksi dengan database
Kelebihan memakai room adalah jika ada statement yang salah maka tidak di-compile (berbeda dengan sqlite yang tetap di compile), tidak menjalannkan main thread
View model dibutuhkan untuk perubahan orientasi pada mobile agar tidak menggambil data ulang, jadi tidak perlu mengmabil ulang dari data set
View model menyimpan data di UI, Data tersebut bisa dari room atau sumber lain seperti API
Insert data dilakukan melalui repository
Repository semacam layer yang digunakan insert dan update ke model
Room akan men-generate live data ketika database mengalami update
Setiap framework mempunyai pattern yang berbeda

-Sqlite dipermudah dengan menggunakan room
-Perbedaan query di database mobile menggunakan sebuah variabel untuk penyimpanan
-Sqlite lebih kompleks daripada room
-Konsep room dengan menggunakan model untuk membuat kolom
-Database SQLite adalah solusi penyimpanan yang baik jika anda memiliki data terstruktur yang perlu diakses dan disimpan -secara persisten serta sering ditelusuri dan diubah
-Jika menggunakan database SQLite, yang dinyatakan sebagai objek SQLiteDatabase adalah semua interaksi dengan database adalah melalui instance dari kelas SQLiteOpenHelper yang akan mengeksekusi permintaan dan pengelolaan database.
-Komponenn room : entity(model), DAO (digunakan untuk CRUD), database (berisi isi entity)
-Room tidak akan ditemukan query sperti select dan lainnya
-Untuk menuliskan query jangan lupa menambahkan @DAO
-Singleton untuk memastikan ada 1 instance yang terkoneksi dengan database
-Kelebihan memakai room adalah jika ada statement yang salah maka tidak di-compile (berbeda dengan sqlite yang tetap di compile), tidak menjalannkan main thread
-View model dibutuhkan untuk perubahan orientasi pada mobile agar tidak menggambil data ulang, jadi tidak perlu mengmabil ulang dari data set
-View model menyimpan data di UI, Data tersebut bisa dari room atau sumber lain seperti API
Insert data dilakukan melalui repository
-Repository semacam layer yang digunakan insert, update ke model
-Room akan men-generate live data ketika database mengalami update
-Setiap framework mempunyai pattern yang berbeda
Materi : https://github.com/google-developer-training

GitHub
Google Developer Training

Google Developer Training has 32 repositories available. Follow their code on GitHub.
