Pertemuan 10

TI3C - 17 - Octavia Alya Nabilla

Pada minggu ini membahas tentang Retrofit.

Reftrofit adalah sebuah library yang dapat digunakan di Android untuk membuat request ke
sebuah endpoint REST API. Library ini dikembangkan oleh sebuah perusahaan di Amerika bernama Square, Inc. (squareup.com).

Mengapa menggunakan Retrofit, karena pada android Untuk mengakses REST API di Android, masih sulit dengan membuat banyak worker dan thread menggunakan Async Task. membutuhkan akses dengan security yang baik. Membuat koneksi dengan Async Task tidak mudah. Maka lebih baik pekerjaan terkait networking dapat dibantu dengan library Retrofit.

Kemudian, ada REST. REpresentational State Transfer (REST) adalah sebuah gaya arsitektur perangkat lunak yang mendefinisikan batasan-batasan tertentu dalam membuat web services.
Dikenal pertama kali oleh seorang computer scientist dari Amerika bernama Roy Thomas Fielding dalam disertasinya pada tahun 2000 yang berjudul “Architectural Styles and the Design of Network-based Software Architecures”. Terdiri dari method: GET, HEAD, POST, PUT, PATCH, DELETE, OPTIONS.

Prinsip REST yaitu,
1. Client-server: memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.

2. Stateless: tidak perlu session, hanya ada di sisi client.

3. Cacheable: respon/request dapat disimpan dan digunakan kembali.

4. Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.

5. Layered system: berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain.

6. Code on demand (optional): sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan.






