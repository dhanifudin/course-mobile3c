dalam perkuliahan hari ini kita membahas tentang List View dan Recycle View

Dalam pengembangan Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan ListView yang memiliki data yang diisi menggunakan Adaptor. Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Dan seharusnya menjadi penerus ListView dan GridView.

Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Menentukan view holder dengan memperluas RecyclerVie
kita di anjurkan harus memahami proses pemodelan dan penampilan data

RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.

Manajer tata letak mengatur elemen individual dalam daftar Anda. Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri. Manajer tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan.

LayoutManager RecyclerView menyediakan pengelola tata letak bawaan ini:

LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.
GridLayoutManager menampilkan item dalam kotak.
StaggeredGridLayoutManager menampilkan item dalam Staggered grid.
Adapter RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah digunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan.
