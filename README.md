Jawaban

2) Gambar tersebut merupakan diagram hierarki widget dalam aplikasi Flutter yang menunjukkan perpindahan antar halaman menggunakan Navigator Push. Berikut adalah penjelasannya:
  1.	Diagram Kiri (Sebelum Navigasi)

o	Aplikasi dimulai dengan MaterialApp.
o	PlanProvider digunakan untuk menyediakan data atau state management.
o	PlanCreatorScreen adalah halaman pertama yang ditampilkan.
o	Di dalam PlanCreatorScreen, terdapat Column yang berisi:
	TextField untuk input.
	Expanded yang berisi ListView untuk menampilkan daftar item.
  
  2.	Diagram Kanan (Setelah Navigasi)
o	Setelah pengguna berpindah ke halaman berikutnya menggunakan Navigator Push, halaman PlanScreen ditampilkan.
o	PlanScreen memiliki:
	Scaffold sebagai struktur dasar halaman.
	Column yang mengatur tata letak elemen dalam layar.
	Expanded berisi ListView untuk menampilkan daftar item.
	SafeArea untuk memastikan teks berada di area yang aman (tidak tertutup oleh status bar atau notch).
