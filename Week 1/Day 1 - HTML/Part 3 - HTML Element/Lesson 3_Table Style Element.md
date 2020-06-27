# Table Style Element

Jika pada *lesson* sebelumnya sudah mempelajari struktur dasar untuk membuat sebuah tabel, maka kali ini akan belajar bagaimana kita melakukan *styling* terhadap tabel yang dibuat. Mulai dari *Border, Cellpadding* dan juga *bgcolor* yang berfungsi untuk memberikan warna *background* pada sebuah tabel.

## Border

Sama seperti membuat tabel pada *microsoft word* atau *excel*, dimana tabel yang dibuat dapat diberi bingkai atau *border*. Pada HTML, kita bisa menambahkan border ke dalam tag `<table>` yang bisa berisi nilai dalam satuan pixel.

### Contoh Border

Masih menggunakan contoh pada *lesson* sebelumnya, yaitu "Structure of Table Element", namun akan ditambahkan *border* di dalam tag `<table>` menjadi seperti ini:

```html
<table border="1">
```

Jika dijalankan maka hasilnya akan seperti ini:

![border](img/3/border.png)

> *border* akan membuat bingkai di sisi luar tabel.

Atau bisa seperti ini:

```html
<table style="border: 1px solid black">
```

Jika dijalankan maka hasilnya akan seperti ini:

![border2](img/3/border2.png)

> Menghasilkan tabel dengan tebal 1px, bergaris normal (solid), dan warna nya hitam (black)

## Cellpadding

Atribut selanjutnya yaitu, *Cellpadding*. Ini berfungsi untuk **mengatur jarak antara garis border sel dengan teks**. Atribut ini sama seperti border, yaitu bernilai satuan pixel. Untuk menggunakannya, kita bisa langsung saja menambahkan setelah atribut border, seperti di bawah ini:

```html
<table border=1, cellpadding=7>
```

Jika dijalankan, maka hasilya akan seperti ini:

![padding](img/3/padding.png)

## Bgcolor

Atribut style selanjutnya adalah *bgcolor*. Pada HTML, atribut ini berfungsi untuk memberikan warna pada tabel.

Atribut ini bernilai warna, bisa diisi dengan menggunakan nama warna dalam bahasa inggris atau dalam format *hexadesimal* yang terdiri dari 6 digit dan diawali dengan #.

### Contoh Bgcolor

```html
<table border=1, bgcolor="pink">
```

Jika dijalankan maka hasilnya seperti ini:

![bgcolor](img/3/bgcolor.png)

>Atribut ini sudah sangat jarang digunakan, terutama pada HTML5. Untuk melakukan Styling terhadap tabel, sangat disarankan menggunakan CSS.
