# **JAVASCRIPT- Array**
> Array adalah tipe data list order yang dapat menyimpan tipe data apapun didalamnya. Array dapat menyimpan tipe data string, Number, Boolean, dan lainnya.
```
let namaSiswa = ["umi", "mita", "obi"]; 
console.log(namaSiswa);
```
# Array-Properties
- .length
- constructor
- index
- input
- prototype


# Array-Methods
- .push() : untuk menambah item array dari urutan terakhir
- .pop() : untuk menghapus item array index pertama
- .shift() : untuk menghapus item array pada index pertama
- .unshift() : untuk menambah item array 
- .sort() : untuk mengurutkan secara Ascending atau Descending Alphanumeric

# Looping Array
- .forEach() : untuk melakukan perulangan pada setiap elemen array.
- .map() : untuk melakukan perulangan dengan cara membuat array baru.

## Recursif
> adalah suatu teknik pemrograman yang menggunakan function.
```
function recursif(){
    // kode lainnya recursif();
}
```
```
function namaFuncRekursif() {
  if (condition) {
    // Base case
  } else {
    // Recursion call
    namaFuncRekursif();
  }
}
```
### Algoritma recursive mempunyai 2 komponen, yaitu:
1. Base Case Kasus dasar untuk menyelesaikan permasalahan. Base case akan dikunjungi jika rekursi berakhir (kondisi untuk berhenti terpenuhi), serta mengembalikan nilai tanpa melakukan rekursi kembali.
2. Recursion Call Permasalahan yang ada tentunya akan diperkecil dengan melakukan pemanggilan function itu sendiri (recursion call). Permasalahan dapat diperkecil dengan mengurangi atau memecahkan data input pada setiap pemanggilannya hingga mencapai base case.
## Regex
> adalah deretan karakter spesial yang menggambarkan pattern atau pola untuk pencarian teks pada sebuah string atau document. cara membuat pola regex ada 2 yaitu:
- regex literal dengan menuliskan pola yang ingin dicari di antara dua slash / seperti ini:
```
const namaVariable = /pola/;
```
- fungsi regex
```
const namaVariable = new RegExp("pola");
```

## Object Oriented Programming (OOP)
> suatu paradigma dalam pemrograman yang bersifat principle, jadi dapat di terapkan pada bahasa programming selain Javascript seperti Ruby, Python dan Java.
### Pilar pada OOP
- Encapsulation : konsep tentang pengikatan data atau metode berbeda yang disatukan menjadi satu unit.
- Abstraction : untuk memerintahkan suatu fungsi, tanpa harus mengetahui bagaimana fungsi tersebut.
- Inheritance : kemampuan untuk membentuk class baru yang memiliki fungsi atau mirip dengan fungsi sebelumnya.
- Polymorpishm : kemampuan suatu pesan atau data untuk diproses lebih dari satu bentuk.

> OOP pada JS
secara umum tipe data dapat dibagi menjadi 2:
- Data primitive : tipe data yang hanya untuk menyimpan data.
- non primitive : tipe data untuk selain menyimpan data, tetapi juga mempunyai metode bawaan (built-in method) utk memodifikasi dan operasi oleh programing.

## Modulus 
> Operasi modulus merupakan operasi untuk menghasilkan sisa dari hasil pembagian.
##  Assyncronous
> adalah saat kita mengeksekusi perintah satu persatu dan berurutan. Analoginya seperti kita sedang mengantri di kasir atau loket. Ketika ada 1 perintah masuk maka dia akan dieksekusi terlebih dahulu. Jika perintah belum selesai dan sudah ada perintah baru maka perintah kedua (yang baru) akan mengantri sampai perintah 1 selesai. Proses seperti ini disebut blocking dan membuat perintah kita tereksekusi dengan lambat.
```
Contoh :

console.log("antrian 1");
console.log("antrian 2");
console.log("antrian 3");

// output
// antrian 1
// antrian 2
// antrian 3
Kode di atas bersifat synchronous yaitu kode dijalankan baris per baris. Maka output kode di atas tereksekusi sesuai urutan perintahnya.
```
## Asynchronous
> cara untuk membuat proses asynchronous, yaitu:
1. setTimeout
2. setInterval
```
setTimeout(() => {
  console.log("Cuci baju"); // proses asynchronous
}, 1000);
console.log("Menyapu");
console.log("Mengepel");
console.log("Memasak");

// 1000 ms = 1 second

// Output:
// Menyapu
// Mengepel
// Memasak
// Cuci baju
```

## Github Lanjutan
> pull request : merupakan sebuah perintah untuk menggabungkan (merge) kode yang telah dimodifikasi dengan repositori utama atau lainnya.