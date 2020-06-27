# Table Element

Jika pertama kita sudah mempelajari 3 element dasar untuk membuat sebuah tabel, maka saat ini akan belajar 3 element tambahan untuk membuat struktur tabel menjadi lengkap. 3 diantaranya yaitu `<thead>` , `<tbody>`, dan `<tfoot>`.

## Pengertian Thead, Tbody dan Tfoot Element

- `<thead>` : Element ini berfungsi untuk mendefinisikan sebuah baris yang menjadi awal / kepala baris. (judul tabel)
  
- `<tbody>` : Element ini berfungsi untuk mendefinisikan seluruh isi yang berada di dalam tag `<tr>` merupakan isi tabel.
  
- `<tfoot>` : Element ini berfungsi untuk mendefinisikan penutup tabel / rangkuman sebuah tabel.

> Ketiga element ini hanya sebagai ‘pembagi’ struktur tabel dan tidak mempengaruhi tampilan tabel secara langsung.

## Contoh Penggunaan Thead, Tbody dan Tfoot Element

Berikut sintaks html untuk membuat contoh penggunaannya:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Belajar thead, tbody, tfooter</title>
</head>

<body>
    <h3>Belajar thead, tbody, tfooter</h3>
    <table border="2" width="85%">
        <thead>
            <tr align="center">
                <td colspan="3">contoh tbody</td>
            </tr>
        </thead>
        <tfoot>
            <tr align="right">
                <td colspan="3">Tfooter</td>
            </tr>
        </tfoot>
        <tbody>
            <tr>
                <td>kolom 1</td>
                <td>kolom 2</td>
            </tr>
            <tr>
                <td>baris 1</td>
                <td>baris - 2</td>
            </tr>
        </tbody>
</body>

</html>
```

Jika sudah dijalankan maka hasilnya akan seperti ini:

![tbody](img/4/tbody.png)
