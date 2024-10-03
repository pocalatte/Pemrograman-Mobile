**Nama: Ellois Karina Handoyo**

**NIM: 2241720154**

## **Soal 1**

Modifikasilah kode pada baris 3 di VS Code atau Editor Code favorit Anda berikut ini agar mendapatkan keluaran ( *output* ) sesuai yang diminta!

Jawab:

voidmain() {

  for (int i =18; i >=9; i--) {

    print('Nama saya adalah Fulan, sekarang berumur $i');

  }

}

## **Soal 2**

Mengapa sangat penting untuk memahami bahasa pemrograman Dart sebelum kita menggunakan framework Flutter ? Jelaskan!

Jawab :

### 1. **Flutter Dibangun di Atas Dart**

   Flutter sepenuhnya menggunakan Dart untuk semua logika bisnis, antarmuka pengguna (UI), dan interaksi dengan sistem. Jika kamu tidak memahami Dart, akan sulit untuk memanfaatkan Flutter secara maksimal karena hampir semua fitur dan alat dalam Flutter berhubungan erat dengan syntax dan struktur Dart.

### 2. **Mendukung Pemrograman Berbasis Objek**

   Dart adalah bahasa yang berorientasi objek, jadi banyak konsep seperti class, inheritance, polymorphism, dan encapsulation digunakan secara luas dalam pengembangan Flutter. Memahami konsep-konsep ini membantu dalam merancang arsitektur aplikasi yang lebih baik dan memanfaatkan pustaka serta widget Flutter dengan efektif.

### 3. **Fungsi Asynchronous dan Pemrograman Responsif**

   Flutter sering melibatkan operasi asynchronous seperti mengambil data dari API atau mengakses database. Dart memiliki fitur khusus seperti `async`, `await`, dan `Future` untuk menangani operasi asynchronous dengan cara yang lebih sederhana dan efisien. Memahami konsep asynchronous di Dart sangat penting karena sebagian besar pengembangan aplikasi modern memerlukan penanganan operasi yang tidak sinkron.

### 4. **Struktur Data dan Kontrol Alur**

   Dart menyediakan banyak fitur seperti list, set, map, dan collection yang sangat berguna dalam Flutter untuk menyimpan, memanipulasi, dan mengelola data. Jika tidak memahami cara kerja struktur data ini, akan lebih sulit untuk mengelola data dalam aplikasi Flutter. Dart juga memiliki kontrol alur seperti loops, conditions, dan exception handling yang harus dipahami agar dapat menulis logika aplikasi dengan baik.

### 5. **Memahami Widget dan State Management**

   Flutter menggunakan konsep widget untuk membangun UI, dan pengelolaan state (state management) adalah aspek inti dalam membangun aplikasi interaktif. Dart memungkinkan kamu untuk membuat custom widget dan mengelola state secara efisien. Pemahaman tentang bahasa Dart sangat penting untuk dapat menulis widget yang kompleks dan mengelola state dengan benar.

### 6. **Memanfaatkan Fitur Dart yang Unik**

   Dart memiliki beberapa fitur unik seperti hot reload dan snapshot yang sangat berguna saat pengembangan aplikasi dengan Flutter. Selain itu, Dart mendukung fitur seperti null safety yang membantu developer mencegah kesalahan runtime terkait nilai null, sehingga meningkatkan stabilitas aplikasi.

### 7. **Kinerja dan Optimisasi**

   Dart mendukung kompilasi just-in-time (JIT) dan ahead-of-time (AOT), yang membantu Flutter memberikan kinerja aplikasi yang cepat dan responsif. Memahami bagaimana Dart dikompilasi dan dijalankan dapat membantu developer mengoptimalkan aplikasi Flutter agar berjalan lebih efisien.

## **Soal 3**

Rangkumlah materi dari codelab ini menjadi poin-poin penting yang dapat Anda gunakan untuk membantu proses pengembangan aplikasi mobile menggunakan framework Flutter.

Jawab:


### 1. **Pengenalan Dart**

* **Bahasa Pemrograman** : Dart adalah bahasa pemrograman yang dikembangkan oleh Google, dirancang untuk pengembangan aplikasi mobile, web, dan server.
* **Bahasa Berorientasi Objek** : Dart adalah bahasa yang berorientasi objek dan mendukung konsep-konsep seperti class, inheritance, dan polymorphism.

### 2. **Sintaks Dasar**

* **Variabel** : Dart mendukung tipe data statis dan dinamis. Gunakan `var`, `int`, `double`, `String`, dan `bool` untuk mendeklarasikan variabel.
* **Fungsi** : Fungsi dideklarasikan dengan `void` (tanpa return value) atau dengan tipe return yang sesuai. Dart juga mendukung fungsi anonim dan fungsi arrow (`=>`).
* **Kondisional** : Gunakan `if`, `else if`, dan `else` untuk logika percabangan.
* **Looping** : Mendukung `for`, `while`, dan `do-while` untuk perulangan.

### 3. **Tipe Data**

* **Primitif** : Tipe data dasar termasuk `int`, `double`, `String`, dan `bool`.
* **Collection** : Dart memiliki koleksi seperti `List`, `Set`, dan `Map` yang sering digunakan untuk menyimpan kumpulan data.
* **Null Safety** : Dart mendukung null safety, yang membantu menghindari error terkait nilai null dengan menandai variabel nullable (`?`).

### 4. **Struktur Data**

* **List** : Struktur data untuk menyimpan sekumpulan item dalam urutan tertentu, dapat berupa list tetap atau dinamis.
* **Map** : Struktur data berbasis pasangan kunci-nilai (`key-value pairs`).
* **Set** : Koleksi yang menyimpan elemen unik tanpa urutan.

### 5. **Pemrograman Berorientasi Objek**

* **Class dan Object** : Class digunakan untuk mendefinisikan blueprint dari objek. Dart mendukung inheritance, encapsulation, dan polymorphism.
* **Constructor** : Dart mendukung constructor untuk inisialisasi objek dan mendukung fitur seperti constructor default dan named constructor.
* **Inheritance** : Dart mendukung pewarisan, di mana class anak dapat mewarisi sifat dari class induk dengan menggunakan keyword `extends`.
* **Abstract Class dan Interface** : Dart mendukung class abstract untuk mendefinisikan kerangka fungsi yang wajib diimplementasikan oleh class turunannya, serta interface untuk mengatur kontrak antar class.
