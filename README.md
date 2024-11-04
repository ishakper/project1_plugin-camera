Praktikum 2: Membuat photo filter carousel 

![hasil crett](https://github.com/user-attachments/assets/eb87d8e0-9d95-4bd3-bffd-9c492dd6f970)

 void async:
void async: Dalam bahasa Dart, kata kunci async digunakan untuk menandai sebuah fungsi sebagai fungsi yang bersifat asynchronous. Fungsi yang ditandai dengan async dapat menjalankan proses yang tidak memblokir, seperti mengambil data dari API atau membaca berkas, sehingga antarmuka pengguna (UI) tetap responsif. Di dalam fungsi ini, Anda dapat menggunakan await untuk menunggu hasil dari operasi asynchronous yang sedang berlangsung. Secara otomatis, fungsi ini akan mengembalikan sebuah Future, yang menunjukkan bahwa hasil dari operasi tersebut akan tersedia di kemudian hari.

 anotasi @immutable dan @override:
@immutable: Anotasi ini digunakan untuk menunjukkan bahwa kelas tersebut seharusnya tidak mengalami perubahan setelah objeknya dibuat. Anotasi ini biasanya diterapkan pada widget yang bersifat stateless. Dengan menggunakan @immutable, Anda mencegah adanya perubahan pada status internal objek setelah diinisialisasi, yang berkontribusi pada peningkatan keandalan kode serta memudahkan dalam pemahaman alur logika.

@override: Anotasi ini digunakan untuk menandai bahwa metode yang Anda tulis sedang menggantikan metode yang sama dari kelas induknya. Anotasi ini memberi tahu pengembang lain (serta alat pengembang) bahwa Anda memiliki niat untuk mengubah implementasi metode dari kelas dasar. Hal ini bermanfaat untuk memastikan bahwa metode yang Anda definisikan memiliki signature (tanda tangan) yang sama dengan metode yang dioverride, dan dapat membantu mendeteksi kesalahan jika terdapat ketidaksesuaian dalam penamaan atau parameter yang digunakan.
