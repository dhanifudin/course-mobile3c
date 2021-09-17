# Rangkuman Pembahasan Pertemuan 3

Membahas tentang widget dan navigation pada android.

1. Widget adalah sebuah “perwakilan” dari aplikasi yang memungkinkan pengguna untuk dapat menggunakan fitur dari aplikasi yang diwakilkan tersebut secara langsung tanpa harus membuka aplikasi “sesungguhnya”. Biasanya widget terletak pada home screen atau tampilan awal layar perangkat Android anda.
  
  Contoh widget pada android studio, seperti berikut:
  - ImageView.
  - TextView.
  - Button.
  - Spinner.
  - CheckBox.
2. Navigasi adalah interaksi yang memungkinkan pengguna melihat-lihat, masuk, dan keluar dari berbagai konten dalam aplikasi Anda. Komponen Navigasi Android Jetpack membantu Anda menerapkan navigasi, mulai dari klik tombol sederhana hingga pola yang lebih kompleks, seperti bilah aplikasi dan panel samping navigasi.

Komponen Navigasi terdiri dari tiga bagian utama yang dijelaskan di bawah:

- Grafik navigasi: Sumber daya XML yang berisi semua informasi terkait navigasi di satu lokasi terpusat. Ini mencakup semua area konten individual dalam aplikasi Anda, yang disebut tujuan, serta jalur yang mungkin dilalui oleh pengguna pada aplikasi Anda.
- NavHost: Container kosong yang menampilkan tujuan dari grafik navigasi Anda. Komponen Navigasi berisi implementasi NavHost default, NavHostFragment, yang menampilkan tujuan fragmen.
- NavController: Objek yang mengelola navigasi aplikasi dalam sebuah NavHost. NavController mengatur pertukaran konten tujuan di NavHost saat pengguna menggunakan aplikasi Anda.
