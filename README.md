| Nama  | Oktovan Agung Shailendra|
|-------|-------------------------|
|NIM    |312010131                |
| Kelas | TI.20.A.1               |

---

## Langkah-Langkah Praktikum
persiapan memuat dokumen HTML dengan nama file **lab5_javascript.html** seperti berikut.
![img](img/img1.png)
Dan lihat hasilnya pada web browser
![img](img/img2.png)

## Javascript Dasar
Pemakaian Alert Sebagai Properti Window.
![img](img/img3.png)

Pemakaian Metode Dalam Objek
![img](img/img4.png)

Pemakaian Prompt
![img](img/img5.png)
![img](img/img6.png)

Pembuatan Fungsi & Cara Pemanggilannya
![img](img/img7.png)

## Dasar Pemrograman Di Javascript
Oprasi Dasar Aritmatika
![img](img/img8.png)

Seleksi Kondisi (if...else)
![img](img/img9.png)
Jika memasukan nilai kurang dari 60
![img](img/img10.png)
Jika memasukan nilai lebih dari 60
![img](img/img11.png)

Penggunaan Operator Switch Untuk Seleksi Kondisi
![img](img/img12.png)
![img](img/img13.png)

## Pembuatan Form
Form Input
![img](img/img14.png)

Form Button
![img](img/img15.png)
![img](img/img16.png)
![img](img/img17.png)
![img](img/img18.png)

## HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis
![img](img/img19.png)

## Pertanyaan & Tugas
1. Buat Script untuk melakukan validasi pada isian form

## JAWABAN

1. Membuat Validasi Nama, NIM, dan E-mail.
### Nama
Validasi nama hanya bisa diisi dengan alfabet (a-z, A-Z) tidak bisa diisi dengan campuran alfabet dengan angka ataupun hanya angka (Abcde123 / 1234)
![img](img/img20.png)
Penjelasan :
- pertama, membuat nama `function Alphabet` dengan parameter dinamis yaitu (nilai,pesan).
- Data yang boleh diinput berupa `a-z, A-Z`.
- Jika selain data `a-z, A-Z` yang diinput maka akan muncul pesan Alert `alert(pesan)`.
![img](img/img26.png)

### NIM
Validasi NIM hanya boleh berisi angka (0-9), tidak bisa diisi dengan huruf alfabet.
![alert1](img/img21.png)
Penjelasan :
- `var numberExp = /^[0-9]+$/;` merupakan variabel numberExp yang diberi batasan validasi angka `(0-9)`.
- Arti Match pada `if(nilai.value.match(numberExp))` adalah string.match(), mencari string menggunakan Regular Expression (Regex)
- Jika inputan tidak benar maka akan ada pesan alert `alert(pesan);`.
![alert2](img/img27.png)

### E-Mail
validasi e-mail masih berupa Regular Expression, contoh : abcd123@gmail.com (benar), abcd123@gmail. (salah).
![img](img/img22.png)
Penjelasan :
- membuat variabel email `var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/;` berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert `alert(pesan);`
![alert](img/img28.png)

### Menambahkan Alert
![img](img/img23.png)

### Menambahkan Form
![img](img/img24.png)

## Kode Secara Keseluruhan
![img](img/img25.png)

## Pengisian Form Yang Benar
![img](img/img29.png)