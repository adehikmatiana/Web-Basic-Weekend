# Review Perulangan di Javascript

Setelah kita mengetahui macam-macam perulangan yang ada pada Javascript, saat ini kita akan memahami lebih lanjut mengenai perulangan yang paling sering dipakai, yaitu **For Loop** dan **While Loop**

## Loop

_Loop_ berguna ketika Anda harus mengeksekusi baris kode yang sama berulang kali, untuk jumlah waktu tertentu atau selama kondisi tertentu benar.

Misalkan Anda ingin mengetik pesan 'Halo' 100 kali di halaman web Anda. Tentu saja, Anda harus menyalin dan menempelkan baris yang sama 100 kali. Sebaliknya, jika Anda menggunakan _loop_, Anda dapat menyelesaikan tugas ini hanya dalam 3 atau 4 baris.

Ada empat jenis _loop_ dalam _JavaScript_:

1. for loop = loop melalui blok kode beberapa kali
2. for/in a loop = loop melalui properti dari suatu objek
3. while loop = loop melalui blok kode sementara kondisi yang ditentukan benar
4. do…while loop = loop melalui blok kode sementara kondisi yang ditentukan benar

## For Loop

Sintax :

```js
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```

Statement 1 dieksekusi (satu kali) sebelum eksekusi blok kode.

Statement 2 mendefinisikan kondisi untuk mengeksekusi blok kode.

Statement 3 dieksekusi (setiap kali) setelah blok kode dieksekusi.

Contoh

```js
for (j = 0; j < 3; j++) {
  text += "Nomor kamu adalah " + j + "<br>";
}
```

Statement 1 menetapkan variabel sebelum loop dimulai (var j = 0).

Statement 2 mendefinisikan kondisi untuk menjalankan loop (saya harus kurang dari 3).

Statement 3 meningkatkan nilai (j ++) setiap kali blok kode dalam loop telah dieksekusi.

1. **Statement 1**

   Biasanya kita dapat menggunakan Statement 1 untuk menginisialisasi variabel yang digunakan dalam loop (j = 0).

   Ini tidak selalu terjadi, _JavaScript_ tidak peduli. Statement 1 adalah opsional.

   Anda dapat menginisiasi banyak nilai dalam Statement 1 (dipisahkan dengan koma)

   Contoh:

   ```js
   for (j = 0, len = cars.length, text = ""; j < len; j++) {
     text += cars[j] + "<br>";
   }
   ```

2. **Statement 2**

   Seringkali Statement 2 digunakan untuk mengevaluasi kondisi variabel awal.

   Ini tidak selalu terjadi, _JavaScript_ tidak peduli. Statement 2 juga opsional.

   Jika Statement 2 mengembalikan _true_, loop akan memulai lagi,jika itu mengembalikan false, loop akan berakhir.

   > Jika Anda menghilangkan pernyataan 2, Anda harus memberikan jeda di dalam loop. Kalau tidak, loop tidak akan pernah berakhir. Ini akan membuat browser kita terkadang error.

3. **Statement 3**

   Seringkali statement 3 menambah nilai variabel awal.

   Ini tidak selalu terjadi, JavaScript tidak peduli, dan statement 3 adalah opsional.

   Statement 3 dapat melakukan hal-hal seperti kenaikan negatif (i--), kenaikan positif (i = i + 15), atau apa pun.

   Statement 3 juga dapat dihilangkan (seperti ketika Anda menambah nilai Anda di dalam loop):

   Contoh :

   ```js
   <script>
   var i = 0;
   var len = cars.length;
   for (; i < len; ) {
   text += cars[i] + "<br>";
   i++;
   }
   </script>
   ```

## While Loop

**While Loop** akan dijalankan selama kondisi yang ditentukan benar. Di dalam loop sementara, kita harus menyertakan pernyataan yang akan mengakhiri loop pada suatu titik waktu. Jika tidak, loop kita tidak akan pernah berakhir dan browser kita mungkin macet.

Sintax :

```js
while (condition) {
  // code block to be executed
}
```

Contoh :

kode dalam loop akan berjalan, berulang-ulang, selama variabel (j) kurang dari 5:

```js
while (j < 5) {
  text += "The number is " + j;
  j++;
}
```

> Jika kita lupa menambah variabel yang digunakan dalam kondisi tersebut, loop tidak akan pernah berakhir. Ini akan membuat browser kita loading terus-menerus.

### Do / while loop

**Do While** adalah varian dari _while loop_. _Loop_ ini akan mengeksekusi blok kode sekali, sebelum memeriksa apakah kondisinya benar, maka itu akan mengulang loop selama kondisinya benar.

Sintax :

```js
do {
  // code block to be executed
} while (condition);
```

Contoh :

di bawah ini menggunakan _do / while loop_. _Loop_ akan selalu dieksekusi setidaknya sekali, walaupun kondisinya salah, karena blok kode dieksekusi sebelum kondisi diuji:

```js
do {
  text += "Urutan anda adalah ke- " + j;
  j++;
} while (j < 10);
```

> Jangan lupa untuk menambah variabel yang digunakan dalam kondisi tersebut, jika tidak, loop tidak akan pernah berakhir!
