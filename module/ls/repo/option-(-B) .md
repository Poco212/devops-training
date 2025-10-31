---
date:  ""
draft: false
title: "Penggunaan Command List dengan Option -B"
short: "ls -B"
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
description: "Nodule penggunaan command dasar linux list dengan option -B"
---

### Pengantar penggunaan command list dengan option -b
---
Perintah ls pada Linux digunakan untuk menampilkan isi direktori. Salah satu opsi yang tersedia adalah -B atau --ignore-backups. Opsi ini berguna untuk mengabaikan file backup saat menampilkan daftar file di direktori. File backup biasanya adalah file yang dibuat otomatis oleh editor teks atau sistem dengan menambahkan karakter ~ di akhir nama file, misalnya oktober.pdf~. Dengan menggunakan ls -B, file-file semacam ini tidak akan ditampilkan, sehingga tampilan menjadi lebih bersih dan fokus hanya pada file utama.

Opsi ini sangat berguna ketika kita ingin melihat isi direktori tanpa terganggu oleh file sementara atau file cadangan yang biasanya tidak relevan. Kombinasi -B juga dapat dipadukan dengan opsi lain, misalnya -l untuk menampilkan daftar file dengan format panjang atau -a untuk menampilkan semua file termasuk file tersembunyi, tetapi tetap mengabaikan file backup.
---

### Cara penggunaan 
```
ls 
```
<img src="/module/ls/pictures/option-B.png" alt="option -B" >

Pada contoh terdapat beberapa file yang telah dibackup dengan menandakan simbol ~ pada ujung filenya. Misalkan dalam direktori terdapat file finance.pdf, finance.pdf~, oktober.pdf, dan oktober.pdf~.

```
ls -B
```
<img src="/module/ls/pictures/option-B-1.png" alt="option -B" >

 Saat perintah dijalankan, output yang ditampilkan hanya finance.pdf dan oktober.pdf, sedangkan file backup yang berakhiran ~ tidak ditampilkan. Hal ini membuat tampilan direktori lebih bersih dan memudahkan pengguna untuk fokus pada file utama tanpa terganggu oleh file cadangan sementara.

```
ls -lb
```
<img src="/module/ls/pictures/option-B.2.png" alt="option -B">

Perintah ls -lB digunakan untuk menampilkan semua file dan direktori, termasuk yang tersembunyi, beserta detail informasinya seperti izin akses, pemilik, ukuran, dan waktu modifikasi. Kombinasi opsi -l (long listing) dan -B  untuk melihat file utama tanpa menampilkan file backupannya.