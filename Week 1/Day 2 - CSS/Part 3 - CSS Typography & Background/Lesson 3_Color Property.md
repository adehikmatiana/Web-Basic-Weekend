# Property Color

Saat ini CSS mendukung setidaknya 4 notasi penulisan warna:

1. Keyword

     Dalam banyak contoh kode program kita sebelum ini, saya selalu menggunakan **keyword** warna untuk property color. **keyword** ini pada dasarnya adalah nama warna dalam bahasa inggris, seperti red, black, white, dll.

     Pada awalnya, CSS hanya mendukung 17 **keyword** warna dasar, yakni: _aqua, black, blue, fuchsia, gray, green, lime, maroon, navy, olive, orange, purple, red, silver, teal, white, dan yellow_. Semua warna ini berasal dari sistem _VGA Windows_. Warna-warna ini dikenal juga dengan istilah _classic internet color_.

     Saat ini **keyword** warna CSS telah dikembangkan hingga mendukung 147 warna tambahan. Warna-warna ini disebut sebagai 147 _SVG colors_ (atau X11 _colors_). Nama warnanya sangat beragam dan cukup unik seperti: turquoise, whitesmoke, rebeccapurple dan peachpuff.

     List lengkap untuk **keyword** warna tambahan ini dapat dilihat di : [developer.mozilla.org](developer.mozilla.org) atau [www.w3.org/TR/css3-color3](www.w3.org/TR/css3-color3).

2. #RRGGBB / #RGB

     Format warna seperti #12F5A5 adalah format warna **#RGB**. Format warna ini sangat sering digunakan di dalam _CSS_, sehingga amat penting untuk dipahami.

     **RGB** adalah singkatan dari **Red Green Blue** (merah hijau biru). Dalam desain media visual seperti televisi atau komputer, model warna inilah yang umumnya digunakan. Seluruh warna lain didapat dari perpaduan ketiga warna dasar **RGB**.

     Sesuai dengan singkatannya, format **#RRGGBB** adalah cara penulisan warna **RGB** dimana RR mewakili warna merah (_red_), GG mewakili warna hijau (_green_), dan BB mewakili warna biru (_blue_). Masing masing warna ini memiliki 256 tingkat ‘kepekatan’, yang diwakili dari angka 0 hingga 255.

     Pada format **#RRGGBB**, masing-masing nilai warna harus di konversi ke angka _heksadesimal_. Angka _heksadesimal_ adalah angka ‘khusus’ yang terdiri dari 16 digit, yakni angka 0 – 9 dan huruf A - F. Nilai 255 pada bilangan desimal sama dengan FF pada bilangan _heksadesimal_.

     Untuk menghasilkan warna putih, penulisannya adalah: #FFFFFF. 2 digit FF pertama mewakili warna merah (red), 2 digit FF selanjutnya mewakili warna hijau (green) dan 2 digit terakhir mewakili warna biru (blue). Untuk menghasilkan warna kuning pekat, penulisannya menjadi: #FFFF00.

3. rgb(rr, gg, bb) / rgba(rr, gg, bb, aa)

     Format warna **rgb(rr, gg, bb)** dan **rgba(rr, gg, bb, aa)** sebenarnya hampir sama dengan format **#RRGGBB**, cuma kali ini kita tidak harus menggunakan angka _heksadesimal_.

     Notasi **rgb(rr, gg, bb)** bisa ditulis menggunakan nilai desimal (basis 10) maupun dalam satuan persen.

4. hsl(hh, ss, ll) / hsla(hh, ss, ll, aa)

     Format warna **hsl(hh, ss, ll)** dan pasangannya **hsla(hh, ss, ll, aa)** merupakan format penulisan warna yang baru saja ditambahkan dalam spesifikasi _CSS3_.

     **HSL** merupakan singkatan dari _Hue, Saturation_ dan _Lightness_ (atau kadang disebut juga dengan Luminance). HSL menggunakan konsep ‘mencari warna’ menggunakan color wheel (roda warna).
     Color wheel adalah sebuah lingkaran yang berisi berbagai jenis warna, dimana setiap warna memiliki posisi tertentu (dalam satuan derajat).
