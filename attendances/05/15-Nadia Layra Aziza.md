# Pertemuan 05

## Rangkuman Bab 5 - Animasi dan Multimedia

## A. ANIMASI

Ada 5 macam animasi, diantaranya yaitu
1. Bitmap Animation
<br>Untuk menganimasikan grafik bitmap seperti ikon atau ilustrasi harus menggunakan API animasi yang dapat digambar. Biasanya, animasi ini didefinisikan secara statis dengan resource yang dapat digambar, tetapi juga dapat menentukan perilaku animasi saat runtime.

2. UI Visibility and Motion
<br>Saat mengubah visibilitas atau posisi tampilan dalam tata letak, harus menyertakan subtle animations (animasi halus) untuk membantu pengguna memahami bagaimana UI berubah. Kita dapat menggunakan property animation system yang disediakan oleh paket android.animation, tersedia di Android 3.0 (API level 11) dan yang lebih tinggi. 

3. Pyhsics Based Motion
<br>Animasi harus menerapkan real-world physics sehingga terlihat alami. Untuk menyediakan perilaku ini, library pendukung Android menyertakan API animasi berbasis physics yang mengandalkan hukum fisika untuk mengontrol bagaimana animasi terjadi.

4. Animate Layout changes
<br>Kita dapat menggunakan transition framework untuk membuat animasi menukar tata letak dalam activity atau fragment. Adapun fitur-fitur dalam transition framework diantaranya :

- Group-level animations: Menerapkan satu atau beberapa efek animasi ke semua tampilan dalam view hierarchy.
- Built-in animations: Menggunakan animasi standar untuk efek umum seperti fade out atau gerakan/movement.
- Resource file support: Memuat view hierarchies dan animasi bawaan dari file layout resource.
- Lifecycle callbacks: Menerima callbacks yang memberikan kontrol atas proses perubahan animasi dan hierarchy.

5. Animate Between Activity
<br>Animasi yang bertransisi di antara Activity. Ini didasarkan pada transition framework yang dijelaskan di atas untuk menganimasikan perubahan layout. Tetapi, Animate Between Activity ini memungkinkan kita membuat animasi di antara layout dalam activity terpisah.

## B. MULTIMEDIA

Framework multimedia android mencakup dukungan untuk memutar berbagai jenis media seperti audio, video, dan gambar ke dalam aplikasi kita. Berikut adalah class yang digunakan untuk memutar suara dan video dalam framework android :

- MediaPlayer : API utama untuk memutar suara dan video.
- AudioManager : mengelola sumber audio dan output audio pada perangkat.
- Internet Permission : Jika MediaPlayer digunakan untuk melakukan streaming konten berbasis jaringan.
- Wake Lock Permission : Jika aplikasi pemutar perlu menjaga layar agar tidak meredup atau menjaga prosesor agar tidak sleeping.

## C. FLUTTER

Pada pertemuan ini juga dijelaskan tentang Flutter. Salah satu kelebihan dari flutter adalah bisa membuat aplikasi multiplatform. Jika ingin membuat project Flutter menggunakan cmd, perintah nya adalah flutter create NameProject. Jika melalui VSCode sudah terdapat menu untuk me-generate project flutter. 

Susunan direktory flutter sedikit berbeda dengan android native. Jika pada flutter, kita akan sering melalukan edit pada bagian folder lib dan pubspec. Untuk mengembangkan app pada flutter, kita harus menginstall SDK dari flutter. Pengecekan instalasi dapat dilakukan dengan perintah flutter doctor. Konsep coding di flutter sedikit berbeda dengan android native, hampir sama dengan react dan vue. Bahasa pemrograman yang digunakan pada flutter adalah Dart, jika kita punya basic di bahasa javascript maka tidak terlalu sulit untuk memahami bahasa Dart. Pada file main.dart (file bawaan flutter) terdapat widget, setiap widget terdapat method build digunakan untuk merender/mengembalikan tampilan. Di flutter tidak ada pemisahan antara tampilan dan logic seperti pada android native, namun terdapat pemisahan pada komponen. Pada flutter, tampilan dan logic berada dalam satu file (komponen). Konsep dasar UI widget pada flutter berbentuk tree, terdapat container (sebagai root) yang berisi layout row dan setiap row terdapat column. kemudian di setiap column terdapat icon dan text. Pada flutter, satu widget hanya boleh diisi oleh satu widget child
