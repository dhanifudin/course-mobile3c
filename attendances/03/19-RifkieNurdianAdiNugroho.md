Rangkuman Pertemuan 3 Mobile

TI3C-19-Rifkie Nurdian AdiNugroho

Widget adalah komponen utama untuk membangun UI di Android.
Widget mewarisi dari kelas View. The user interface (UI) untuk aplikasi Android dibangun sebagai hierarki layout dan widget.

Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi.
Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

Navigation Graph adalah :

-Destination adalah area konten yang berbeda di aplikasi Anda.
-Actions adalah koneksi logis antara tujuan Anda yang mewakili jalur yang dapat diambil pengguna.

Navigation Editor adalah :

-Destination Panel mencantumkan host navigasi Anda dan semua tujuan yang saat ini ada di Editor Grafik.
-Graph Editor berisi representasi visual dari grafik navigasi Anda. Anda dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
-Attributes menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.

Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi. Host navigasi harus berasal dari NavHost.
