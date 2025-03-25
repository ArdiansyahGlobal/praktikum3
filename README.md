Tugas Praktikum 3: State di Multiple Screens
1.	Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silahkan diperbaiki sesuai dengan tujuan aplikasi tersebut dibuat.
2.	Berdasarkan Praktikum 3 yang telah Anda lakukan, jelaskan maksud dari gambar diagram berikut ini!
 
3.	Lakukan capture hasil dari Langkah 14 berupa GIF, kemudian jelaskan apa yang telah Anda buat!








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
3) GIF Praktikum 3
 
Widget _buildMasterPlans() digunakan untuk menampilkan daftar rencana (plan) yang diambil dari PlanProvider.
•	Jika daftar rencana kosong, ditampilkan ikon dan pesan “Anda belum memiliki rencana apapun.”
•	Jika ada data, ditampilkan dalam bentuk ListView menggunakan ListTile.
•	Saat salah satu rencana diklik, pengguna diarahkan ke halaman detail PlanScreen dengan membawa data rencana tersebut melalui Navigator.push().

