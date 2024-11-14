# Laporan Akhir Pertemuan 7 - Praktikum RPL2

## Maulana Hidayatulloh Mujanah (50421797) - 4IA28

---

### ACT Pertemuan 1 (Pengenalan oop)

---

Pada File Activity 1 ini, materi yang dibahas adalah pengenalan pemrograman berorientasi objek (OOP), dengan fokus pada pembuatan kelas dan objek. Isi dari File Activity 1 ini melibatkan kelas dasar yang menggambarkan suatu entitas (seperti Mahasiswa). Di dalam kelas ini, atribut dan metode sederhana dibuat untuk mendefinisikan data serta perilaku dari objek mahasiswa. Output yang dihasilkan menunjukkan penerapan instansiasi objek dari kelas tersebut dan menampilkan nilai atribut yang telah diinisialisasi.

---

### ACT Pertemuan 2 (Inheritance/Pewarisan)

---

Pada File Activity 2 ini, materi yang dibahas mengenai konsep Inheritance (Pewarisan) dalam OOP, dengan pembuatan superclass dan subclass. Isi dari File Activity 2 ini mencakup kelas Kendaraan dan Main sebagai superclass, serta kelas turunan yang memperluas fungsionalitasnya. Dengan penerapan pewarisan, subclass dapat memanfaatkan atribut dan metode yang ada pada superclass, sehingga menghasilkan kode yang lebih terstruktur dan efisien. Output yang dihasilkan menunjukkan bagaimana subclass mengakses atribut yang diwariskan dari superclass.

---

### ACT Pertemuan 3 (MVC)

---

Pada File Activity 3 ini, materi yang dibahas adalah penerapan arsitektur Model-View-Controller (MVC), yang bertujuan untuk memisahkan logika aplikasi dari tampilan pengguna. Dalam implementasinya, terdapat beberapa komponen, seperti MahasiswaController yang bertanggung jawab untuk mengatur alur data antara tampilan (view) dan model aplikasi, dengan berinteraksi langsung dengan MahasiswaDAO untuk melakukan operasi CRUD (Create, Read, Update, Delete). MahasiswaDAO berfungsi sebagai perantara antara controller dan database, memungkinkan pengelolaan data mahasiswa. Di sisi tampilan, MahasiswaView menyediakan antarmuka yang memudahkan pengguna dalam berinteraksi dengan aplikasi, seperti menambah atau mengubah data mahasiswa. Seluruh proyek dikendalikan melalui pom.xml untuk memastikan keberadaan dependensi yang diperlukan. Output aplikasi menampilkan hasil penambahan, pembaruan, dan penghapusan data mahasiswa.

---

### ACT Pertemuan 4 (ORM)

---

Pada File Activity 4 ini, materi yang dibahas adalah penerapan Object-Relational Mapping (ORM) dengan menggunakan Hibernate, yang bertujuan untuk mempermudah komunikasi antara aplikasi dan database tanpa perlu menulis query SQL secara manual. Dalam isi file Activity 4 ini, MahasiswaController mengelola operasi CRUD dan berinteraksi dengan MahasiswaControllerImpl yang memanfaatkan Hibernate. Kelas HibernateUtil digunakan untuk pengaturan konfigurasi Hibernate dan mengelola koneksi ke database. Pada bagian ini, ModelTabel Mahasiswa berfungsi sebagai representasi data mahasiswa dalam bentuk tabel, yang kemudian ditampilkan melalui MahasiswaView. Konfigurasi proyek juga dikelola melalui pom.xml yang mencakup dependensi untuk Hibernate.

---

### ACT Pertemuan 5 (Spring Boot)

---

Pada File Activity 5 ini, materi yang dibahas adalah penggunaan Spring Boot yang mempermudah pengembangan aplikasi Java dengan konfigurasi otomatis dan pengelolaan dependencies.Dalam isi file Activity 5 ini, file Application.properties digunakan untuk mengatur koneksi ke database, sementara MahasiswaController bertugas mengelola permintaan HTTP yang berkaitan dengan operasi data mahasiswa. Kelas ModelMahasiswa menggambarkan struktur data mahasiswa, dan MahasiswaRepository memungkinkan interaksi dengan database secara efisien menggunakan Spring Data JPA. Hasil akhirnya adalah aplikasi yang dapat menambah dan menampilkan data mahasiswa dalam database.

---

### ACT Pertemuan 6 (AOP)

---

Pada File Activity 6 ini, materi yang dibahas adalah penerapan konsep Aspect-Oriented Programming (AOP) dengan Spring, yang memungkinkan pengelolaan concerns yang melintas banyak bagian, seperti logging atau manajemen transaksi, tanpa mengubah logika utama aplikasi. Komponen MahasiswaApp berfungsi sebagai kelas utama, sedangkan MahasiswaService menangani logika bisnis yang mengelola data mahasiswa. Aspek-aspek tambahan, seperti logging, diterapkan dalam kode untuk menangani tugas-tugas tersebut secara terpisah. Tampilan aplikasi ditangani oleh MahasiswaView, yang menampilkan data mahasiswa. Output aplikasi menunjukkan cara penambahan dan penghapusan data mahasiswa berdasarkan ID, serta tampilan data setelah penghapusan.

---

### ACT Pertemuan 7 (Git & GitHub)

---

Pada File Activity 7 ini, materi yang dibahas adalah penggunaan Git dan GitHub. Terdapat dua folder utama, yaitu Folder A (Folder Coba Github) dan Folder B (Folder Clone), di mana Folder B berfungsi sebagai salinan dari Folder A. Penggunaan Git Bash dijelaskan untuk menjalankan perintah dasar seperti clone, commit, push, dan pull. Materi ini juga mencakup cara mengelola repository di GitHub, termasuk penggunaan branch untuk mengorganisir pekerjaan di Folder B atau Clone, serta fitur tag. Selain itu, file README.md dan Test.txt digunakan sebagai contoh untuk melakukan perubahan dan dokumentasi pada repository. Secara keseluruhan, materi ini mengajarkan konsep dasar pengelolaan proyek dengan Git dan GitHub, termasuk penggunaan branch untuk membuat versi terpisah dan menyinkronkan antar folder.
