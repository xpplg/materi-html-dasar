# Berkenalan dengan HTML

***Apa itu HTML ??***

<p align="justify">HTML merupakan singkatan dari Hyper Text Markup Language. HTML adalah sebuah bahasa standar untuk pembuatan halaman web. Dengan adanya HTML, kita dapat membedakan struktur yang tersusun dari sebuah halaman melalui tag atau elemen-elemen penyusunnya.</p>
<p align="justify">Elemen atau tag pada HTML dikenali oleh browser seperti google chrome, firefox atau Ms Edge, dll. Browser tersebut mengidentifikasi setiap elemen penyusun HTML dan ditampilkan sesuai karakteristik elemen tersebut. Contohnya sebuah elemen paragraph akan ditampilkan sebagai tulisan panjang, atau sebuah elemen pranala/link akan dicetak dengan warna biru dan ketika mouse mendekat kursornya berubah menjadi telunjuk, dsb.</p>

<p align="justify">Contoh sebuah halaman HTML sederhana:</p>

```html
  <!DOCTYPE html>
  <html>
  <head>
  <title>Page Title</title>
  </head>
  <body>

  <h1>My First Heading</h1>
  <p>My first paragraph.</p>

  </body>
  </html>
```
<p align="justify">Dari contoh di atas kita dapat mengidentifikasi elemen-elemen nya seperti berikut:</p>

* element  ```<!DOCTYPE html>``` mengartikan bahwa dokumen ditulis dengan versi HTML5
* elemen ```<html>``` adalah elemen induk atau elemen utama yang sering disebut juga root element dari sebuah halaman HTML.
* elemen ```<head>``` berisi informasi tentang halaman HTML yang sedang dibuat
* elemen ```<title>``` adalah judul dari halaman HTML yang akan tampil di tab browser.

***Elemen pada HTML***
<p align="justify">Elemen atau sering disebut dengan tag pada HTML adalah penyusun dari sebuah halaman web yang dapat dikenali oleh browser dan ditampilkan oleh browser sesuai karakteristik masing-masing.</p>

<p align="justify">Sebuah elemen HTML terdiri dari tag pembuka(start/open tag), atribut (attribute), isi (content), dan tag penutup(close tag).</p>


pada ilustrasi di atas merupakan sebuah elemen paragraph dibuka dengan tag pembuka ```<p>``` . Di dalam tag pembuka tersebut terdapat atribut class yang disematkan ke dalam tag. Isi atau content dari sebuah tag paragraph ```<p>``` akan ditampilkan sebagai paragraf. lalu terakhir sebuah tag ditutup dengan sebuah tag penutup.

*catatan*
Tidak semua elemen HTML memiliki tag penutup seperti ```<input> <img> <meta>```.

***Elemen di dalam elemen (nested element)***
<p align="justify">sebuah elemen HTML dapat terisi dengan elemen-elemen lain di dalamnya. Semua dokumen HTML yang kita lihat di halaman web terdiri dari kumpulan elemen bersarang atau elemen yang mengandung elemen lain di dalamnya.</p>

Contohnya halaman berikut: