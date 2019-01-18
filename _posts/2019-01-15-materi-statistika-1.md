---
layout: post
date: '2019-01-15 16:10:31 +0700'
categories:
  - Statistika
tags: Materi
title: Statistika Bagian 1
permalink: materi-statistika-1.html
published: true

---
Wah, bicara tentang statistika kita akan berkutat dengan kehidupan sehari-hari mulai dari menghitung rata-rata uang saku perhari sampai perhitungan indeks ekonomi global…

Namun jangan khawatir, materi statistika SMA maupun SMK mempelajari perhitungan ukuran pemusatan data dan ukuran penyebaran data baik data tunggal maupun data berkelompok. Berdasarkan pengalaman waktu sekolah dulu, akan lebih efektif jika kita rangkum materi statistika menjadi suatu tabel sederhana di bawah ini…

Ukuran Pemusatan Data


| Rumus  | Data Tunggal  | Data Berkelompok  |
| ------------ | ------------ | ------------ |
| Rataan (mean) | $\\bar{x} = \\frac{\\sum x\_{i}}{n}$ | $\\bar{x} = \\frac{\\sum f\_{i}.x\_{i}}{\\sum f\_i}$ |
| Modus | $Mo$ = nilai dg frekuensi tertinggi/paling sering muncul | $Mo=T\_B+ \\frac{d\_1}{d\_1+d\_2}.i$ |
| Median | ganjil $Me=x\_{\\frac{n+1}{2}} $ genap $Me= \\frac 12.(x\_{\\frac n2}+x\_{\\frac n2+1})$ | $Me=T\_B+\\frac{\\frac n2-f\_k}{f\_{Me}}.i$ |
| Kuartil | $Q\_i = x\_{\\frac{i(n+1)}{4}}$ $\_i = 1,2,3$ | $Q\_i=T\_B+\\frac{\\frac {i.n}{4}-f\_k}{f\_Q}.i$ |
| Desil | $D\_i = x\_{\\frac{i(n+1)}{10}}$ $\_i =1,2,3,4,5,6,7,8,9$ | $D\_i=T\_B+\\frac{\\frac {i.n}{10}-f\_k}{f\_D}.i$ |

Untuk data tunggal, data diurutkan terlebih dahulu sehingga saat mencari median, kuartil dan desil kita tidak salah menentukan $x\_i$ -nya.

Yang pasti, selain hafal rumusnya juga harus tahu simbol dan cara menentukan nilainya yah Lihat keterangan berikut ini :

| $x\_i$             | \= nilai ke- i (data tunggal) |
| $x\_i$             | \= nilai tengah kelas ke-i (data berkelompok) |
| $f\_i$             | \= frekuensi ke- i |
| $n= \\sum f\_i$    | \= jumlah frekuensi/banyaknya data |
| $T\_B$             | \= tepi bawah = (BB – 0,5) |
| $d\_1$             | \= frekuensi kelas modus – frek kls di atasnya |
| $d\_2$             | \= frekuensi kelas modus – frek kls di bawahnya |
| $i$                | \= interval/panjang kelas=BA-BB+1 |
| $f\_k$             | \= frekuensi kumulatif sebelum kelas yg dimaksud |
| $f\_{Me}$          | \= frekuensi kelas Median |
| $f\_Q$             | \= frekuensi kelas kuartil |
| $f\_D$             | \= frekuensi kelas desil |
| \*letak kls Median | \= $\\frac n2$ |
| \*letak kls Kuartil| \= $\\frac{i.n}{4}$ |
| \*letak kls Desil  | \= $\\frac{i.n}{10}$ |



Langsung ke contoh dan pembahasan soal data tunggal 1. Diketahui data sebagai berikut : 5, 6, 4, 8, 7, 3, 8, 9, 4, 10 . Tentukan $\\large \\bar x$, Modus, Median, Kuartil ke-3, dan desil ke-7 ! jawab :

urutan data:

| $x\_1$ | $x\_2$ | $x\_3$ | $x\_4$ | $x\_5$ | $x\_6$ | $x\_7$ | $x\_8$ | $x\_9$ | $x\_{10}$ |
| 3, | 4, | 4, | 5, | 6, | 7, | 8, | 8, | 9, | 10 |

1.  \\begin{array}{rcl} \\bar x & = & \\frac{3+4+4+5+6+7+8+8+9+10}{10}\\\\ & = & \\frac{64}{10}\\\\ & = & 6,4 \\end{array}
2.  \\begin{array}{rcl} Mo & = & 4 dan 8\\end{array}
3.  \\begin{array}{rcl} Me & = & \\frac 12.(x\_5+x\_6)\\\\ & = & \\frac 12.(6+7)\\\\ & = & 6,5 \\end{array}
4.  \\begin{array}{rcl} Q\_3 & = & x\_{\\frac{3(10+1)}{4}}\\\\ & = & x\_{8,25}\\\\ & = & x\_8+0,25(x\_9-x\_8)\\\\ & = & 8+0,25(9-8)\\\\ & = & 8,25\\end{array}
5.  \\begin{array}{rcl} D\_7 & = & x\_{\\frac{7(10+1)}{10}}\\\\ & = & x\_{7,7}\\\\ & = & x\_8+0,7(x\_8-x\_7)\\\\ & = & 8+0,7(8-8)\\\\ & = & 8\\end{array}

Untuk data berkelompok, selanjutnya silahkan buka rangkuman materi [Statistika Bagian 2]({{site.baseurl}}/materi-statistika-2.html "Statistika Bagian 2")

Have a nice study here…
