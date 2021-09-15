# Pertemuan 03

## Rangkuman Bab 3 Widget and Navigation

1. Widget adalah komponen utama untuk menyusun UI di android yang merupakan turunan dari view class. Untuk memanipulasi widget kita bisa mendefinisikan id pada XML. 

2. Dalam widget, terdapat set/get value diantaranya :
- EditText: Text etc
- ImageView: ImageResource etc
- RadioButton: Text, Checked
- CheckBox: Text, Checked
- Dan masih banyak lagi

3. Komponen navigasi digunakan untuk memanage navigasi antara fragment dengan layout. Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari user experience. Hal tersebut menetapkan dasar untuk user experience yang konsisten dan intuitif di seluruh aplikasi. Komponen Navigasi dirancang untuk menerapkan hal tersebut secara default, memastikan bahwa user/pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

4. Untuk menghendel fragment bisa menggunakan FragmentTransaction. Konsep dari fragment adalah menggunakan single page dan bisa di reply. Sedangkan activity, window nya ditumpuk-tumpuk. Selain itu, life cycle dari fragment lebih kompleks dari pada activity. Sekarang, kebanyakan konsep yang digunakan adalah 1 activity dengan multi fragment.

5. Pada komponen navigasi, jika perlu setup nya ditambah. Ada 2 cara untuk setup projek android :
- setup library bisa disisipkan di file bluild.gradle (module) di bagian dependencies 
- dengan menyisipkan private repository di file bluild.gradle (project) 

6. Destination adalah layar pertama yang dilihat pengguna saat mereka meluncurkan aplikasi dari launcher. Setiap aplikasi memiliki destination/tujuan awal yang tetap. Selain itu, destination juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke launcher setelah menekan tombol Kembali.

7. Pada grafik navigasi terdapat 2 komponen, yaitu :
- Destinations => area konten yang berbeda dalam aplikasi 
- Actions => koneksi logis antara destinations/tujuan yang mewakili jalur yang dapat diambil oleh user/pengguna

8. Pada Navigation Editor terdapat 3 bagian :
- Destinations panel => Mencantumkan host navigasi dan semua destinations/tujuan yang saat ini ada di Graph Editor.
- Graph Editor => Berisi representasi visual dari grafik navigasi. Kita dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
- Attributes => Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.

9. Salah satu bagian inti dari komponen Navigasi adalah host navigasi. Host navigasi merupakan wadah kosong tempat destinations/tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi. Host navigasi harus berasal dari NavHost.

10. Jika tertarik untuk mempelajari pemrograman mobile lebih luas, bisa explore di internet dengan keyword jetpack atau codelabs.