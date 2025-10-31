---
date:  ""
draft: false
title: "Penggunaan Command List dengan Option -C"
short: "ls -C"
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
description: "Nodule penggunaan command dasar linux list dengan option -c"
---

### Pengantar penggunaan command list dengan option -C
---
Perintah ls pada Linux digunakan untuk menampilkan daftar file dan direktori dalam suatu folder. Salah satu opsi yang bisa digunakan adalah -C. Opsi ini akan menampilkan daftar file dalam format multi-column secara horizontal, memanfaatkan lebar terminal. Dengan kata lain, file akan ditampilkan dalam beberapa kolom sehingga lebih ringkas dan mudah dibaca, terutama jika jumlah file banyak. Secara default, ls sudah menampilkan file dalam beberapa kolom ketika output diarahkan ke terminal, tetapi opsi -C memastikan tampilan kolom tetap diterapkan, bahkan saat ada opsi lain yang bisa memengaruhi format tampilan.

Penggunaan ls -C sangat berguna ketika Anda ingin melihat banyak file sekaligus tanpa scroll terlalu panjang. Ini berbeda dengan opsi -1 (angka satu) yang menampilkan file satu per baris. Dengan -C, file akan diatur secara otomatis berdasarkan lebar terminal, sehingga memaksimalkan ruang layar dan memudahkan identifikasi file secara sekilas.
---

### Cara penggunaan 

```
ls -C
```
<img src="/module/ls/pictures/option-C.png" alt="option -C">

Dengan opsi -C, ls menata daftar file dalam beberapa kolom sesuai lebar terminal, sehingga semua file bisa terlihat sekaligus tanpa harus scroll panjang, membuat tampilan lebih rapi dan memudahkan identifikasi file secara cepat.