# Template Dasar HTML Bootstrap CDN

**CDN** merupakan singkatan dari **Content Delivery Network** yang secara sederhana bisa disebut sebagai jaringan harddisk online super cepat yang bisa diakses oleh siapa saja selama terhubung ke internet. Penyedia layanan CDN cukup banyak, mulai dari yang gratis hingga berbayar.

Jika tidak ingin download file bootstrap, kita bisa mendapatkan nya pada link  `https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/ css/bootstrap.min.css.`

Dengan demikian, tag `<link>` yang dipakai untuk mengimport kode CSS Bootstrap bisa ditulis menjadi:

1. CDN CSS Bootstrap

    ```html
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/ 4.1.1/css/bootstrap.min.css">
    ```

2. CDN jQuery, Pooper, JS Bootstrap

    ```js
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    ```

## Bootstrap Modul

Modul yang ada di dalam Bootstrap, yakni fitur apa saja yang tersedia di dalam Bootstrap.

Secara garis besar, Bootstrap terdiri dari 4 kelompok modul:

1. **Modul Layout** berisi kode Bootstrap untuk pengelolaan layout, yang terdiri dari Bootstrap grid system, wrapping container, flexible media object, dan responsive utility class.

2. **Modul Content** berisi koleksi kode CSS untuk mengubah tampilan konten, diantaranya
Bootstrap reboot (CSS reset versi Bootstrap), pengelolaan font, tabel dan gambar.

3. **Modul Components** merupakan modul utama Bootstrap yang berisi berbagai komponen web hasil perpaduan kode HTML, CSS dan JavaScript. Terdapat puluhan komponen Bootstrap, mulai dari membuat tombol alert, popover, breadcrumb, carousel, navbar, pagination, tooltips, form, dll. Setiap komponen ini akan kita bahas dengan detail nantinya.

4. **Modul Utilities** berisi berbagai komponen kecil atau modul bantu, seperti pengaturan margin dan padding, pengaturan warna, posisi teks, clearfix, float, efek bayangan (shadow), visibility, dll.
