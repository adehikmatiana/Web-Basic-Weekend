# Form Element

Elemen formulir atau `<form>` berfungsi untuk kontrol yang dapat berinteraksi dengan pengguna untuk mengirim informasi kembali ke server. Element ini biasanya digunakan untuk mengumpulkan informasi dari pengunjung situs web, seperti pendaftaran, komentar, pendapat, dan banyak lagi. Ini juga **sangat penting dalam proses login** yang disediakan oleh beberapa situs web.

Seluruh objek *form* (*text box, radio button, checkbox,* dsb) harus berada di antara tag pembuka `<form>` dan tag penutup `</form>`. Tag ini berguna sebagai *container* atau penampung dari *form*. Berapapun jumlah objek *form* yang berada di antara tag ini, masih dianggap sebagai satu *form*.

## Text-box

**Objek *form* yang paling sederhana (dan juga paling banyak digunakan) adalah *text box***. *Text box* terlihat sebagai kotak persegi panjang di mana pengguna bisa mengetik sesuatu ke dalam kotak ini. *Text box* disebut juga dengan ***'input type text'***, karena untuk membuat *text box*, kita menambahkan atribut `type="text"` pada tag `<input>`.

Tag `<input>` merupakan tag *‘universal’* yang digunakan untuk membuat hampir seluruh objek *form*. **Nilai dari atribut `type` inilah yang akan membedakan jenis objek *form* yang satu dengan yang lain**. Penulisan tag `<input>` juga tidak memerlukan tag penutup atau dikenal sebagai *self closing tag*.

Contoh pembuatan *text box* di dalam HTML:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form type</title>
</head>

<body>
    <div class="contoh">
        <label for="name">Nama Lengkap</label>
        <input type="text" name="name" id="name" required>
    </div>
</body>

</html>
```

Jika dijalankan maka hasilnya akan seperti ini:

![textbox](img/5/textbox.png)

## Text-area

`<textarea>` biasanya digunakan untuk menginput suatu teks secara multi line. TextArea sendiri bisa berisi angka ataupun karakter dengan jumlah yang tidak terbatas.

Textarea ini memiliki ukuran default nya, tetapi kita juga bisa mendefinisikan ukuran panjang lebar nya TextArea dengan menggunakan CSS.

Contoh `<textarea>`:

```html
<div class="textarea">
    <label for="komen">Komentar</label>
    <textarea name="komen"></textarea>
</div>
```

Jika dijalankan maka hasilnya akan seperti ini:

![textarea](img/5/textarea.png)

## Check-box

Checkbox adalah objek form yang tampilannya berupa kotak persegi dimana pengguna bisa men-klik (ceklist) kotak isian untuk memilih. Untuk membuat checkbox kita menggunakan atribut `type="checkbox"` pada tag `<input>`.

```html
<p><input type="checkbox" name="cth1"> front end developer</p>
<p><input type="checkbox" name="cth1"> back end developer</p>
<p><input type="checkbox" name="cth3"> mobile developer</p>
```

Jika dijalankan maka hasilnya akan seperti ini:

![check](img/5/check.png)

## Radio button

Radio Button ini merupakan kebalikan dari checkbox. Dimana radio button membatasi pengguna hanya bisa memilih salah satu pilihan saja.

```html
<p><input type="radio" name="jenis_kelamin"> Laki-laki</p>
<p><input type="radio" name="jenis_kelamin"> Perempuan</p>
```

![radio](img/5/radio.png)
