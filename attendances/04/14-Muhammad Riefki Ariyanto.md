<h2>Rangkuman Pertemuan minggu 04 Mobile<h2>    
<h4>RecyclerView</h4>

  RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
  Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.
  RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah Anda gunakan,
  tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan.

RecyclerView menyediakan pengelola tata letak bawaan ini:
- LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.
- GridLayoutManager menampilkan item dalam kotak.
- StaggeredGridLayoutManager menampilkan item dalam kisi terhuyung.

 <h4>ListView</h4>

  LisView yang memiliki data yang diisi menggunakan Adaptor
Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

<h4>Adapter</h4>
  RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah Anda gunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan.
Anda perlu mengganti tiga metode:
onCreateViewHolder()
diBindViewHolder()
getItemCount()
