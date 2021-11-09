Pertemuan 10
Retrofit
Retrofit adalah sebuah library Android untuk melakukan request ke sebuah endpoint REST API.Library ini dikembangkan oleh sebuah perusahaan di Amerika bernama Square, Library ini juga bersifat Open Source, sehingga kode-kodenya bebas diakses di GitHub. Minimal menggunakan Java 8+ atau Android 5.0 API 21+ (Lollipop).

Rest
Representational State Transfer (REST) adalah sebuah gaya arsitektur perangkat lunak yang mendefinisikan batasan-batasan tertentu dalam membuat web services. Terdiri dari method: GET, HEAD, POST, PUT, PATCH, DELETE, OPTIONS. Memiliki 6 prinsip, yaitu

Client-server memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.
Stateless memiliki prinsip tidak perlu session, hanya ada di sisi client.
Cacheable bersifat respon/request dapat disimpan dan digunakan kembali.
Uniform interface memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.
Layered system berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain.
Code on demand (optional) sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan.

prinsip REST
Client-server: prinsipnya adalah memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data.

Stateless: tidak perlu session, hanya ada di sisi client.

Cacheable: respon/request dapat disimpan dan digunakan kembali.

Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum.

Layered system: berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain.

Code on demand (optional): sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan.
