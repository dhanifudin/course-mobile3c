# Ragkuman Pertemuan 03
  Pada pertemuan minggu ketiga kali ini membahas tentang widget dan navigation pada sebuah pemrograman mobile. Widget adalah komponen utama untuk menyusun UI di android yang merupakan turunan dari class view. Widget ini dapat dibuat atau dimanipulasi pada file .xml.<br>
Dalam widget terdapat beberapa komponen , antara lain:<br>
  - EditText: Text etc
  - ImageView: ImageResource etc
  - RadioButton: Text, Checked
  - CheckBox: Text, Checked
  - Dan lain-lain.<br>
  
Navigation adalah proses perpindahan antara layar satu ke layar lainnya pada suatu aplikasi. 
Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi. <br>

Destination adalah layar pertama yang dilihat oleh user/pengguna saat mereka pertama kali membuka aplikasi dari launcher. 
Setiap aplikasi memiliki destination awal yang tetap. Selain itu, destination  ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

Ada 2 komponen penting dalam Navigation Graph, yaitu:
- Destination adalah area konten yang berbeda di aplikasi anda.
- Actions adalah koneksi logis antara tujuan Anda yang mewakili jalur yang dapat diambil pengguna.

Ada 3 bagian pada Navigation Editor, yaitu:
- Destinations panel: Mencantumkan host navigasi Anda dan semua tujuan yang saat ini ada di Editor Grafik.
- Graph Editor: Berisi representasi visual dari grafik navigasi Anda. Anda dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
- Attributes: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.
