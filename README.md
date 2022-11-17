# Tugas 7
1. Stateless widget adalah widget yang tidak memiliki state dan immutable(semua value di dalamnya adalah final), sedangkan stateful widget merupakan widget yang memiliki state dan mutable. 
2. Widget yang saya pakai di proyek saya kali ini adalah Text untuk menampilkan counter dan genap/ganjil, Column yang digunakan untuk layout secara vertical, dan FloatingActionButton yang merupakan button untuk menambah dan mengurangi variabel counter.
3. Fungsi dari setState() adalah untuk refresh state dari widget yang dilakukan ketika widgetnya berubah. Pada proyek saya kali ini variabel yang terdampak adalah warna, word, dan _counter
4. Isi dari const merupakan const juga, namun isi dari final bukan merupakan final, sehingga isi collections final dapat dirubah.
5. E

Referensi:
1. https://docs.flutter.dev/get-started/codelab#step-3-add-a-stateful-widget
2. https://docs.flutter.dev/development/ui/widgets-intro
3. https://docs.flutter.dev/development/ui/interactive
4. https://stackoverflow.com/questions/50431055/what-is-the-difference-between-the-const-and-final-keywords-in-dart

# Tugas 8
1. Navigator.push hanya memasukkan halaman ke dalam stack navigator, sedangkan Navigator.pushReplacement merubah head of stack navigator dengan halaman baru(melakukan pop terlebih dahulu dan kemudian push)
2. Widget yang saya pakai di proyek saya kali ini adalah drawer yang digunakan untuk navigasi antara halaman counter_7, form, dan data, Text untuk menampilkan kata, TextFormField untuk input form, DropdownButton untuk pilih jenis, dan TextButton untuk submit form.
3. onPressed, onLongpress, onHover, dll.
4. Cara kerja Navigator dalam "mengganti" halaman(route) dari aplikasi flutter adalah sebagai stack yang terbuat dari halaman, ketika ingin menampilkan halaman baru maka push halaman ke dalam stack, jika ingin ke halaman sebelumnya maka harus pop halaman dari stack. Halaman yang ditampilkan sekarang adalah halaman pada head of stack
5. Pertama dengan menggunakan widget drawer pada file main, form, dan dart, di dalam drawer terdapat 3 listtile yang berfungsi sebagai button yang akan menunjukkan ke halaman pada text listtile tersebut, pada halaman form terdapat 2 TextFormField untuk input judul dan nominal, 1 DropdownButton yang digunakan untuk memilih jenis, dan 1 TextButton untuk submit form dan menyimpan data yang telah diisi di TextFormField dan DropdownButton

Referensi:
1. https://api.flutter.dev/flutter/widgets/Navigator/pushReplacement.html
2. https://docs.flutter.dev/development/ui/widgets-intro
3. https://api.flutter.dev/flutter/material/ElevatedButton-class.html#onPressed
4. https://docs.flutter.dev/cookbook/navigation/navigation-basics

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
