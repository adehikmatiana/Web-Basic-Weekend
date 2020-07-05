# Array Pada Javascript

**Array** merupakan tipe data bentukan yang berisi banyak data. Di dalam JavaScript, **array** juga termasuk ke dalam **Object** yang memiliki berbagai property dan method. Dalam bab ini kita akan fokus membahas tentang **Array** **Object** JavaScript.

Array bisa ditulis menggunakan **object constructor** dengan perintah _new Array()_, maupun dengan penulisan **array literal** menggunakan tanda kurung siku [ ]. Berikut contohnya:

```JS
var foo = new Array("a","b","c","d","e");
 console.log ( typeof foo ); // object
 console.log ( foo ); // Array [ "a", "b", "c", "d", "e" ]

var bar = ["a","b","c","d","e"];
 console.log ( typeof bar ); // object
 console.log ( bar ); // Array [ "a", "b", "c", "d", "e" ]
```

Terlihat kedua cara pembuatan _array_ ini tetap dianggap sebagai object oleh JavaScript. Namun karena lebih praktis dan efisien, cara pembuatan _array_ yang lebih disarankan adalah menggunakan **array literal**, yakni membuat _array_ menggunakan tanda kurung siku [ ].

## Kenapa Kita Butuh Array

Ilustrasi data mahasiswa diatas tersebut adalah salah satu alasan mengapa kita membutuhkan _array_, yaitu karena _array_ dapat menampung lebih dari sebuah nilai, alasan lain kenapa kita menggunakan _array_ adalah:

1. Mempermudah pengelolaan nilai / value/ data. Dengan _array_ kita dapat melakukan penulusuran dan pencarian.
2. Manajemen memori, karena kita tidak perlu lagi membuat variabel yang banyak, cukup dengan sebuah _array_ kita sudah dapat menampung banyak data sekaligus.

## Karakteristik Array

1. _Array_ itu adalah variabel jamak, yang mempunyai banyak elemen dan diacu dengan nama yang sama
2. Kumpulan pasangan key dan nilai / key and value pair. Key adalah index pada _array_ dengan tipe integer yang dimulai dari 0
3. _Array_ pada _JavaScript_ ini tipenya adalah Object, karena **array adalah Object** maka _array_ pada _JavaScript_ memiliki fungsi/method, salah satunya adalah length yang digunakan untuk menghitung jumlah elemen didalamnya.
4. Elemen pada _array_ boleh saja memiliki tipe data yang berbeda.

## Cara Membuat Array pada Javascript

Pada _javascript_, array dapat kita buat dengan tanda kurung siku **([...])**.

Contoh:

```js
var products = [];
```

Maka variabel products akan berisi sebuah array kosong.

Kita bisa mengisi data ke dalam array, lalu setiap data dipisah dengan tanda koma (,).

Contoh:

```js
var products = ["Flashdisk", "SDD", "Monitor"];
```

## Cara Mengambil Data dari Array

Seperti yang sudah kita kethaui, Array akan menyimpan sekumpulan data dan memberinya nomer indeks agar mudah diakses.

**Indeks array** selalu dimauli dari nol 0.

Misalkan kita punya array seperti ini:

```js
var aktivitas = ["Makan", "Minum", "Tidur"];
```

Bagaimana cara kita mengambil nilai "Tidur"?

Jawabannya seperti ini:

aktivitas[2] //-> "Tidur"
Kenapa bukan 3?

> **Ingat: indeks array selalu dimulai dari nol.**
