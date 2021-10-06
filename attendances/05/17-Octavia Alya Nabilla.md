Rangkuman Pertemuan 5 Pemrograman Mobile

TI3C - 17 - Octavia Alya Nabilla

Minggu ini materi yang disampaikan tentang animasi dan multimedia, dan juga cara penggunaan flutter dari dasar.

untuk flutter sendiri disampaikan dari proses penginstallan hingga membuat widget. 

Kemudian untuk materi yang dipelajari yaitu animasi dan multimedia.

Dalam animasi sendiri ada bermacam macam yaitu, Bitmap Animation, UI Visibility Motion, Physics Based Motion, Animated Layout changes, Animate Between Activity.

- Bitmap Animation = Saat Anda ingin menganimasikan grafik bitmap seperti ikon atau ilustrasi, Anda harus menggunakan API animasi yang dapat digambar. Biasanya, animasi ini didefinisikan secara statis dengan sumber daya yang dapat digambar, tetapi Anda juga dapat menentukan perilaku animasi saat runtime.

- UI Visibility Motion = Untuk mengubah visibilitas atau posisi tampilan dalam tata letak Anda, Anda harus menyertakan animasi halus untuk membantu pengguna memahami bagaimana UI berubah. Untuk memindahkan, mengungkapkan, atau menyembunyikan tampilan dalam tata letak saat ini, Anda dapat menggunakan sistem animasi properti yang disediakan oleh paket android.animation, tersedia di Android 3.0 (API level 11) dan yang lebih tinggi. 

- Physics Based Motion = Physics Based Motion didorong oleh gaya. Gaya pegas adalah salah satu gaya yang memandu interaktivitas dan gerak. Gaya pegas memiliki sifat-sifat sebagai berikut: redaman dan kekakuan. Dalam animasi berbasis pegas, nilai dan kecepatan dihitung berdasarkan gaya pegas yang diterapkan pada setiap frame. Maka, animasi Anda harus menerapkan fisika dunia nyata sehingga terlihat alami. 

- Animated Layout changes = Di Android 4.4 (API level 19) dan yang lebih tinggi, Anda dapat menggunakan kerangka kerja transisi untuk membuat animasi saat Anda menukar tata letak dalam aktivitas atau fragmen saat ini. Yang perlu Anda lakukan adalah menentukan tata letak awal dan akhir, dan jenis animasi apa yang ingin Anda gunakan. Kemudian sistem mencari tahu dan menjalankan animasi di antara dua tata letak. Anda dapat menggunakan ini untuk menukar seluruh UI atau untuk memindahkan/mengganti hanya beberapa tampilan. 

- Animate Between Activity = Di Android 5.0 (API level 21) dan yang lebih tinggi, Anda juga dapat membuat animasi yang bertransisi di antara aktivitas Anda. Ini didasarkan pada kerangka transisi yang sama yang dijelaskan di atas untuk menganimasikan perubahan tata letak, tetapi ini memungkinkan Anda membuat animasi di antara tata letak dalam aktivitas terpisah. Anda dapat menerapkan animasi sederhana seperti menggeser aktivitas baru dari samping atau memudarkannya, tetapi Anda juga dapat membuat animasi yang bertransisi antara tampilan bersama di setiap aktivitas. 

Kemudian untuk multimedia dalam MediaPlayer overviewnya kerangka kerja multimedia Android mencakup dukungan untuk memutar berbagai jenis media umum, sehingga Anda dapat dengan mudah mengintegrasikan audio, video, dan gambar ke dalam aplikasi Anda. Anda dapat memutar audio atau video dari file media yang disimpan di sumber daya aplikasi Anda (sumber daya mentah), dari file mandiri di sistem file, atau dari aliran data yang tiba melalui koneksi jaringan, semuanya menggunakan API MediaPlayer.

Kelas yang digunakan untuk memutar suara dan video dalam kerangka kerja Android:
1. Izin Internet - Jika Anda menggunakan MediaPlayer untuk mengalirkan konten berbasis jaringan, aplikasi Anda harus meminta akses jaringan.
2. Izin Penguncian Bangun - Jika aplikasi pemutar Anda perlu menjaga layar agar tidak meredup atau prosesor tidak tidur, atau menggunakan metode MediaPlayer.setScreenOnWhilePlaying() atau MediaPlayer.setWakeMode(), Anda harus meminta izin ini.

