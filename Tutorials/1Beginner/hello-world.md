# Hello World Python

Seperti yang sudah kita ketahui bersama dalam Pendahuluan, bahwa bahasa python sangatlah sederhana untuk ditulis dan dibaca sintaks-nya jika dibandingkan dengan bahasa program lainnya.

## Sintaks Dasar

Dibawah ini merupakan contoh fungsi bawaan Python yang dapat digunakan untuk mencetak. Di Python untuk mencetak apapun cukup gunakan fungsi `print()` , dimana sesuatu yang akan dicetak harus diletakkan diantara kurung buka dan kurung tutup. Jika ingin mencetak tipe data String, teman-teman harus memasukannya kalimatnya ke dalam tanda kutip terlebih dahulu.

> Contohnya:
> ```python
> print("Hello World!")
> ```

Saat teman-teman menjalankan sintaks diatas, maka teman-teman akan melihat output berupa text `Hello World!`

## Python Case Sensitive

Python sangat amatlah sensitif mengenai deklarasinya, dalam artian disini huruf Upper & Lower sangat berperan penting dalam membuat penamaan baik untuk Variabel, Fungsi, dan Kelas. Karena setiap karakter penamaan dianggap berbeda dengan satu sama lainnya. Sebagai contoh: jika saya mendeklarasikan variable `x` yang bernilai 10, maka saat kita ingin mencetak variable `x` maka tidak bisa diubah menjadi `X`

> Contoh sintaks-nya:
> ```python
> x = 10
> print(X)
> ```
>
> Maka akan muncul pesan NameError, seperti:
>
> ```
> Traceback (most recent call last):
>   File "/home/main.py", line 2, in <module>
>       print(X)
> NameError: name 'X' is not defined. Did you mean: 'x'?
> ```

Jadi, saat kita ingin mendeklarasi sesuatu apapun sebaiknya ikuti aturan yang sudah ditetapkan oleh Python.

> _**Sebelumnya:**_ [Cara Penggunaan Pemrograman Python](cara-penggunaan.md) | _**Selanjutnya:**_ [Variabel & Komentar](variable-komentar.md)
