# Pertemuan 5 | Animasi dan Multimedia
## ANIMASI
Animasi terbagi menjadi lima macam yaitu:
1. Bitmap Animation
Untuk menganimasikan grafik bitmap seperti ikon atau ilustrasi, menggunakan API animasi yang dapat digambar. didefinisikannya secara statis dengan sumber daya yang dapat digambar, tetapi juga dapat menentukan perilaku animasi saat runtime.Misalnya, menganimasikan tombol putar yang berubah menjadi tombol jeda saat diketuk adalah cara yang bagus untuk mengomunikasikan kepada pengguna bahwa kedua tindakan tersebut terkait, dan menekan yang satu membuat yang lain terlihat.
2. UI Visibility and Motion
Untuk mengubah visibilitas atau posisi tampilan dalam tata letak Anda, Anda harus menyertakan subtle animations (animasi halus) untuk membantu pengguna memahami bagaimana UI berubah.
3. Pyhsics Based Motion
Animasi harus menerapkan real-world physics sehingga terlihat alami. 
4. Animate Layout changes
Di Android 4.4 (API level 19) dan yang lebih tinggi, dapat menggunakan kerangka kerja transisi untuk membuat animasi saat menukar tata letak dalam aktivitas atau fragmen saat ini. Yang perlu di lakukan adalah menentukan tata letak awal dan akhir, dan jenis animasi apa yang ingin Anda gunakan. Kemudian sistem mencari tahu dan menjalankan animasi di antara dua tata letak. Anda dapat menggunakan ini untuk menukar seluruh UI atau untuk memindahkan/mengganti hanya beberapa tampilan.
Kita dapat menggunakan transition framework untuk membuat animasi menukar tata letak dalam activity atau fragment. Adapun fitur-fitur dalam transition framework diantaranya :
- Group-level animations
- Built-in animations
- Resource file support
- ifecycle callbacks
5. Animate Between Activity
Animasi yang bertransisi di antara Activity. Ini didasarkan pada transition framework yang dijelaskan di atas untuk menganimasikan perubahan layout. Tetapi, Animate Between Activity ini memungkinkan kita membuat animasi di antara layout dalam activity terpisah.
## Multimedia
Kerangka kerja multimedia Android mencakup dukungan untuk memutar berbagai jenis media umum, sehingga mudah mengintegrasikan audio, video, dan gambar ke dalam aplikasi. 
Berikut Kelas digunakan untuk memutar suara dan video dalam kerangka kerja Android:
-	MediaPlayer Kelas ini adalah API utama untuk memutar suara dan video.
-	AudioManager Kelas ini mengelola sumber audio dan output audio pada perangkat.
-	Izin Internet  ketika menggunakan MediaPlayer untuk mengalirkan konten berbasis jaringan, aplikasi Anda harus meminta akses jaringan.
-	Izin Penguncian Bangun ketika aplikasi pemutar perlu menjaga layar agar tidak meredup atau prosesor tidak tidur, atau menggunakan metode MediaPlayer.setScreenOnWhilePlaying() atau MediaPlayer.setWakeMode(),harus meminta izin ini.
