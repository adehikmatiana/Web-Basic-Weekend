# Strong, Bold, Italic Element

Saat ini kita akan membahas 4 Element dalam HTML yang berfungsi sebagai **menebalkan huruf** `<b>` dan `<strong>` dan juga **memiringkan huruf** `<i>` dan `<em>`.

Tetapi jika anda mengikuti standar HTML5, maka untuk kata-kata yang penting dan ingin ditekankan maknanya, gunakan `<em>` atau `<strong>`. Sedangkan untuk kata yang tidak terlalu penting, tapi ingin ditulis miring atau tebal, gunakan `<i>` atau `<b>`.

## - Strong `<strong>` dan Bold `<b>`

Tag `<strong>` dan `<b>` merupakan elemen HTML yang dapat digunakan untuk meng-*highlight* kata-kata penting atau bagian teks terntu dalam sebuah halaman website.

### Perbedaan Strong `<strong>` dan Bold `<b>`

Perbedaan antara kedua tag HTML adalah **Bold** `<b>` membuat **teks hanya terlihat tebal secara visual**, sementara **Strong** `<strong>`  yang memiliki kepanjangan **‘strong importance’** (kata yang penting), juga secara semantik menekankan teks masing-masing sebagai hal yang penting dan menunjukkan bahwa itu adalah kata atau bagian teks yang bermakna.

Perbedaan ini disebabkan oleh fakta bahwa kode HTML membedakan antara **tag HTML semantik-logis** dan **fisik-visual**. Sementara **Strong** `<strong>` merujuk pada makna (semantik = teori makna) dari masing-masing bidang,  **Bold** `<b>` hanya mendefinisikan tampilan optik di browser.

```html
<p> <b>kamu terlihat</b> <strong>lemah</strong></p>
```

## - Italic `<i>` dan Emphasis `<em>`

Dalam standar HTML5, tag `<i>` digunakan untuk menandai kata-kata yang tidak memerlukan penekanan, tetapi ingin ditulis miring, seperti bahasa asing dan istilah teknis. Sedangkan tag `<em>` yang merupakan singkatan dari **emphasis** (penekanan kata).

   ```html
   <p><em>kamu terlihat</em><i>kuat</i></p>
   ```
