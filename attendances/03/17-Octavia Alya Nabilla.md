Rangkuman Pertemuan 3 Mobile

TI3C-17-Octavia Alya Nabilla

Hari ini mempelajari tentang Widget dan Navigation. Widget adalah komponen utama untuk membangun UI di Android.
Widget mewarisi dari kelas View. The user interface (UI) untuk aplikasi Android dibangun sebagai hierarki layout dan widget.
Kita perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin.

Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi.
Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

Navigation Graph :
1. Destination adalah area konten yang berbeda di aplikasi Anda.
2. Actions adalah koneksi logis antara tujuan Anda yang mewakili jalur yang dapat diambil pengguna.

Navigation Editor  :
1. Destination Panel mencantumkan host navigasi Anda dan semua tujuan yang saat ini ada di Editor Grafik.
2. Graph Editor berisi representasi visual dari grafik navigasi Anda. Anda dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
3. Attributes menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.

Salah satu bagian inti dari komponen Navigasi adalah host navigasi. Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi. Host navigasi harus berasal dari NavHost.