#JS Basic files Explanation
## array.js
Berisi contoh initialisasi variabel array dan menampilkan member array baik untuk single array dan multi array
output di node dengan perintah node array.js menghasilkan output:
one
undefined
three
undefined
4
0-2
1-2

## boolean.js
Berisi contoh penggunaan tipe data boolean.
- Variabel isActive dideklarasikan sebagai boolean dengan perintah var isActive = true;
- nilai variabel isActive di tampilkan menggunakan perintah console.log
output lewat node adalah :
### Current status: true

## breakContinue.js
penggunaan perintah while untuk mengeksekusi looping. Perintah continue untuk melanjutkan stage eksekusi perintah berdasrkan evaluasi kondisi true dari fungsi if, dan perintah break untuk outscoping ekskusi program. 

## breakWithLabel.js
Berisi contoh penggunaan perintah break untuk keluar dari scope looping. Dengan menggunakan perintah break [nama label] memungkinkan break eksekusi atau keluar dari scope label tesebut 

## const.js
adalah contoh penggunaan immutable variabel menggunakan perintah const. Variabel menu dalam program ini tidak akan pernah berubah dalam keseluruhan scope program.

## doWhile.js
program ini menampilkan hasil penambahkan variabel i dengan angka 2 terus menerus sampai nilai i <= 20 menggunakan do while dimulai dari i=0. Perintah do while berfungsi untuk mengeksekusi perintah looping (berulang) setidaknya satu kali dan menghentikan jika kondisi while bernilai true.

## dynamic.js
program ini menunjukkan dynamic typing dalam javascript. variabel jumlahMahasiswa yang awalnya bertipe data numeric berubah menjadi string karena ditambahkan dengan sebuah nilai string. Disini juga membuktikan bahwa tipe data string bersifat toxic, apapun yang ditambahkan dengan string akan menjadi string.

## floatingPoint.js
menunjukkan contoh penggunaan tipe data float. Berbeda dengan integer tipe data float adalah numeric yang mengandung decimal point.

## forIn.js
menunjukkan contoh penggunaan perintah iterasi suatu koleksi data, dalam ini adalah sebuah object. berbeda dengan iterasi menggunakan for of, for in mengambil key (nama key) dari obyek, atau index dari sebuah array.  

## for.js
menunjukkan proses iterasi/ looping perintah berulang. variabel i=0 ditambahkan nilai 1 kemudian ditampilkan, berulang hingga i < 9.

## fungsiAnonim.js
sebuah variabel x dideklarasikan sebagai sebuah fungsi dengan nama pangkat yang menghasilkan sebuah fungsi lain yang tidak bernama (anonymous function). Fungsi anonim ini menerima sebuah parameter bernama angka, kemudian mengeksekusi perintah angka*angka (angka dikalikan angka). nilai angka tidak dapat diakses dari luar scope fungsi anonim.

## fungsiRecursif.js
menunjukkan program rumus factorial menggunakan fungsi yang dipanggil secara recursif (memanggil dirinya sendiri)

## if.js
menunjukkan penggunaan pemilihan kondisi (conditional execution) menggunakan perintah if

## integers.js
menunjukkan penggunaan tipe data integer.

## json.js
menunjukkan bagaimana mengakses data bertipe object(dalam format serialisasi json) perbedaan object dan json hanya pada penulisan name key. pada json name key ditulis dalam quote.

##nested.js
menunjukkan bahwa function adalah juga sebuah object yang dapat diletakkan sebagai expression di mana saja, juga di dalam function lain.

##readline.js
menunjukkan bagaimana cara menggunakan modul/libray dari nodejs untuk membuat interface yang meminta input dari user dan mengembalikan hasil input tersebut lewat sebuah callback function

##switch.js
menunjukkan perintah berdasarkan pilihan kondisi (conditional expression) menggunakan case. 

##throw.js
error handling, menggunakan blok try .. throw .. catch . throw mendefinisikan message error yang akan ditampilkan saat catch error > 0

##try.js
membungkus satu atau lebih baris perintah dalam blok yang mana jika terjadi error akan dimasukkan dalam blok catch. adapun blok finally akan selalu dieksekusi apapun yang terjadi, biasanya diisi dengan perintah pembersihan memori atau menampilkan pesan. dalam fungsi ini error akan selalu ditangkap oleh blok catch karena fungsi gakAdaFungsiIni() adalah undefined atau belum diinitialisasi sebelumnya.
##whyle.js

adalah perintah conditional structure menggunakan fungsi while


  




