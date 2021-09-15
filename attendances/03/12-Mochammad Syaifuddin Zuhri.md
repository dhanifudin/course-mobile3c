# RANGKUMAN MATERI PERTEMUAN 3

Pada pertemuan 3 ini membahas tentang Widget dan Navigation pada Android Studio.

- Widget adalah sebuah komponen yang dibuat untuk membangun tampilan UI dari sebuah aplikasi. Widget ini termasuk inheritent atau anak dari sebuah class.
  Terdapat banyak jenis widget yang ada di Android Studio, antara lain:
  - TextView
  - Buttton
  - ScrollView
  - ImageView
  - Dan lain sebagainya

  Pada umumnya hirarki User Interface (UI) ketika membuat aplikasi android adalah dibentuk dari kumpulan layouts dan widgets. Tampilan UI tersebut dibuat dengan menggunakan file .XML yang tersedia untuk bahasa pemrograman Java dan Kotlin.
  Ketika sudah membuat tampilan tersebut nantinya akan di proses untuk mengatur value dari sebuah widget maupun mengambil value dari sebuah widget dengan menggunakn method Setter dan Getter.
  
- Navigation adalah proses dalam perpindahan antara layar satu dengan layar laiinya pada sebuah aplikasi. 
  Dalam membuat navigation harus tahu arah tujuan dari layar selanjutnya. begitupun juga harus tahu berada di layar mana sebelum berpindah ke layar lain. 
  Navigation Component adalah sebuah library yang termasuk bagian dari Android Jetpack yang dibuat untuk mempermudah developer untuk membuat navigation antar Activity atau Fragment.
  Sebelumnya di dalam navigation sendiri ada 3 prinsip :
  - There’s always starting place yaitu Screen pertama yang dilihat user ketika pertama kali membuka sebuah app dan menjadi screen terakhir ketika user akan menutup sebuah app.
  - You can always Go back yaitu Screen yang kita buat harus memiliki fungsi back dari current destination ke start destinationnya.
  - Up goes back yaitu Up button harus memiliki fungsi back yang sama dengan system back button. Up button adalah tombol yang biasa kita lihat di pojok kiri atas sebuah app sedangkan system back button adalah tombol yang terdapat di pojok kanan bawah sebuah app atau handphone.
