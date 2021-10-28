# RANGKUMAN PERTEMUAN MINGGU KE-5

### Animasi 

- Bitmap Animation
Saat Anda ingin menganimasikan grafik bitmap seperti ikon atau ilustrasi, Anda harus menggunakan API animasi yang dapat digambar. Biasanya, animasi ini didefinisikan secara statis dengan sumber daya yang dapat digambar, tetapi Anda juga dapat menentukan perilaku animasi saat runtime.
Misalnya, menganimasikan tombol putar yang berubah menjadi tombol jeda saat diketuk adalah cara yang bagus untuk mengomunikasikan kepada pengguna bahwa kedua tindakan tersebut terkait, dan menekan yang satu membuat yang lain terlihat.

- UI visibility and motion
Saat Anda perlu mengubah visibilitas atau posisi tampilan dalam tata letak Anda, Anda harus menyertakan animasi halus untuk membantu pengguna memahami bagaimana UI berubah.
Untuk memindahkan, mengungkapkan, atau menyembunyikan tampilan dalam tata letak saat ini, Anda dapat menggunakan sistem animasi properti yang disediakan oleh paket android.animation, tersedia di Android 3.0 (API level 11) dan yang lebih tinggi

- PAnimate layout changes
Di Android 4.4 (API level 19) dan yang lebih tinggi, Anda dapat menggunakan kerangka kerja transisi untuk membuat animasi saat Anda menukar tata letak dalam aktivitas atau fragmen saat ini. Yang perlu Anda lakukan adalah menentukan tata letak awal dan akhir, dan jenis animasi apa yang ingin Anda gunakan. Kemudian sistem mencari tahu dan menjalankan
animasi di antara kedua tata letak. Anda dapat menggunakan ini untuk menukar seluruh UI atau untuk memindahkan/mengganti hanya beberapa tampilan.

### Multimedia

- MediaPlayer overview
Kerangka kerja multimedia Android mencakup dukungan untuk memutar berbagai jenis media umum, sehingga Anda dapat dengan mudah mengintegrasikan audio, video, dan gambar ke dalam aplikasi Anda. Anda dapat memutar audio atau video dari file media yang disimpan di sumber daya aplikasi
Anda (sumber daya mentah), dari file mandiri di sistem file, atau dari aliran data yang tiba melalui koneksi jaringan, semuanya menggunakan API MediaPlayer.
