# Rangkuman Pertemuan 4-Mobile

## List View & Recycle View

Pada pertemuan minggu ini akan dibahas tentang view (tampilan) untuk pengolahan data, yaitu List View dan Recycle View

### List View

ListView digunakan untuk menampilkan daftar vertikal item yang dapat di-scroll dalam pengembangan aplikasi berbasis android.
ListView yang digunakan adalah ListView yang memiliki data yang diisi menggunakan Adaptor.
Adaptor yang paling sederhana untuk digunakan adalah ArrayAdapter karena dapat mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

### Recycle View
RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa.
Ini seharusnya menjadi penerus dari ListView dan GridView. Setiap elemen individu dalam daftar ditentukan oleh objek view holder.
Menentukan view holder dengan memperluas RecyclerView.ViewHolder.
RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor.
Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.

Dosen mendemokan bagaimana cara menerapkan Recycle View pada Android Studio. Penggunaan Recycle View harus diatur dalam file java dan resource (xml).

Untuk mengatur tampilan list, diperlukan file xml lagi untuk mengatur tampilan per item.
sedangkan untuk mengatur konfigurasi adapter agar item muncul terletak pada file java nya. 
