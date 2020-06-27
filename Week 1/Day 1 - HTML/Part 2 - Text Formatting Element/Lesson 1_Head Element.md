# Head Element

Setelah membahas tentang struktur HTML dan aturan dasar penulisan HTML pada bab sebelumnya, dalam bab kali ini kita akan membahas lebih jauh tentang *head element*, yakni tag-tag apa saja yang umumnya ada dalam bagian `<head>` dari sebuah halaman HTML.

**Tag `<head>` biasanya berisi informasi tentang halaman yang akan diproses atau pendefinisian *link* kepada *file-file* yang dibutuhkan dalam memproses halaman tersebut**, seperti *file* CSS atau *file* JavaScript.

letak tag *head*, adalah:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Belajar HTML</title>
    
  </head>
  <body>

  </body>
</html>
```

## Meta Element

Element pertama yang berada di dalam tag `<head>` adalah meta element. **Tag `<meta>` berfungsi untuk memberi informasi mengenai halaman HTML yang saat ini sedang ditampilkan.** Tag ini ditujukan bukan kepada pengunjung *website*, tetapi kepada *web browser*. Oleh karena itu efek dari tag `<meta>` tidak terasa bagi pengunjung.

Seluruh tag `<meta>` bersifat opsional dan tidak harus ada dalam setiap halaman HTML. Pengecualian untuk hal ini adalah tag `<meta charset="UTF-8">` yang jika tidak ditambahkan, validator HTML5 akan mengeluarkan *error*.

Jika teman-teman menggunakan Visual Studio Code sebagai *text editor*, teman-teman bisa langsung mendapatkan *'template'* HTML dengan mengetik HTML pada *file* dengan *extention* .html, lalu ketikkan *snippet* `html5` kemudian tekan tab, maka akan muncul secara keseluruhan seperti ini:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

## Title Element

`<title>` Element merupakan salah satu yang paling penting juga di dalam `<head>`, karena nantinya title ini berdungsi untuk menampilkan judul halaman di browser kita. Seperti contoh sebelumnya pada `Hello Word dalam HTML`, `<title>` yang kita masukkan adalah "Pengenalan HTML". Maka pada saat kita jalankan file tersebut di browser, maka akan terlihat `<title>`nya. Pada hasil pencarian Google, hanya 50-60 karakter pertama saja yang akan ditampilkan. Oleh karena itu sebaiknya tidak menggunakan judul yang terlalu panjang.
