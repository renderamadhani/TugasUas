# TugasUas
Tugas ini dibuat guna memenuhi ujian akhir semester 1

Nama		: Muhammad Rende Ramadhani

NIM		: 312010277

Kelas		: TI.20.B.1

`Buat syntax program python`
Membuat code program : daftar_nilai.py

![2021-01-18](https://user-images.githubusercontent.com/73051103/104926369-a4557400-59d2-11eb-86af-41a4b8a6db62.png)

Penjelasan :

-Disini kita menggunakan dictionary ya untuk menyimpan inputan data mahasiswa
-Def tambahkan : Dibagian ini kita gunakan print untuk penulisan bagian input data mahasiswa nanti agar terlihat rapih
-Def hapus :
-Disini kita buat inputan yang menginput nama
       -Gunanya untuk menghapus data mahasiswa dari nama mahasiswa itu sendiri
       -Kita gunakan del untuk fungsi menghapus datanya
       -(If)Jika mahasiswa tersebut ada maka data mahasiswa tersebut akan terhapus
       -(Else)Jika nama mahasiswa tersebut tidak ada maka datanya tidak akan ditemukan
-Def ubah
Penjelasan:
     -Disini kita hampir sama dengan yang hapus, kita gunakan inputan nama untuk mengubah NIM, Nilai                      Tugas, Ujian Tengah Semester(UTS), ataupun Ujian Akhir Semester(UAS)
    -Lalu setelah kita memasukkan nama maka dictionary akan mengeksekusi program menggunakan keys untuk mencari data dari nama mahasiswa tersebut
    -(If)Jika nama mahasiswa tersebut ketemu atau ada didalam data maka program akan masuk ke inputan NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS yang baru
    -(Else)Jika nama mahasiswa tersebut tidak ada didalam data maka program akan memunculkan tulisan atau perintah bahwa data mahasiswa tidak ada
-Def cari
Penjelasan:
     -Fungsinya sama dengan Def tambahkan

Membuat code program input_nilai.py

![2021-01-18 (1)](https://user-images.githubusercontent.com/73051103/104926825-33fb2280-59d3-11eb-8e49-9bfe4d41c9d3.png)

Penjelasan:

From dan import
Penjelasan:
-From digunakan untuk memanggil package sementara import untuk tujuan yang kita pilih yaitu modul daftar_nilai

-Lalu kita gunakan import data_mahasiswa itu gunanya agar saat kita menginputkan data atau setiap kali kita menambah data maka data mahasiswa secara otomatis akan masuk kedalam dictionary meskipun beda atau terpisah package dan juga modulnya

-Def tambah data
Penjelasan:

-Disini kita buat inputan karena tadi kita sudah membuat kata - kata outputnya kali ini kita cukup membuat inputan data mahasiswanya saja
-Jangan lupa gunakan perkalian untuk menghitung hasil total atau rata- ratanya

Membuat code program view_nilai.py

![2021-01-18 (3)](https://user-images.githubusercontent.com/73051103/104926969-69a00b80-59d3-11eb-9d5a-c9a7566ce730.png)
![2021-01-18 (4)](https://user-images.githubusercontent.com/73051103/104927028-83d9e980-59d3-11eb-8cf6-9fa97c736cdb.png)

Penjelasan:

-From dan import
Penjelasan:

-Fungsinya sama saja dengan yang ada dibagian Input_Nilai

-Def tampil
Penjelasan:

-Disini kita buat sebuah tabel untuk menampilkan data - data dan nama - nama mahasiswa didalam dictionary
-(If)Jika terdapat data maka data dan nama mahasiswa tersebut akan muncul
-Disini kita menggunakan for untuk melakukan perulangan nomor urut
-(Else)Jika kita belum menginputkan data sama sekali maka akan muncul tulisan "tidak ada data"

-Def cari data
Penjelasan:

-Tadi kita sudah buat print sama seperti dibagian Input_Nilai
-Kita akan langsung membuat inputan dengan format nama untuk mencari data dari mahasiswa yang sedang kita cari
-(If)Jika data mahasiswa yang dicari ada didalam dictionary maka data baik Nama, NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS akan muncul
-(Else)Jika data mahasiswa yang dicari tidak ada didalam dictionary maka akan muncul tulisan "datanya tidak ada"

Membuat code program : main.py

![2021-01-18 (5)](https://user-images.githubusercontent.com/73051103/104928039-bcc68e00-59d4-11eb-840f-a080a9c10bdc.png)

-From dan import
Penjelasan:

-Sama seperti sebelumnya hanya saja disini sedikit berbeda

-From disini kita tulis package.modulnya lalu import fungsi(def) tadi

-Karena dibagian main ini kita akan menggunakan atau membuat syntax pilihan menu

-While True
Penjelasan:

-Kita gunakan print untuk membuat pilihan menunya
-Lalu kita buat inputan untuk memilih menu nanti ketika program dijalankan
-(If dan Elif)Kita gunakan karena kita akan membuat cabang pilihan yang banyak
-Lalu dibawahnya kita tambahkan juga fungsi - fungsi yang sudah kita buat tadi
-Pada perintah ke 6 kita gunakan break untuk keluar dari program yang kita jalankan
-(Else)Jika kita tidak memilih salah satu menu tersebut maka akan muncul peringatan "pilih menu yang tersedia diatas"


