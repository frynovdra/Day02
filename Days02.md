# Day 02 : Javascript
Primitve data type bukanlah object dan tidak memiliki method
Dulu deklarasi variabel di javascript hanyalah `var` semenjak munculnya
Scoope seperti `let` dan `const`, menggunakan Scoope bisa lebih aman dari deklarasi yang sama sejak ES6 muncul

Primary data type : Boolean , String, Number

### String dan pengolahannya :
* String adalah kumpulan huruf symbol dan angka yang ditandai dengan :  ` , ’,  “ ,Semisal  : **n = "Harimau"** jadi  n adalah string.
* `Let z = new String(‘Hallo’)` z menjadi sebuah object, dengan String sebagai key dan hallo sebagai key valuenya.
* Bisa di concatenation seperti string.Misal : `n = "Harimau"` dan `m = " Lapar"` maka output dari `console.log(m+n)` adalah `Harimau Lapar`.
* `String.split(‘ ‘)` mengubah string menjadi array berdasarkan tanda spasi sebagai pemisah dan `String.join( )` menggabungkannya lagi
* `.toLowerCase()` dan `toUpperCase()` , merubah semua huruf di string menjadi huruf kecil atau kapital semua 
* Slice, memotong strig dimulai dari indeks yang dipotong dari arah kiri jika ada lagi indeks keduanya adalah akhir yang dipotong misal `namastring.slice(3,5)` jadi yang dipotong adalah indeks sebelum 3 dan Sebelum  5

### Number dan pengolahannya :
* Ana banyak Jenis (integer , decimal/float, angle Diwali nol, hexa decimal, NaN(not a number).
* Not a number `NaN` adalah jenis kata yang bukan number tapi mash dibaca sebagai number.

### Boolean : 
* Nilai nya ada dua yaitu true dan false.
* Berfungsi nutuk mengecek kebenaran pada suatu pernyataan.
* Null = tidak ada nilai sama sekali.
* Undefined = variabel yang tidak ada valuenya.

### Special data type Object:
* Deklarasi masih menggunakan let dan const `Let obj = {wanna : “Hitam”}`
* `Console.log(namaobject.keyproperties)` untuk log value pada object, contohnya `console.log(obj.warna)`
* Const dikecualikan ke object dan array
* `JSON.parse(JSON.stringify(nama object))` adalah perintah untuk mengakali agar object yang terhubung dengan object baru tidak terupdate.
* Loop juga bisa diterapkan kepada objek.

### Special data type Array :
* Array adalah struktur structur data yang berisi beberapa elemen, cara mendeklarasikannya = `let namaArray = [element]`
* Assign , menambahkan value ke array, instruksinya  : `array[indeks] = masukan value` 
* Pop menghapus item pada indeks paling akhir `arr.pop()`
* Push menambahkan indeks paling akhir `arr.push()`
* Shift dan unshift, menghapus di indeks awal `arr.shift()` dan `arr.unshit()`
* Array juga bisa di concatenate seperti string, seperti :  `namaArray.Concat(nama array lagi yang akan digabung)`
* Data pada Array juga bisa disort melalui `namaArray.sort()`
* indexOf mengindeks item yang ingin kita cari `namaArray.indexOf()`
* Splice memotong aray berdasarkan indeks `namaArray.splice(indeks)`
* Array bisa juga Looping
* Complex Array adalah aray yang berisi beberapa objek
