# Pertemuan 4 | Mobile

> Rangkuman

### ListView

ListView adalah UI pada Android yang menampilkan item-item dari sekumpulan daftar yang tersusun berbaris ke bawah atau ke samping dengan tampilan yang dapat scroll. ListView menampilkan item-item dari suatu Array atau List atau Query Database yang dijadikan data model sebagai item dari ListView.


### RecyclerView

RecyclerView adalah ViewGroup yang berisi tampilan yang sesuai dengan data. ViewGroup sendiri juga merupakan tampilan yang menambahkan RecyclerView ke tata letak dengan cara yang sama seperti menambahkan elemen UI lainnya.

### Adapter

Adapter adalah class yang mengatur item-item pada ListView ataupun RecycleView. Adapter mengatur resource view pada setiap item. Resource view yang ada pada sebuah tampilan layar sebuah aplikasi memiliki jumlah resource view yang tetap sesuai dengan item yang tampak pada layar. 

dibutuhkan override 3 method : 
- onCreateViewHolder()
- onBindViewHolder()
- getItemCount()

### LayoutManager

Terdapat beberapa layout manager built-in yang tersedia : 

- LinearLayoutManager : 
    Menampilkan item secara vertikal atau horizontal
- GridLayoutManager : 
    menampilkan item dengan grid
- StaggeredGridLayoutManager


