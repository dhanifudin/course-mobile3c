# Pertemuan 04

## Rangkuman Bab 4 ListView & RecyclerView

Pada pertemuan 4, mempelajari tentang cara menampilkan tampilan bentuk list menggunakan ListView dan RecyclerView.

## A. ListView

ListView digunakan untuk menampilkan daftar vertikal item yang dapat di-scroll dalam pengembangan aplikasi berbasis android. ListView yang digunakan adalah ListView yang memiliki data yang diisi menggunakan Adaptor.

Adaptor yang paling sederhana untuk digunakan adalah ArrayAdapter karena dapat mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView. Cara menggunakan ArrayAdapter seperti contoh potongan source code berikut :

ArrayAdapter<String> itemsAdapter = 

    new ArrayAdapter<String>(this, android.R.layout.simple_list_item_1, items);

ListView listView = findViewById(R.id.lvItems);

listView.setAdapter(itemsAdapter);

Sedangkan cara menggunakan Custom ArrayAdapter adalah
- Mendefinisikan model
- Membuat tampilan templete
- Mendefinisikan Adapter -> ArrayAdapter Inheritance
- Memasangkan Adapter ke ListView
- Mengisi data ke ListView

## B. RecyclerView

RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Ini merupakan penerus dari ListView dan GridView.

Setiap elemen dalam list ditentukan oleh objek view holder. Kita bisa menentukan view holder dengan cara meng-extend RecyclerView.ViewHolder.

Layout manager mengatur tiap elemen dalam list kita. Kita dapat menggunakan salah satu layout manager yang disediakan oleh library RecyclerView, atau kita juga dapat menentukan sendiri. Layout manager semuanya didasarkan pada abstract class library LayoutManager.

RecyclerView menyediakan Layout Manager bawaan, diantaranya yaitu :
- LinearLayoutManager -> menampilkan item dalam vertical maupun horizontal scrolling list
- GridLayoutManager -> menampilkan item dalam grid
- StaggeredGridLayoutManager -> menampilkan item dalam staggered grid

Pada RecyclerView juga menyertakan jenis Adapter baru. pendekatannya mirip dengan yang sebelumnya, tetapi dengan beberapa ciri khas seperti ViewHolder yang diperlukan.
Kita butuh untuk override 3 method, diantaranya yaitu :
- onCreateViewHolder()
- onBindViewHolder()
- getItemCount()

Untuk setup RecyclerView, kita juga dapat menarik widget RecyclerView dari UI Editor secara langsung. 

Note : Performa antara ListView & RecyclerView sebenarnya lebih efektif RecyclerView jika data yang akan ditampilkan banyak. Namun, jika data yang ditampilkan sedikit, menggunakan ListView sudah cukup.
