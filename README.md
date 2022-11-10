# counter_7
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

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
