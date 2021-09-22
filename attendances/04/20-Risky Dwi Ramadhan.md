## Ragkuman Pertemuan 04
Pada minggu ini membahas tentang ListView dan RecyclerView
# ListView
ListView adalah user interface pada Android yang menampilkan item-item dari sekumpulan daftar yang tersusun berbaris ke bawah atau ke samping dengan 
tampilan yang dapat scroll. ListView menampilkan item-item dari suatu Array atau List atau Query Database yang dijadikan data model sebagai item dari ListView.

# RecyclerView
RecyclerView adalah ViewGroup yang berisi tampilan yang sesuai dengan data Anda. ViewGroup sendiri juga merupakan tampilan, 
jadi Anda menambahkan RecyclerView ke tata letak dengan cara yang sama seperti menambahkan elemen UI lainnya.

  Pada listview dan recyclerview juga terdapat adapter. Adapter adalah class yang mengatur item-item pada ListView. Adapter mengatur resource view pada setiap item dari ListView. 
Resource view pada ListView yang ada pada sebuah tampilan layar sebuah aplikasi memiliki jumlah resource view yang tetap sesuai dengan item yang tampak pada layar. 
Pada ListView dengan tampilan scroll, resourve view akan digunakan secara berulang (reusable) dengan mengatur item yang tampak dan yang tersembunyi pada ListView. 
Adapter juga mengatur data model dari setiap item ListView. Sebuah data model akan diatur menjadi sebuah item dari ListView. 
