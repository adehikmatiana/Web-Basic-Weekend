# Underline , Mark, Strikethrough

Element *underline* dan *strikethrough* sama seperti element sebelumnya, yaitu memiliki 2 tag.

## Underline element

 Element ini digunakan untuk membuat **garis bawah** untuk teks, Untuk membuat garis bawah (*underline*), kita dapat menggunakan tag `<u>` dan tag `<ins>`

## Strikethrough element

 Element ini digunakan untuk membuat **garis tercoret** di tengah sebuah teks, untuk membuat garis tercoret bisa menggunakan tag `<s>` dan tag `<del>`.

### Contoh Penggunaan Underline dan Strikethrough element

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Underline dan Strikethrough</title>
</head>

<body>
    <p>
        <s>Pengenalan</s> <ins>HTML</ins> memiliki element <u>Underline dan Strikethrough</u>.
        masing masing memiliki fungsi inti yang sama, <del>yaitu memberikan garis pada teks</del>
    </p>
</body>

</html>
```

Jika dijalankan maka hasilnya seperti ini:

![understrike](img/4/understrike.png)

## Mark Element

Tag `<mark>` adalah salah satu tag baru yang diperkenalkan pada HTML5. Tag ini berfungsi untuk menandai bagian teks yang dianggap penting, relatif kepada teks di sekelilingnya. Tag ini juga bisa digunakan untuk menandai hasil pencarian.

### Contoh Penggunaan Mark

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mark Element</title>
</head>

<body>
    <p>
        Belajar <mark>Front-End Basic Specialization</mark> di <mark>Hacktiv8 Indonesia</mark>
    </p>
</body>

</html>
```

Jika dijalankan maka hasilnya seperti ini:

![mark](img/4/mark.png)

>Pendanda dengan tag `<mark>` akan secara otomatis memiliki warna background kuning.
