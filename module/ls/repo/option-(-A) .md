---
date:  ""
draft: false
title: "Penggunaan Command List dengan Option -A"
short: "ls -a"
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
description: "Nodule penggunaan command dasar linux list dengan option -A"
---

### Pengantar penggunaan command list dengan option -A
---
Perintah ls -A pada Linux digunakan untuk menampilkan daftar semua file dan direktori di dalam sebuah folder, termasuk file tersembunyi yang diawali dengan titik (.). Berbeda dengan opsi -a, ls -A tidak menampilkan entri khusus . (direktori saat ini) dan .. (direktori induk). Hal ini membuat tampilan daftar file lebih bersih dan lebih fokus pada konten yang relevan, terutama ketika kita ingin melihat konfigurasi atau file tersembunyi tanpa terganggu oleh direktori saat ini atau induk.

Penggunaan ls -A sangat bermanfaat ketika mengeksplorasi folder yang memiliki banyak file tersembunyi, seperti folder home pengguna, atau ketika mengelola proyek yang menggunakan file konfigurasi tersembunyi seperti .git atau .env. Misalnya, menjalankan ls -A di home directory akan menampilkan file-file konfigurasi seperti .bashrc atau .profile, serta direktori biasa seperti Documents dan Downloads, tanpa menampilkan . dan .., sehingga daftar yang muncul lebih ringkas dan mudah dibaca.
---

### Cara penggunaan 
```
ls -A
```
<img src="/module/ls/pictures/option-A.png" alt="option -A" >

penggunaan perintah ini adalah dengan mengetikkan ls -A di terminal. Misalnya, ketika berada di direktori home (~), menjalankan perintah tersebut akan menampilkan daftar file seperti .bashrc, .profile, .config, serta folder lain seperti Downloads. Tanpa ada entri khusus . (direktori saat ini) dan .. (direktori induk).

```
ls -lA
```
<img src="/module/ls/pictures/option-A.1.png" alt="option -A">

Perintah ls -lA digunakan untuk menampilkan semua file dan direktori, termasuk yang tersembunyi, beserta detail informasinya seperti izin akses, pemilik, ukuran, dan waktu modifikasi. Kombinasi opsi -l (long listing) dan -A (all) ini tidak menampilkan entri khusus . (direktori saat ini) dan .. (direktori induk).