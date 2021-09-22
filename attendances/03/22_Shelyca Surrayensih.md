# Pertemuan ke 3(Widget and Navigation)

## pada pertemuan ketiga kita mempelajari tentang Widget and Navigation 
## Widget and Navigation

Widget adalah komponen utama untuk membuat UI di Android yang merupakan warisan dari kelas View dan Periksa palet di Android Studio untuk daftar Widget UI yang tersedia

User Interface (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget.kita perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin

## Set/Get Value of Widget
- EditText: Text etc
- ImageView: ImageResource etc
- RadioButton: Text, Checked
- CheckBox: Text, Checked

## Navigation Component
Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna, Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default.

## Tujuan:
- Setiap aplikasi yang kamu buat memiliki tujuan awal yang tetap
- Ini adalah layar pertama yang dilihat pengguna saat mereka meluncurkan aplikasi Anda dari peluncur.
- Tujuan ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

Navigation Graph bertujuan untuk area konten yang berbeda di aplikasi

Actions adalah koneksi logis antara tujuan yang mewakili jalur yang dapat diambil pengguna

## Navigation Editor terdapat 3 bagian yaitu:
- Destinations panel: Mencantumkan host navigasi dan semua destinations/tujuan yang saat ini ada di Graph Editor.
- Graph Editor: Berisi representasi visual dari grafik navigasi. Kita dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
- Attributes: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.

Salah satu bagian inti dari komponen Navigasi adalah host navigasi,Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda.
Host navigasi harus berasal dari NavHost.
