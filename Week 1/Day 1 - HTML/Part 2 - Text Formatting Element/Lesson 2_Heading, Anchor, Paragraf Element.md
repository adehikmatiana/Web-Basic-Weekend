# Heading, Anchor dan Paragraf Element

## Heading Element (h1 – h6)

***Heading element* atau tag `<h1>` sampai `<h6>` digunakan untuk membuat judul (heading) di dalam halaman HTML.**

`<h1>` untuk *heading* dengan *font* terbesar dan `<h6>` untuk *heading* dengan *font* terkecil.

Berikut merupakan contoh penggunaannya:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>belajar Heading</title>
</head>

<body>
    <h1> dengan heading H1</h1>
    <h2> dengan heading H2</h2>
    <h3> dengan heading H3</h3>
    <h4> dengan heading H4</h4>
    <h5> dengan heading H5</h5>
    <h6> dengan heading H6</h6>
</body>

</html>
```

Jika dijalankan di *browser* hasilnya akan seperti ini:

![heading](img/2/heading.png)

## Anchor Element

**Anchor Elemet atau Tag `<a>`** berfungsi untuk membuat link ke halaman website, file, alamat email, lokasi di halaman yang sama, atau apapun yang berhubungan dengan *link*.  

Untuk menggunakan Tag `<a>`, setidaknya kita perlu 2 hal penting, yaitu *link* tujuan dan juga teks alias yang nantinya dapat di klik menuju halaman link tersebut.

Contohnya seperti ini:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag <a></title>
</head>

<body>

    <p>Berikut adalah beberapa media sosial yang populer:</p>
    <ul>
        <li><a href="https://www.instagram.com/">instagram</a></li>
        <li><a href="https://www.twitter.com/">twitter</a></li>
        <li><a href="https://web.facebook.com/">facebook</a></li>
    </ul>
</body>

</html>
```

Jika dijalankan maka hasilnya akan seperti ini:

![anchor](img/2/anchor.png)

> Bisa dilihat ketika kita meng-*hover* kursor ke arah **instagram**, maka akan muncul alamat link di bagian bawah kiri sebuah *browser*

### Atribut Anchor Element

Seperti yang sudah dicoba di atas, bahwa tag `<a>` membutuhkan atribut `href`. Selain itu, ada beberapa atribut lain, diantaranya:

1. `href`

    `href` merupakan atribut yang menampung URL yang dituju.

    - Alamat Telfon menggunakan `tel: +URL`
    - Alamat Email menggunakan `mailto: +URL`

2. `target`

    Atribut target pada tag `<a>` digunakan untuk menentukan pada jendela mana halaman web akan ditampilkan. Nilai yang bisa digunakan untuk atribut ini adalah _self, _blank, _parent, _top, atau framename.

    - `target="_self"`: Menampilkan halaman *link* di dalam *window* / Tab saat ini.

        ```html
        <a href="https://www.instagram.com/">instagram</a>
        ```

        > Biasanya `target` ini jarang dipakai, karena kondisi **DEFAULT**

    - `target="_blank"`: Menampilkan halaman *link* di dalam *window* / Tab baru web browser.

        ```html
        <a href="https://www.instagram.com/" target="_blank">instagram</a>
        ```

        > Penggunaan `target blank` ini sangat disarankan untuk semua link yang mengarah ke website luar, fungsinya agar pengunjung website dapat kembali lagi ke website asalnya.

## Paragraf Element

**Paragraf Element atau Tag `<p>` digunakan untuk membuat paragraf, biasanya tag inilah yang paling banyak digunakan ketika mengisi konten untuk sebuah *website*.**

Untuk membuat paragraf, kita tinggal mengisi teks diantara tag pembuka `<p>` dan tag penutup `</p>`, seperti contoh berikut:

```html
<p>Ini adalah paragraf pertama</p>
<p>Ini adalah paragraf kedua</p>
```

**Tag `<p>` merupakan *block level element*, sehingga akan tampil terpisah dalam baris baru**. *Web browser* juga akan menambahkan beberapa spasi sebelum dan sesudah paragraf. Spasi ini (atau lebih tepatnya: *margin*) nantinya bisa dihilangkan atau diubah menggunakan CSS.
