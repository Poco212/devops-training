---
date:  ""
draft: false
title: "Penggunaan Command List dengan Option -d"
short: "ls -d"
thumb:
    image: ""
    anima: ""
    video: ""
layout: ""
weight: 
lister: 
format:
    media: "article"
    model: ""
    datum:
        data: ""
require:
    - prop: ""
      name: ""
      icon: ""
      desc: ""
metadata:
    index: 
    thumb: ""
    group: []
    author: ["Achmad Baihaqi"]
description: "Nodule penggunaan command dasar linux list dengan option -d"
---

### Pengantar penggunaan command list dengan option -d
---
Perintah ls -d pada Linux digunakan untuk menampilkan direktori itu sendiri, bukan isi dari direktori tersebut. Secara default, perintah ls akan menampilkan semua file dan subdirektori di dalam sebuah direktori. Dengan menambahkan opsi -d, kita bisa melihat direktori sebagai entitas tunggal, mirip seperti file biasa. Hal ini sangat berguna ketika kita hanya ingin mengetahui keberadaan direktori tertentu atau memeriksa atributnya tanpa menampilkan seluruh isi di dalamnya.

Opsi -d juga sering digunakan bersama wildcard untuk menampilkan daftar direktori dalam satu lokasi tanpa menampilkan file. Misalnya, perintah ls -d */ akan menampilkan semua direktori di dalam direktori saat ini, tanpa menampilkan file yang ada. Selain itu, ls -d bisa digunakan untuk menampilkan beberapa direktori sekaligus dengan menuliskan nama direktori secara bersamaan, sehingga mempermudah dalam pengelolaan direktori dan scripting di Linux. Perintah ini sederhana namun sangat efektif untuk memfilter dan menampilkan informasi direktori secara spesifik.
---

### Cara penggunaan 

```
ls -d
```
<img src="/module/ls/pictures/option-d.png" alt="option -d">

Dengan opsi -d, ls hanya menampilkan posisi direktorinya tanpa menampilkan isi dari direktori tersebut. contoh diatas dimana penggunaan command ls -d didalam direktori Downloads.

```
ls -d */
```
<img src="/module/ls/pictures/option-d.1.png" alt="option -d">

Perintah diatas untuk menampilkan semua direktori yang ada pada direktori tersebut tanpa menampilkan isi direktorinya. contoh diatas menampilkan direktori yang ada pada direktori Downloads.