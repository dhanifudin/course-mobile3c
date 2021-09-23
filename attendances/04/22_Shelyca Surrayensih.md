# Pertemuan 4 - ListView & RecyclerView
Pada pertemuan minggu ke 4 kita membahas tentang ListView & RecyclerView
## ListView 
Dalam pengembangan Android ketika menampilkan daftar vertikal item yang dapat digulir menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor
Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.
## ArrayAdapter
![image](https://user-images.githubusercontent.com/70507995/134353843-47732528-2d0b-4e3a-9905-f855ad25732b.png)

## cara menggunakan Custom ArrayAdapter adalah:
- Mendefinisikan model
- Membuat tampilan templete
- Mendefinisikan Adapter -> ArrayAdapter Inheritance
- Memasangkan Adapter ke ListView
- Mengisi data ke ListView
## RecyclerView 
RecyclerView  adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
Setiap elemen individu dalam daftar ditentukan oleh objek view holder. menentukan view holder dengan memperluas RecyclerView.ViewHolder.
## LayoutManagers
RecyclerView menyediakan built-in layout managers:
- LinearLayoutManager -> menampilkan item dalam daftar gulir vertikal atau horizontal.
- GridLayoutManager -> menampilkan item dalam kotak.
- StaggeredGridLayoutManager -> menampilkan item dalam kisi terhuyung.
## Adapter
RecyclerView menyertakan jenis adaptor baru, pendekatan yang mirip dengan yang sudah digunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan. 
Kita harus meng-override 3 method dibawah :
- onCreateViewHolder()
- onBindViewHolder()
- getItemCount()
