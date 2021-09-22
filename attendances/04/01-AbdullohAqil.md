Pertemuan 4

mempelajari tentang cara menampilkan tampilan bentuk list menggunakan ListView dan RecyclerView. 

Recycle view 

recycle view merupakan ui pada android yang juga menampilkan data sama seperti list view namun berbeda dengan list view, recyclee view merupakan versi terbaru dari metode penampilana data dan juga lebih kompleks dari list view yang merupakan metode penampilan data yang lama

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


