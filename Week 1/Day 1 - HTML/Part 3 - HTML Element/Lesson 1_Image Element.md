# Image Element

**Image Element** berfungsi untuk menambahkan *Image* atau gambar ke dalam halaman website. Image Element didefinisikan dengan Tag `<img>`, di mana Tag `<img>` membutuhkan atribut yang mendukung fungsinya.

Tag `<img>` termasuk ke dalam *inline level element*, sehingga akan mengikuti alur teks dimana tag tersebut ditempatkan.

Tag `<img>` juga merupakan *void element*, dan tidak membutuhkan tag penutup `</img>`.

## Atribut Image Element

1. `src` atau *Source* berfungsi untuk menuliskan *link* ke alamat gambar yang akan ditampilkan. `src` ini dapat berisi *link* menuju sebuah website luar atau *path* di dalam direktori lokal kita sendiri.

2. `Alt` atau *alternate text* berfungsi untuk memberikan keterangan mengenai gambar. Isi dari `Alt` ini adalah teks yang akan ditampilkan jika gambar dalam kondisi-kondisi berikut:

    - Gambar tidak dapat ditampilkan (misalkan karena gangguan jaringan internet).
    - *Web browser* tidak mendukung format gambar.
    - *Web browser* sedang dalam proses menampilkan gambar.
    - *Web browser* diset agar tidak menampilkan gambar.
    - Pengguna menggunakan browser khusus seperti “screenreader”yangtidakakanmenampilkan gambar.

### Contoh Penggunaan Image Element

Di bawah ini adalah contoh menggunakan Tag `<img>` di dalam HTML

#### Gambar dari perangkat laptop / PC

Berikut sintaks nya:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Element</title>
</head>

<body>
    <p>Contoh gambar dari laptop</p>
    <img src="haltev.png">
</body>

</html>
```

Jika dijalankan maka hasilnya seperti ini :

![image1](img/1/haltev.png)

> Pastikan bahawa file foto terdapat di folder yang sama dengan file html nya. Jika tidak dalam 1 folder yang sama, silahkan menggunakan `/` sebagai *Path* untuk menuju lokasi gambar.

#### Gambar dari website luar

Berikut sintaks nya:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Element</title>
</head>

<body>
    <p>Contoh gambar dari website luar</p>
    <img src="https://haltev.id/wp-content/uploads/2020/02/cropped-logo-transparent-e1580815036845.png">
</body>

</html>
```

Jika dijalankan maka hasilnya seperti ini :

![image1](img/1/image2.png)

#### Gambar menggunakan atribut `Alt`

Contoh sekarang adalah menggunakan contoh yang sebelumnya, nantinya akan kita buat error *link* nya dengan menambahkan simbol `-` diujung `link`, sehingga menjadi seperti ini:

```html
<img src="https://hacktiv8.com//assets/img/logos/hacktiv8-text-black-.svg">
```

>Tanpa Alt

Jika dijalankan maka hasilnya seperti ini:

![tanpa](img/1/tanpa.png)

```html
<img alt="logo hacktiv8" src="https://hacktiv8.com//assets/img/logos/hacktiv8-text-black-.svg">
```

>Dengan Alt

Jika dijalankan maka hasilnya seperti ini:

![tanpa](img/1/dengan.png)
