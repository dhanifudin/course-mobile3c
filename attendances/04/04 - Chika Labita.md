<h1>Week 4 - Pemrograman Mobile</h1>

Topik Pembahasan minggu kali ini adalah List View,

Recycler View dan Pembahasan mengenai 

mini project untuk minggu ke 7 <br>

<h2>ListView</h2>

- List View illustration

   DataSource <-> Adapter <-> Adapter View

*DataSource : Cursor, ArrayList<br>

*Adapter View : list view, grid view, spinner<br>

*Adapter : parsing dari data ke tampilan.

<h2>RecyclerView</h2>

-> Merupakan tampilan dari dataset berisi kumpulan model.<br>

<br>

- Recycler View illustration

   LayoutManager -> Adapter -> Dataset<br>

<br>

- LayoutManager

1. LinearLayoutManager<br>

2. GridLayoutManager<br>

3. StaggeredGridLayoutManager<br>

<br>

Butuh 3 override methods:<br>

1. onCreateViewHolder()<br>

2. onBindViewHolder()<br>

3. getItemCount()<br>

<br>

<b>ViewHolder</b> digunakan hanya pada 1 class, digunakan untuk merepresentasikan tampilan.<br>

<br>

##Biasanya RecyclerView berpasangan dengan yang namanya CardView<br>

<br>

#Penggunaan halaman login : <br>

* Ketika terdapat data yang disimpan <br>

* Data penting yang bersifat rahasia. 

Selain dari itu, tidak perlu menggunakan 

halaman login.
