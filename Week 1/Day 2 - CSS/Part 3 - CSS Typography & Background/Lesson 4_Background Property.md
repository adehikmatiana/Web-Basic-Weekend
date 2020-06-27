# CSS Background

## Property _background-color_

   Seperti namanya, property _background-color_ digunakan untuk mengubah warna latar belakang dari _element HTML_. Nilai default property ini adalah _transparant_, yang berarti akan ‘melewatkan’ warna parent element-nya.

   Selain itu, kita bisa menggunakan berbagai nilai warna, seperti _keyword,#RGB, rgb(), rgba(), hsl(),_ dan _hsla()_. Berikut adalah contoh penggunaan dengan menggunakan _keyword_

   ```css
   body {
     background-color: Green;
   }
   ```

## Property _background-image_

   Property _background-image_ berfungsi untuk memasukkan gambar ke dalam background sebuah element HTML.

   CSS mendukung berbagai format file gambar, walaupun ini sebenarnya lebih dibatasi oleh web browser. Tipe file gambar yang sering digunakan adalah JPG, PNG, GIF, dan SVG.

   Nilai dari _background-image_ adalah ‘path’ gambar, yakni alamat file gambar yang akan diinput. Alamat ini bisa berupa alamat relatif seperti ‘image/background/nama_gambar.jpg’ maupun alamat absolut seperti `http://www.google.com/doodles/googles-new-logo`. Alamat ini ditempatkan ke dalam keyword ‘url()’ seperti contoh berikut:

   ```css
   body {
     background-image: url("image/background/gambar.jpg");
   }
   div {
     background-image: url(`http://www.google.com/doodles/googles-new-logo`);
   }
   ```

## Property background-position

   Untuk mengatur posisi _background_, kita bisa menggunakan property _background-position_. Property ini membutuhkan nilai dalam satuan _length_ seperti _pixel, em, persen_ maupun _keyword_: _top, bottom, right, left,_ dan _center_.

   Perhitungan posisi _background_ dimulai dari titik koordinat 0,0 pada sudut kiri atas element hingga ke sudut kanan bawah. Nilai default untuk _background-position_ adalah 0%, 0%. Sehingga apabila property ini tidak ditulis, gambar akan ‘dibentangkan’ mulai dari sudut kiri atas.

   Property _background-position_ bisa diisi dengan 1, 2, 3 atau 4 nilai. Yang paling mudah dipahami adalah penulisan dengan 2 nilai, dimana nilai pertama digunakan untuk posisi sumbu x (horizontal), dan nilai kedua untuk posisi sumbu y (vertikal). Format penulisannya adalah sebagai berikut:

   ```css
   background-position: posisi_sumbu_x posisi_sumbu_y;
   ```

   Perhatikan bahwa diantara kedua nilai dipisah dengan karakter spasi.
   Sebagai contoh, apabila saya ingin menempatkan gambar background yang berjarak 100px dari sisi kiri element dan 50px dari atas, saya bisa menggunakan:

   ```css
   background-position: 100px 50px;
   ```
