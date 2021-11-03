# Rangkuman Minggu sepuluh Pemrograman Mobile

## Retrofit

Sebuah library Android untuk melakukan request ke sebuah endpoint REST API.

Untuk mengakses REST API di Android, masih sulit dengan membuat banyak worker dan thread menggunakan Async Task.

## Rest 

REpresentational State Transfer (REST) adalah sebuah gaya arsitektur perangkat lunak yang mendefinisikan batasan-batasan tertentu dalam membuat web services.

Terdiri dari method: GET, HEAD, POST, PUT, PATCH, DELETE, OPTIONS

REST memiliki 6 prinsip, yaitu client-server, stateless, cacheable, uniform interface, layered system, dan code on demand.

### prinsip REST

Client-server: prinsipnya adalah memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.

Stateless: tidak perlu session, hanya ada di sisi client.

Cacheable: respon/request dapat disimpan dan digunakan kembali.

Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.

Layered system: berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain.

Code on demand (optional): sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan.
