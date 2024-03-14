# LP5DPBO2024C1

## JANJI
*Saya Alif Faturahman Firdaus (2107377) mengerjakan Latihan Praktikum 5 dalam mata
kuliah DPBO untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang
telah dispesifikasikan. Aamiin.*

## TUGAS
Download dan Open project ini menggunakan IntelliJ IDEA:  
https://drive.google.com/file/d/1zRFJbX1YAhSqtUKv7xCsW0yrudnicFD2/view?usp=sharing
1. Ketik ulang code di atas untuk melengkapi file Menu.java.
2. Tambahkan satu atribut baru di class Mahasiswa sekaligus component input-nya di form. (Usahakan setiap orang atribut barunya berbeda)
3. Tambah confirmation prompt sebelum delete.

BONUS (+20)  
Jika component baru yang ditambahkan bukan JTextField (Component baru berupa JComboBox, JSlider, JRadioButton, dsb).

## DESAIN PROGRAM
Program ini teridiri dari 2 kelas :

### Class Mahasiswa  
Kelas ini adalah kelas untuk membuat objek mahasiswa yang didalamnya terdapat 5 atribut, diantaranya nim (string), nama (string), jenisKelamin (string), hobby (string) dan mbti (string). Terdapat juga setter dan getter untuk setiap atributnya.

### Class Menu  
Kelas ini berisikan method-method untuk menampilkan tampilan dan juga terdapat fitur-fitur yang memiliki fungsi beragam didalam program, diantaranya :
1. Menu -> method yang berfungsi sebagai pilar utama dari jalan kerja program
2. setTable -> method yang berfungsi untuk membuat table
3. insertData -> method yang berfungsi untuk menambahkan mahasiswa data pada tabel
4. updateData > method yang berfungsi untuk mengubah data yang tersedia pada tabel
5. deleteData -> method yang berfungsi untuk menghapus satu baris data dari tabel
6. clearForm -> method yang berfungsi untuk menghapus data pada form tabel menjadi kosong kembali

## PENJELASAN ALUR
* Untuk judul "Daftar Mahasiswa" dan owner "*By Alif Faturahman Firdaus*" menggunakan swing controls JLabel, kemudian untuk "NIM", "Nama", "Jenis Kelamin", "Hobby", dan "MBTI" juga menggunakan swing controls JLabel. 
* Pada kolom "nim", "nama", dan "hobby" menggunakan swing controls JTextField. 
* Terdapat juga dropdown menu pada kolom "jenisKelamin" dan "mbti" yang menggunakan swing controls JCompoBox. 
* Pada tombol "add", "update", "cancel", "delete" menggunakan swing controls JButton. 
* Kemudian yang terakhir yaitu tabel, menggunakan swing controls JTable.

Terdapat method Menu yang berfungsi untuk melakukan pengisian tabel dengan list mahasiswa, dapat juga melakukan styling font seperti pada Label judul dan owner. Untuk isi dari list pada dropdown menu yang terdapat pada CompoBox juga setiap elemenya di isi melalui method Menu yangmana kita dapat mengisi atau menambahkan elemen sesuai keinginan. Kemudian berisikan juga listener untuk berbagai fungsi seperti "addUpdateButton", "deleteButton", "cancelButton", dan "mahasiswaTable".

## DOKUMENTASI
Pertama, lakukan pengisian data pada seluruh TextField dan juga memilih menu yang tersedia pada dropdown, setelah selesai mengisi data kemudian tekan tombol "add" dan data pun masuk kedalam tabel (No.21). Kemudian isi kembali form lalu tekan tombol "cancel" dan alhasil form ter-reset kembali menjadi tampilan awal (kosong). Setelah itu klik salah satu data pada tabel, kemudian ubah nama, jenis kelamin, hobby, dan mbti nya, setelah selesai mengisi data dilanjut dengan klik tombol "update" dan data pada tabel akan berubah menjadi data yang baru. Terakhir, pilih data pada tabel lalu klik tombol "delete", akan menampilkan confirmation prompt lalu klik "yes", setelah itu muncul notifikasi berhasil menghapus data dan data pada tabel terhapus.

Berikut ini adalah video demo dari programnya.

https://github.com/Aliffaturahman/LP5DPBO2024C1/assets/100842759/40604b1f-031a-44a5-9aec-673332533c17

