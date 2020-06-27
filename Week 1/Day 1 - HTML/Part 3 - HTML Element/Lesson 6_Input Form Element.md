# Atribut Action

**Atribut `action` digunakan untuk menulis alamat *file* yang menjadi tujuan pengiriman data.** Biasanya nilai dari atribut `action` berupa alamat sebuah halaman PHP (atau bahasa pemrograman server lain) yang digunakan untuk memproses isi *form*.

Berikut contoh penulisan atribut `action` dalam *form*:

```html
<form action="namafileproses.php">
  ...silahkan masukkan isi form...
</form>
```

*Form* di atas akan mengirim hasil isian *form* ke halaman **prosesform.php** untuk selanjutnya diproses di sisi server.

## Atribut Method

**Atribut `method` berfungsi untuk memberitahu *web browser* bagaimana cara pengiriman data *form*.** Atribut ini dapat diisi dengan nilai `get` atau `post`.

Perbedaan antara `get` dan `post` lebih bersifat teknis. Sebagai gambaran, jika kita menulis atribut **`method="get"`**, **maka isian data *form* akan ditambahkan ke dalam alamat URL (terlihat pada _address_ *bar* *web browser*)**. Sedangkan jika menggunakan **`method="post"`**, **isi data *form* ini tidak akan terlihat**.

Sesuai dengan namanya, `method="get"` digunakan jika *form* akan **‘mengambil’** sesuatu dari server (seperti menampilkan artikel atau menampilkan hasil pencarian), sedangkan `method="post"` lebih cocok digunakan untuk *form* yang akan **‘menginput’** sesuatu ke dalam *web server* (seperti *form* registrasi) atau *form* dengan data yang bersifat rahasia (seperti *form* login). Walaupun demikian, sifatnya hanya sebagai rekomendasi. Kita bisa menggunakan *method* `get` maupun `post` untuk tujuan apa saja.

Baik *method* `get` maupun `post` memiliki batas maksimal karakter yang dapat dikirim. Ini bergantung ke pada *web browser* dan *web server* yang digunakan. Sebagai gambaran, ***method* `get` umumnya mendukung hingga 2 kb karakter (sekitar 2000 karakter)**, sedangkan ***method* `post` bisa mendukung hingga 2 gb karakter (sekitar 2 milyar karakter)**. Oleh karena itu, jika *form* yang dikirim cukup panjang, sebaiknya menggunakan *method* `post`.

> Nilai *default* dari ***method*** ini adalah `get`

contoh penulisan atribut ***method***:

```html
<form action="namafileproses.php" method="post">
  ...silahkan masukkan isi form...
</form>
```

## Input Element Type Submit

Tag `<input type="text">` yang kita pelajari sebelum ini merupakan salah satu dari banyak objek *form* di dalam HTML. Sebelum kita mempelajari objek-objek *form* lain, kita akan membahas terlebih dahulu cara mengirimkan *form* ke server untuk diproses dengan menggunakan tombol ***submit***.

Untuk mengirimkan *form* ke server, HTML menyediakan tag `<input type="submit">`. Tag ini masih menggunakan tag `<input>`, akan tetapi tampilannya berbentuk tombol *(button)*. Berikut contoh penggunaannya:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Buat form dengan HTML</title>
  </head>
  <body>
    <form action="namafileproses.php" method="post">
      <p>Agama : <input type="text" name="agamauser" /></p>
      <p>Jenis Kelamin : <input type="text" name="jkuser" /></p>
      <p><input type="submit" /></p>
    </form>
  </body>
</html>
```

Silahkan teman-teman *save* dan jalankan di _browser_ masing-masing, maka hasilnya akan seperti ini:

![form](img/2/form.png)

Seperti yang terlihat, tag `<input type="submit">` berbentuk tombol. Ketika tombol ini di klik, *form* akan langsung dikirim ke halaman **namafileproses.php** (sesuai dengan atribut *action* pada tag *form*).
