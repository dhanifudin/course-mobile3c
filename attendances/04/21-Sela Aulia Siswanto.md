<h1>Rangkuman Minggu-04</h1>
<h2>ListView dan RecyclerView</h2>
List View dan Recycler view adalah dua model tampilan pengolahan data pada android. Perbedaan dari kedua tampilan tersebut adalah seperti berikut ini:

- List View

List view menampilkan daftar vertikal item yang dapat digulir dan memiliki data yang diisi menggunakan adaptor. Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

- Recycler View

RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView. Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Menentukan view holder dengan memperluas RecyclerView.ViewHolder. RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.

Manajer tata letak berfungsi uutk mengatur elemen individu dalam daftar. Dalam menggunakan pengelolah tata letak dapat menggunakan pustaka RecyclerView atau menentukan sendiri. Manajer tata letak semuanya pada kelas abstrak LayoutManager perpustakaan. RecyclerView menyediakan pengolahan tata letak bawaan seperti berikut:

a. LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.

b. GridLayoutManager menampilkan item dalam kotak.

c. StaggeredGridLayoutManager menampilkan item dalam kisi terhuyung.