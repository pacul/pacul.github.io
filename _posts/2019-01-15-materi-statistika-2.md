---
published: true
layout: post
date: '2019-01-15 16:09:31 +0700'
categories:
  - Statistika
tags: Materi
permalink: materi-statistika-2.html
title: Statistika Bagian 2
---
Materi statistika 2 merupakan kelanjutan dari [Statistika Bagian 1]({{site.baseurl}}/materi-statistika-2.html "Statistika Bagian 1"), sebelumnya telah kita punya rangkuman rumus statistika dan contoh soal pada data tunggal, nah sekarang kita akan berlatih contoh soal data berkelompok yuk…

Diketahui data sebagai berikut :

Nomor   | fi
------- | ---
10 – 14 | 3
15 – 19 | 6
20 – 24 | 9
25 – 29 | 8
30 – 34 | 4

Tentukanlah rataan, median, modus, kuartil pertama ($Q\_1$) dan desil ke delapan ($D\_8$) !

jawab:

1.  Untuk mencari rataan kita buat kolom bantuan $x\_i$ yaitu nilai tengah dan $f\_i.x\_i$ sebagai berikut :
    
    Nomor | $fi$ | $xi$ | $fi.xi$
    ----- | ---- | ---- | -------
    10 – 14 | 3 | 12 | 36    
    15 – 19 | 6 | 17 | 102    
    20 – 24 | 9 | 22 | 198    
    25 – 29 | 8 | 27 | 216    
    30 – 34 | 4 | 32 | 128    
    $\\sum$ | 30 |  | 680
    
    \\begin{array}{rcl}\\bar{x} & = & \\frac{\\sum f\_{i}.x\_{i}}{\\sum f\_i}\\\\ & = & \\frac{680}{30}\\\\ & = & 22,67\\end{array}
    
2.  untuk mencari median kita buat kolom tambahan $f\_k$ yaitu frekuensi kumulatif sebagai berikut :
    
    Nomor | $fi$ | $fk$    
    ----- | ---- | ---- 
    10 – 14 | 3 | 3    
    15 – 19 | 6 | 9    
    20 – 24 | 9 | 18    
    25 – 29 | 8 | 26    
    30 – 34 | 4 | 30    
    $\\sum$ | 30 | 
    
    kita tentukan kelas median terlebih dulu, $\\frac n2=\\frac{30}{2}=15$ (lihat $f\_{k}$-nya) data ke $15$ terletak di kelas ke $3$ dimana:
    
    $T\_B=20-0,5=19,5$
    
    $i=5$
    
    $f\_k=9$ ingat $f\_k$ disini adalah frekuensi kumulatif sebelum kelas ke $3$
    
    $f\_{Me}=9$ lihat $f\_i$ kelas ke $3$
    
    maka :
    
    \\begin{array}{rcl}Me & = & T\_B+ \\frac {\\frac {n}{2}-f\_{k}}{f\_{Me}}.i\\\\ & = & 19,5+\\frac{15-9}{9}.5\\\\ & = & 19,5+\\frac {6}{9}.5\\\\ & = & 19,5+3,33\\\\ & = & 22,83\\end{array}
    
3.  untuk mencari modus, tidak dibutuhkan kolom tambahan sehingga perhatikan tabel soal
    
    Nomor | $fi$   
    ----- | ---- 
    10 – 14 | 3    
    15 – 19 | 6    
    20 – 24 | 9    
    25 – 29 | 8    
    30 – 34 | 4    
    $\\sum$ | 30
    
    kita tentukan kelas modus terlebih dulu, kelas dengan frekuensi terbesar yaitu kelas ke $3$
    
    $T\_B=20-0,5=19,5$
    
    $i=5$
    
    $d\_1=9-6=3$ ingat selisih kelas ke $3$ dengan kelas ke $2$
    
    $d\_2=9-8=1$ ingat selisih kelas ke $3$ dengan kelas ke $4$
    
    maka
    
    \\begin{array}{rcl}Mo & = & T\_B+\\frac{d\_{1}}{d\_{1}+d\_{2}}.i\\\\ & = & 19,5+\\frac{3}{3+1}.5\\\\ & = & 19,5+\\frac{3}{4}.5\\\\ & = & 19,5+3,75\\\\ & = & 23,25\\end{array}
    
4.  untuk mencari kuartil pertama kita pakai tabel untuk mencari median
    
    Nomor | $fi$ | $fk$  
    ----- | ---- | ----   
    10 – 14 | 3 | 3    
    15 – 19 | 6 | 9    
    20 – 24 | 9 | 18    
    25 – 29 | 8 | 26    
    30 – 34 | 4 | 30    
    $\\sum$ | 30 | 
    
    kita tentukan kelas $Q\_1$ terlebih dulu, $\\frac {i.n}{4}=\\frac{1.30}{4}=7,5$ , (lihat $f\_{k}$ -nya) data ke 7,5 terletak di kelas ke $2$ dimana:
    
    $T\_B=15-0,5=14,5$
    
    $i=5$
    
    $f\_k=3$ ingat $f\_k$ disini adalah frekuensi kumulatif sebelum kelas ke $2$ (kelas $Q\_1$)
    
    $f\_{Q1}=6 lihat f\_i$ kelas ke $2$
    
    maka
    
    \\begin{array}{rcl}Q\_1 & = & T\_B+\\frac{\\frac {i.n}{4}-f\_k}{f\_Q}.i\\\\ & = & 14,5+\\frac{7,5-3}{6}.5\\\\ & = & 14,5+\\frac{4,5}{6}.5\\\\ & = & 14,5+3,75\\\\ & = & 18,25\\end{array}
    
5.  untuk mencari desil ke $8$ kita pakai tabel untuk mencari median
    
    Nomor | $fi$ | $fk$  
    ----- | ---- | ----   
    10 – 14 | 3 | 3    
    15 – 19 | 6 | 9    
    20 – 24 | 9 | 18    
    25 – 29 | 8 | 26    
    30 – 34 | 4 | 30    
    $\\sum$ | 30
    
    kita tentukan kelas $D\_8$ terlebih dulu,$ \\frac{i.n}{10}=\\frac{8.30}{10}=24$ ,(lihat $f\_{k}$-nya) data ke $24$ terletak di kelas ke $4$ dimana:
    
    $T\_B=25-0,5=24,5$
    
    $i=5$
    
    $f\_k=18$ ingat $f\_k$ disini adalah frekuensi kumulatif sebelum kelas ke $4$ (kelas $D\_8$)
    
    $f\_{D8}=8$ lihat $f\_i$ kelas ke $4$
    
    maka
    
    \\begin{array}{rcl}D\_8 & = & T\_B+\\frac{\\frac {i.n}{10}-f\_k}{f\_D}.i\\\\ & = & 24,5+\\frac{24-18}{8}.5\\\\ & = & 24,5+\\frac{6}{8}.5\\\\ & = & 24,5+3,75\\\\ & = & 28,25\\end{array}
    

oke…selamat mencoba….
