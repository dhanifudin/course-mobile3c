# Pertemuan 07

## Progres Pengerjaan Mini Projek 1 

Progres pengerjaan mini projek saya dengan tema "KATALOG LIST PERUSAHAAN IT TERKEMUKA DI DUNIA" untuk minggu ini adalah :

1. Membuat NavBottom 
<br>Terdapat 2 menu pada NavBottom yaitu Home dan All List. Pada menu Home digunakan untuk menampilkan kategori perusahaan IT, sedangkan menu All List untuk menampilkan semua perusahaan tanpa dibedakan berdasarkan kategori.

2. Membuat Halaman Home
<br>Pada halaman home menampilkan 4 menu kategori perusahaan yaitu Media, Semikonduktor, Hardware & Tech.Device, Software & Layanan IT. Untuk halaman home, saya menggunakan fragment yang kemudian ditampilkan pada activity_main. Tampilan menu kategori dibuat dengan CardView yang kemudian tata letaknya menggunakan GridLayout 2:2.

3. Menambahkan RecyclerView pada menu All List
<br>Pada minggu sebelumnya, saya telah membuat tampilan RecyclerView yang mana setiap itemnya bisa diklik untuk menampilkan detail dari masing-masing itemnya. Kemudian saya pindahkan RecyclerView tersebut untuk ditampilkan pada menu All List. Untuk menu All List, saya menggunakan fragment seperti menu home yang kemudian cara menampilkannya melalui activity_main.

4. SetOnClickListener pada setiap kategori perusahaan
<br>Pada halaman home terdapat 4 menu kategori perusahaan. Pada setiap kategori diatur SetOnClickListener agar bisa diklik yang kemudian akan menampilkan list perusahaan berdasarkan masing-masing kategori.

5. Menambahkan RecyclerView untuk setiap kategori perusahaan
<br>RecyclerView ini akan tampil setelah meng-klik kategori perusahaan yang dipilih. pada activity.java juga diatur agar setiap item list perusahaan yang di-klik akan menampilkan halaman detail perusahaan.

6. Menambahkan menu toolbar pada halaman Detail Perusahaan
<br>menu toolbar ini digunakan untuk menampilkan biodata dari pendiri masing-masing perusahaan.

7. Menambahkan Activity untuk biodata pendiri perusahaan 
<br>Pada bagian ini, saya masih menambahkan Activity nya saja belum mengatur layout dan belum ada datanya.




