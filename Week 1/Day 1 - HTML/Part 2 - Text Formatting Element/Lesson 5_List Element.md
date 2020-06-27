# List Element

## Ordered List `<ol>`

**Ordered list** adalah **list yang berurutan**. List ini menggunakan angka atau huruf sebagai penentu urutan.

Ordered list biasanya digunakan untuk sebuah daftar yang harus tersusun dan berurutan sehingga membutuhkan penanda yang spesifik seperti 1, 2, 3 atau A, B, C

Untuk membuat ordered list, kita menggunakan tag `<ol>`, sedangkan untuk membuat isi dari list, menggunakan tag `<li>`.

### Atribut Ordered List

Atribut pada tag `<ol>` berfungsi untuk menentukan jenis karakter yang digunakan sebagai penanda list. Terdapat 5 jenis type yang tersedia di dalam HTML:

- `type="a"`, merupakan list dengan huruf kecil
- `type="A"`, merupakan list dengan huruf besar
- `type="i"`, merupakan list dengan angka romawi kecil
- `type="I"`, merupakan list dengan angka romawi besar
- `type="1"`, merupakan list dengan angka desimal, ini adalah **DEFAULT** jika atribut tidak ditulis.

#### Contoh Penggunaan Ordered List

Berikut adalah sintaks untuk membuat ordered list:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List Elemen</title>
</head>

<body>
    <h2>Course dalam Front-End Basic Specialization</h2>
    <ol>
        <li>HTML</li>
        <li>CSS</li>
        <li>Javascript</li>
        <li>Algoritma</li>
    </ol>
</body>

</html>
```

Jika dijalankan maka hasilnya seperti ini:

![order1](img/5/ordered1.png)

Untuk menambhkan type, bisa langsung saja ditambhakan di dalam tag `<ol>`

```html
 <ol type="A">
```

Jika dijalankan maka hasilnya seperti ini:

![order2](img/5/ordered2.png)

## Unordered List `<ul>`

**Unordered list** adalah **list yang tidak memerlukan urutan**. Biasanya list ini digunakan jika posisi daftar tidak berpengaruh.

### Atribut Unordered List

Seperti **Ordered List** yang memiliki **atribut default**, **Unordered List** memiliki **atribut default yaitu *bullets** atau lingkaran hitam sebagai penanda list.

Tetapi kita bisa menggunakan atribut type untuk menggantinya.

- `type="disc"`, **DEFAULT** menggunakan lingkaran hitam penuh.
- `type="circle"`, merupakan list bulatan hitam (dengan isi lingkaran putih).
- `type="square"`, merupakan list kotak hitam.

#### Contoh Penggunaan Unordered List

Sama seperti sebelumnya, hanya saja `<ol>` nya kita ganti menjadi `<ul>`. Jika dijakankan maka hasilnya akan seperti ini:

![unorder1](img/5/unorder1.png)

Jika kita ingin menambahkan atribut, bisa langsung dimasukkan di dalam tag `<ul>`, menjadi

```html
<ul type="circle">
```

![unorder2](img/5/unorder2.png)

## Description List `<dl>`

**Description List** adalah list yang digunakan untuk struktur list yang memiliki judul beserta keterangannya, seperti ‘kamus’. Jenis list ini tidak terlalu sering digunakan.

### Pasangan Tag

Untuk membuat description list, seluruh list harus berada di dalam pasangan tag `<dl>` dan `</dl>`. Untuk setiap deskripsi atau bagian judul, kita menggunakan tag `<dt>`. Sedangkan untuk bagian penjelasannya, kita menggunakan tag `<dd>`.

- `<dl>` adalah singkatan dari **description list**
- `<dt>` adalah singkatan dari **data term**
- `<dd>` adalah singkatan dari **data description**

#### Contoh Penggunaan Description List

Berikut adalah sintaks untuk membuat Description List

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List Elemen</title>
</head>

<body>
    <h2>Hacktiv8 Indonesia</h2>
    <dl>
        <dt>Program</dt>
        <dd>Banyak program yang tersedia di Hacktiv8 yang dapat mendukung minat dan bakat</dd>
        <dt>Alamat</dt>
        <dd>Jl. Sultan Iskandar Muda, Kebayoran Jakarta Selatan</dd>
        <dt>CEO</dt>
        <dd>Ronal Ishak</dd>
    </dl>
</body>

</html>
```

Jika dijalankan maka hasilnya seperti ini:

![desc](img/5/desc.png)
