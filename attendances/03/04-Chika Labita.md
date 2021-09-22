<h1><b>Week 03 - Widget and Navigation</b></h1>

<h2><b>-> Widget</b></h2>

Widget merupakan komponen utama untuk membangun sebuah UI pada Android. Widget mewarisi dari sebuah View Class.

    Jika kita akan memanipulasi widget maka harus didefinisikan id nya
    cara akses -> R.id.editText)
    R bukanlah sebuah variable akan tetapi R merupakan class khusus pada Android.
    R -> tidak selalu atau tidak harus id akan tetapi sesuai dengan kebutuhan.
    R -> digunakan untuk bagian Front End.
    
    ## UI dan Logic sebaiknya dipisah.
    
  <br>

    Activity Lifecycle pada Android :
    - onCreate()
    - onStart()
    - onResume()
    - onPause()
    - onStop()
    - onRestart()
    - onDestroy()
<br>

    Website Recommend :
    - https://developer.android.com/

Set and Get Value of Widget [tergantung yang kita gunakan]
- It’s depends on Widget
- EditText: Text etc
- ImageView: ImageResource etc
- RadioButton: Text, Checked
- CheckBox: Text, Checked
- Etc


<h2><b>-> Navigation Component</b></h2>

Navigation -> Interaksi yang memungkinkan pengguna melihat-lihat, masuk, dan keluar dari 
berbagai konten dalam aplikasi

3 bagian utama Komponen Navigasi :
- Sumber daya XML yang berisi semua informasi terkait navigasi di satu lokasi terpusat.
mencakup semua area konten individual dalam aplikasi, yang disebut tujuan, 
serta jalur yang mungkin dilalui oleh pengguna pada aplikasi.
- NavHost : mengatur perpindahan 
- NavController : mengatur pertukaran konten tujuan di NavHost saat pengguna menggunakan aplikasi.

Setup pada Android terdapat 2 lokasi :
1. Build.gradle.Module
2. Build.gradle.Project [Jarang digunakan]

Perbedaan Activity dan Fragment
- Activity -> windowsnya ditumpuk-tumpuk
- Fragment -> hanya 1 windows 

Selain pada Activity, pada Fragment juga terdapat lifecycle

    Fragment Lifecycle pada Android :
    - onCreate()
    - onStart()
    - onResume()
    - onPause()
    - onStop()
    - onRestart()
    - onDestroy()
<br>
Jazakumullah Khairan.
