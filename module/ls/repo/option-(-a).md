---
date:  ""
draft: false
title: "Penggunaan Command List dengan Option -a"
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
description: "Nodule penggunaan command dasar linux list dengan option a"
---

### Pengantar penggunaan command list dengan option -a
---
Perintah ls -a pada sistem operasi Linux digunakan untuk menampilkan seluruh isi direktori, termasuk file dan folder yang bersifat tersembunyi. Secara default, ketika pengguna menjalankan perintah ls tanpa opsi tambahan, sistem hanya akan menampilkan file dan direktori yang terlihat, sementara file tersembunyi—yang biasanya diawali dengan tanda titik (.)—tidak akan muncul. File tersembunyi ini sering digunakan untuk menyimpan konfigurasi sistem atau aplikasi, seperti .bashrc, .profile, atau .gitconfig, yang berfungsi mengatur preferensi pengguna atau perilaku program di lingkungan terminal.

Dengan menggunakan opsi -a (singkatan dari all), pengguna dapat melihat seluruh file dan direktori tanpa pengecualian, termasuk entri khusus . dan .. yang masing-masing merepresentasikan direktori saat ini dan direktori induk. Hal ini sangat berguna ketika melakukan troubleshooting, mengedit konfigurasi tersembunyi, atau memeriksa struktur file yang tidak tampak pada tampilan biasa. Perintah ini membantu pengguna untuk memahami isi direktori secara lebih menyeluruh, sehingga dapat melakukan manajemen file dan sistem dengan lebih efektif.
---

### Cara penggunaan 
```
ls -a
```
<img src="/module/ls/pictures/option-a.png" alt="option -a">

penggunaan perintah ini adalah dengan mengetikkan ls -a di terminal. Misalnya, ketika berada di direktori home (~), menjalankan perintah tersebut akan menampilkan daftar file seperti .bashrc, .profile, .config, serta folder lain seperti Downloads.

```
ls -la
```
<img src="/module/ls/pictures/option-a.1.png" alt="option -a">

Perintah ls -la digunakan untuk menampilkan semua file dan direktori, termasuk yang tersembunyi, beserta detail informasinya seperti izin akses, pemilik, ukuran, dan waktu modifikasi. Kombinasi opsi -l (long listing) dan -a (all) ini memberikan tampilan yang lebih lengkap dan informatif dibandingkan ls biasa, sehingga sangat berguna untuk memeriksa atribut file, memantau hak akses, dan mengelola file tersembunyi secara lebih efisien.
