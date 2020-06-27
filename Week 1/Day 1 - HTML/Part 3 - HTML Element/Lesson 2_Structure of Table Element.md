# Structure of Table Element

Dalam HTML, untuk membuat tabel bisa menggunakan elemen `<table>`. Di dalam elemen `<table>`, bisa menggunakan elemen `<tr>` untuk membuat baris, dan untuk membuat kolom di dalam baris, bisa menggunakan elemen `<td>`.

Jadi, Untuk membuat tabel, minimal diperlukan 3 jenis element, yakni `<table>`, `<tr>`, dan`<td>`.

Berikut merupakan contoh penggunaan nya:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table Element</title>
</head>

<body>
    <table>
        <tr>
            <th>No.</th>
            <th>Nama</th>
            <th>Program</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Tiana</td>
            <td>Front-End Basic</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Fauzan</td>
            <td>Front-End Framework</td>
        </tr>
    </table>
</body>

</html>
```

Jika di jalankan maka hasilnya seperti ini:

![table](img/2/table.png)

> Untuk mengatur jarak, atau model borders antar tabel akan dibahas pada lesson selanjutnya.
