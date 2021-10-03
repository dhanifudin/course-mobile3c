# Rangkuman Minggu kelima Pemrograman Mobile

## Bitmap Animation
- Saat kita ingin menganimasikan grafik bitmap seperti ikon atau ilustrasi, kita harus menggunakan API animasi yang dapat digambar. Biasanya, animasi ini didefinisikan secara statis dengan sumber daya yang dapat digambar, tetapi kita juga dapat menentukan perilaku animasi saat runtime.
Misalnya, menganimasikan tombol putar yang berubah menjadi tombol jeda saat diketuk adalah cara yang bagus untuk mengomunikasikan kepada pengguna bahwa kedua tindakan tersebut terkait, dan menekan yang satu membuat yang lain terlihat.
- Salah satu cara untuk menganimasikan Drawable adalah memuat serangkaian sumber daya Drawable satu demi satu untuk membuat animasi. Ini adalah animasi tradisional dalam arti dibuat dengan urutan gambar yang berbeda, diputar secara berurutan, seperti gulungan film. Kelas AnimationDrawable adalah dasar untuk animasi Drawable.
- Meskipun kita dapat menentukan bingkai animasi dalam kode kita, menggunakan API kelas AnimationDrawable, ini lebih mudah dilakukan dengan satu file XML yang mencantumkan bingkai yang menyusun animasi. File XML untuk jenis animasi ini berada di direktori res/drawable/ dari proyek Android kita. Dalam hal ini, instruksinya adalah urutan dan durasi untuk setiap frame animasi.

## Animate UI visibility and motion
Saat kita perlu mengubah visibilitas atau posisi tampilan di tata letak, kita harus menyertakan animasi halus untuk membantu pengguna memahami bagaimana UI berubah.
Untuk memindahkan, mengungkapkan, atau menyembunyikan tampilan dalam tata letak saat ini, kita dapat menggunakan sistem animasi properti yang disediakan oleh paket android.animation, tersedia di Android 3.0 (API level 11) dan yang lebih tinggi. API ini memperbarui properti objek Tampilan kita selama periode waktu tertentu, terus menggambar ulang tampilan saat properti berubah. Misalnya, saat kita mengubah properti posisi, tampilan bergerak melintasi layar, atau saat kita mengubah properti alfa, tampilan memudar masuk atau keluar.
Untuk membuat animasi ini dengan sedikit usaha, kita dapat mengaktifkan animasi pada tata letak kita sehingga ketika kita hanya mengubah visibilitas tampilan, animasi berlaku secara otomatis. Untuk informasi selengkapnya, lihat Pembaruan Tata Letak Animasi Otomatis.
Saat aplikasi kita digunakan, informasi baru perlu ditampilkan di layar saat informasi lama dihapus. Segera beralih apa yang ditampilkan dapat terlihat menggelegar atau pengguna dapat dengan mudah melewatkan konten baru di layar. Memanfaatkan animasi dapat memperlambat perubahan dan menarik perhatian pengguna dengan gagasan sehingga pembaruan lebih jelas.
Ada tiga animasi umum yang digunakan saat menampilkan atau menyembunyikan tampilan. kita dapat menggunakan animasi pengungkapan melingkar, animasi crossfade, atau animasi cardflip.

## Physics-based motion
Bila memungkinkan, animasi kita harus menerapkan fisika dunia nyata sehingga terlihat alami. Misalnya, mereka harus menjaga momentum ketika target mereka berubah, dan membuat transisi yang mulus selama perubahan apa pun.
Untuk menyediakan perilaku ini, pustaka Dukungan Android menyertakan API animasi berbasis fisika yang mengkitalkan hukum fisika untuk mengontrol bagaimana animasi kita terjadi.

## Animate layout changes
- Di Android 4.4 (API level 19) dan yang lebih tinggi, kita dapat menggunakan kerangka kerja transisi untuk membuat animasi saat kita menukar tata letak dalam aktivitas atau fragmen saat ini. Yang perlu kita lakukan adalah menentukan tata letak awal dan akhir, dan jenis animasi apa yang ingin kita gunakan. Kemudian sistem mencari tahu dan menjalankan animasi di antara dua tata letak. kita dapat menggunakan ini untuk menukar seluruh UI atau untuk memindahkan/mengganti hanya beberapa tampilan.
Misalnya, saat pengguna mengetuk item untuk melihat informasi selengkapnya, kita dapat mengganti tata letak dengan detail item, menerapkan transisi.

## Materi Animate between activities
- Di Android 5.0 (API level 21) dan yang lebih tinggi, kita juga dapat membuat animasi yang bertransisi di antara aktivitas kita. Ini didasarkan pada kerangka transisi yang sama yang dijelaskan di atas untuk menganimasikan perubahan tata letak, tetapi ini memungkinkan kita membuat animasi di antara tata letak dalam aktivitas terpisah.
kita dapat menerapkan animasi sederhana seperti menggeser aktivitas baru dari samping atau memudarkannya, tetapi kita juga dapat membuat animasi yang bertransisi antara tampilan bersama di setiap aktivitas. Misalnya, saat pengguna mengetuk item untuk melihat informasi lebih lanjut, kita dapat beralih ke aktivitas baru dengan animasi yang menumbuhkan item tersebut dengan mulus untuk memenuhi layar. 

## Multimedia
Kerangka kerja multimedia Android mencakup dukungan untuk memutar berbagai jenis media umum, sehingga kita dapat dengan mudah mengintegrasikan audio, video, dan gambar ke dalam aplikasi kita. kita dapat memutar audio atau video dari file media yang disimpan di sumber daya aplikasi kita (sumber daya mentah), dari file mandiri di sistem file, atau dari aliran data yang tiba melalui koneksi jaringan, semuanya menggunakan API MediaPlayer.
Dokumen ini menunjukkan kepada kita cara menggunakan MediaPlayer untuk menulis aplikasi pemutar media yang berinteraksi dengan pengguna dan sistem untuk mendapatkan kinerja yang baik dan pengalaman pengguna yang menyenangkan. Atau, kita mungkin ingin menggunakan ExoPlayer, yang merupakan pustaka sumber terbuka yang dapat disesuaikan yang mendukung fitur berkinerja tinggi yang tidak tersedia di MediaPlayer