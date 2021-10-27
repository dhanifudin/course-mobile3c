<h1> Week 9 - Preferences, Setting && Storing Data with Room</h1> 

Point : 
- SQLite Database -> menggunakan RDBMS
- Content Provider paling umum digunakan pada aplikasi Contact
- SharedPreferences.Editor -> simpan setting dan simpan data session.

Konsep SQL :
untuk database biasa dapat menyimpan pada database langsung, jika Android perlu menyimpan pada suatu variable.

- Cursor menunjuk pada satu baris.

Perbedaan SQLite dan Room adalah SQLite harus membuat statement untuk create table. Sedangkan, Room harus membuat sebuah model untuk create table.<br>

Komponen-komponen pada Room :
- Entity
- DAO Database Access Object
- Database -> berisi definisi Entitas-entitas.

       Note : Annotation ditandai dengan '@' : @override, @entity dan sebagainya.
       
Setiap perubahan skema naikkan version nya.

Singleton : memastikan instansiasi object hanya terdapat 1 instance database yang terhubung.

Kelebihan Room :
- Jika terdapat statement yang salah maka tidak dapat di Compile
- Defaultnya Operasi Database menggunakan Asynchronous.

ViewModel -> datanya disimpan pada UI
Repository -> 

untuk Flutter -> umumnya menggunakan BLoC (sesuai dengan kebutuhan).
