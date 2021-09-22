# Pertemuan 4 - ListView & RecyclerView
## ListView 
Dalam pengembangan Android, setiap kali ingin menampilkan daftar vertikal item yang dapat di-scroll, maka akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor.
Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengubah ArrayList objek menjadi Item Tampilan yang dimuat ke dalam container ListView.
Penggunaan ArrayAdapter sebagai berikut : 
ArrayAdapter<String> itemsAdapter = 
    new ArrayAdapter<String>(this, android.R.layout.simple_list_item_1, items);

ListView listView = findViewById(R.id.lvItems);
listView.setAdapter(itemsAdapter);

Kemudian untuk cara menggunakan custom ArrayAdapater terdapat beberapa poin sebagai berikut : 
1. Define the Model (Mendefinisikan model)
2. Create View Template (Membuat template tampilan)
3. Define the Adapter -> ArrayAdapter Inheritance (Mendefinisikan Adapter menjadi ArrayAdapter Inheritance)
4. Attaching the Adapter to a ListView (Melampirkan Adapter ke dalam ListView)
5. Populating Data into ListView (Mengisi kedalam ListView)

## RecycleView
RecyclerView adalah ViewGroup yang membuat tampilan berbasis adaptor dengan cara yang sama. Seharusnya menjadi penerus ListView dan GridView.

### LayoutManagers
RecyclerView menyediakan built-in layout managers :
1. LinearLayoutManager
2. GridLayoutManager
3. StaggeredGridLayoutManager

### Adapter
RecyclerView menyertakan jenis adaptor baru. Hal ini adalah pendekatan yang mirip dengan yang sudah digunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan. Kita harus meng-override 3 method dibawah :
1. onCreateViewHolder()
2. onBindViewHolder()
3. getItemCount()
