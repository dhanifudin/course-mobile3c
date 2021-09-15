# Rangkuman Minggu ketiga Pemrograman Mobile

## widget

Widget adalah komponen utama untuk membangun UI di Android
Widget mewarisi dari kelas View
Periksa palet di Android Studio untuk daftar Widget UI yang tersedia


User Interface (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget.
Anda perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin

Set/Get Value of Widget : It’s depends on Widget

- EditText: Text etc
- ImageView: ImageResource etc
- RadioButton: Text, Checked
- CheckBox: Text, Checked
- Etc
 - Tips: Gunakan konsep set/get

## Navigation Component

Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi

Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

Tujuan:

- Setiap aplikasi yang Anda buat memiliki tujuan awal yang tetap.
- Ini adalah layar pertama yang dilihat pengguna saat mereka meluncurkan aplikasi Anda dari peluncur.
- Tujuan ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

## NavHost

Salah satu bagian inti dari komponen Navigasi adalah host navigasi.
Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda.
Host navigasi harus berasal dari NavHost
