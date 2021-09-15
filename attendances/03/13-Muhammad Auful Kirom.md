# PERTEMUAN 3 | Widget and Navigation

> Rangkuman Bahasan
1. Widget : <br>
    - Merupakan komponen utama dalam membangun sebuah UI (User Interface) di android
    - merupakan inheritance (keturunan) dari kelas View

2. Hirarki UI (User Interface) : <br>
    - Tampilan aplikasi android dibangun atas hirarki (susunan) dari layout dan widget
    - widget bisa dimanipulasi dengan java, dengan cara mendefinisikan idnya di XML

3. Komponen Navigasi : <br>
    - Navigation Graph : <br>
        Sebuah resource XML yang mengandung semua navigasi dan informasi yang terkait dalam satu lokasi pusat.
    - NavHost : <br>
        Container kosong yang akan menunjukkan destinasi dari navigation graph. Dalam komponen navigasi terdapat default NavHost implementation, NavHostFragment, yang menunjukkan fragmen tujuan
    - NavController : <br>
        Pengatur navigasi dengan NavHost.

4. Perbedaan antara Fragmen dan Activity : <br>
    Activity biasanya berupa stack (tumpukan) yang mana jika ingin pindah ke navigasi tertentu maka akan sedikit sulit, sedangkan jika dengan fragmen maka bisa langsung di <i>replace</i> dengan navigasi yang dituju.

5. Destination : <br>
    Setiap aplikasi yang dibuat pasti memiliki sebuah destination tetap, dan itu merupakan layar pertama ketika dibuka oleh user, dan juga merupakan layar terakhir yang dilihat oleh user.
