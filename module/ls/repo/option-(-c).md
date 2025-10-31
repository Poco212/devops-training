---
date:  ""
draft: false
title: "Penggunaan Command List dengan Option -c"
short: "ls -c"
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

### Pengantar penggunaan command list dengan option -c
---
Perintah ls -c pada Linux adalah opsi dari perintah ls yang digunakan untuk menampilkan daftar file dan direktori dengan urutan berdasarkan waktu perubahan status inode (ctime). Waktu ctime mencakup perubahan metadata file, seperti perubahan hak akses, kepemilikan, atau pembuatan link, bukan perubahan isi file itu sendiri. Dengan kata lain, jika sebuah file baru saja mengalami perubahan hak akses atau dipindahkan, perintah ini akan memperbarui waktu tampilnya sebagai file terbaru ketika menggunakan opsi -c. Hal ini berbeda dengan opsi default ls -l atau opsi -t, yang biasanya menampilkan file berdasarkan waktu modifikasi isi file (mtime).

Opsi -c sering digunakan bersamaan dengan -l untuk mendapatkan tampilan yang lebih lengkap, termasuk informasi izin, pemilik, ukuran, dan tanggal perubahan status file. Misalnya, perintah ls -lc akan menampilkan daftar file dengan format long listing tetapi menyortir dan menandai waktu yang ditampilkan berdasarkan ctime. Opsi ini sangat berguna ketika administrator sistem ingin melacak file yang baru saja mengalami perubahan atribut, bukan konten, sehingga memudahkan pemantauan keamanan atau audit sistem.
---

### Cara penggunaan 

```
ls -lc
```
<img src="/module/ls/pictures/option-c.png" alt="option -c">

Perintah ini menampilkan daftar file dan direktori di folder home dengan format long listing, tetapi tanggal yang ditampilkan adalah waktu perubahan status inode (ctime), bukan waktu modifikasi isi file. Misalnya, jika sebuah file baru saja diubah hak akses atau kepemilikannya, perintah ini akan menempatkan file tersebut sesuai urutan waktu ctime terbaru, sehingga memudahkan pengguna untuk melihat file yang baru saja mengalami perubahan atribut atau metadata, bukan hanya kontennya.