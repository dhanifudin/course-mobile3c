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
-> Merupakan tampilan dari dataset berisi kumpulan model. RecyclerView juga memudahkan untuk menampilkan kumpulan data dalam jumlah besar secara efisien. <br>

<br>
- Recycler View illustration
   LayoutManager -> Adapter -> Dataset<br>
<br>
- LayoutManager
1. LinearLayoutManager : menyusun item dalam daftar satu dimensi.<br>
2. GridLayoutManager : menyusun semua item dalam petak dua dimensi yaitu vertical dan horizontal<br>
3. StaggeredGridLayoutManager : hampir mirip dengan GridLayoutManager -> baris atau kolom dapat saling mengimbangi.<br>
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
#Penggunaan halaman login yaitu ketika terdapat data yang disimpan, kemudian data penting yang bersifat rahasia, individu.
Selain dari kondisi tersebut, tidak perlu menggunakan halaman login.
