---
published: true
layout: post
date: '2019-01-14 15:24:31 +0700'
categories:
  - Integral
tags: Materi
title: Integral
permalink: materi-integral.html
redirect_from: "/591210-materi-integral.html"
---
Bagaimana kalau kali ini kita membahas tentang integral….??!! mulai dari integral sederhana,integral subtitusi, integral parsial, integral trigonometri sampai latihan dan contoh soal integral.

pastinya dah tidak sabar buat belajar kan???

Masih ingatkah dengan turunan pada materi sebelumnya??

Nah, Integral ini nih merupakan antiturunan (tapi bukan tanjakan lho ya… :) )

Integral dinotasikan dengan :

> $\\Large \\int {\\color{DarkRed} f(x)} dx={\\color{Blue} F(x)}$

Jika $F(x)$ adalah fungsi umum yang bersifat $F ‘ (x) = f(x)$, maka $F(x)$ merupakan **antiturunan** atau integral dari $f(x)$.

Contoh

$F(x) = 3x2$ akan mempunyai turunan $F ‘(x) = 6x$

ini dapat berarti $f(x) = 6x$ maka integral dari $f(x) = 6x$ adalah $F(x) = 3x2$

Rumus Integral

> $\\Large \\int {\\color{Blue} a}x^{\\color{DarkRed} n}\\;dx=\\frac{\\color{Blue} a}{\\color{DarkRed} n}+1\\;x^{n+1}+C$ untuk $n\\neq -1$
> 
> $\\Large \\int \\frac 1x\\;dx=ln\\;x+C$

Contoh :

\\begin{align\*}1.\\;\\;\\int {\\color{Blue} 3}x^{\\color{Red} 2}dx&=&\\frac{\\color{Blue} 3}{\\color{Red} 2}+1\\;x^{\\color{Red} 2}+1+C\\\\&=&x^3\\;\\;+\\;C \\end{align\*}

\\begin{align\*}2.\\;\\;\\int \\sqrt{x}\\;dx&=&\\int x^{\\frac 12}\\;dx\\\\&=&\\frac{1}{\\frac 12+1}\\;x^{\\frac 12+1}+C\\\\&=&\\frac{\\;\\;1\\;\\;}{\\frac 32}\\;x^{\\frac 32}+C\\\\&=&\\frac 23\\;x\\sqrt{x}+C \\end{align\*}

\\begin{align\*}3.\\;\\;\\int \\frac{\\color{Blue} 3}{x^{\\color{Red} 2}}\\;dx&=& \\int {\\color{Blue} 3}.x^{\\color{Red} -2}\\;dx\\\\&=&\\frac{\\color{Blue} 3}{\\color{Red} -2+1}x^{-2+1}\\;+C\\\\&=&\\frac{3}{-1}\\;x^{-1}+C\\\\&=&-\\frac{3}{x}\\;+\\;C\\end{align\*}

Perhatikan untuk contoh **no.2** dan **no.3** fungsi $f(x)$ dinyatakan terlebih dulu sebagai fungsi pangkat,yaa…..jangan sampai terlupa !!!

Sifat -sifat :

> $\\Large \\int kf(x)\\;dx=k\\int f(x)\\;dx$
> 
> $\\Large \\int f(x)+g(x)\\;dx=\\int f(x)\\;dx+\\int g(x)dx$
> 
> $\\Large\\int f(x)-g(x)\\;dx=\\int f(x)\\;dx-\\int g(x)\\;dx$

Nah…sekarang langsung ke contoh soal integral dan pembahasannya lagi yuuuuks….

1.  Tentukan integral dari $\\Large f(x)=5x^4+\\frac{2\\pi}{3}$ !
    
    Jawab :
    
    \\begin{align\*} \\int f(x)\\;dx&=&\\int {\\color{Red} 5}x^{\\color{Red} 4}+{\\color{Blue} \\frac{2\\pi}{3}}\\;dx\\\\&=&\\frac{\\color{Blue} 5}{\\color{Red} 4}+1\\;x^{\\color{Red} 4}+1+{\\color{Blue} \\frac{2\\pi}{3}}\\;x^{\\color{Red} 0}+1+C\\\\&=&x^5+\\frac{2\\pi}{3}\\;x+C\\end{align\*}
    
2.  Jika $f(x)=\\int 3x^2-2x+6\\;dx$ dan $f(0)=-6$ maka $f(x)$=....
    
    Jawab :
    
    \\begin{align\*}f(x)&=&\\int {\\color{Blue} 3}x^{\\color{Red} 2}-{\\color{Blue} 2}x+{\\color{Blue} 6}\\;dx\\\\&=&\\frac{\\color{Blue} 3}{\\color{Red} 2}+1\\;x^{\\color{Red} 2}+1-\\frac{\\color{Blue} 2}{\\color{Red} 1}+1\\;x^{\\color{Red} 1}+1+\\frac{\\color{Blue} 6}{\\color{Red} 0}+1x^{\\color{Red} 0}+1+C\\\\f(x)&=&x^3-x^2+6x+C\\end{align\*}
    
    *   Nah, karena f(0)=-6 maka kita bisa mencari C
        
        \\begin{align\*}f(x)&=&x^3-x^2+6x+C\\\\f(0)&=&0^3-0^2+6.0+C\\\\-6&=&C\\end{align\*}
        
    *   Sehingga $f(x)=x^3-x^2+6x+6$
        
3.  Tentukan integral dari $\\Large f(x)=\\frac{6}{x^3}\\;-\\;\\frac{3}{x^2}$ !!!
    
    Jawab :
    
    Ingat …. nyatakan dalam bentuk perpangkatan terlebih dulu tiap sukunya !!!
    
    \\begin{align\*}\\int f(x)dx&=&\\int \\frac{\\color{Blue} 6}{x^{\\color{Red} 3}}\\;-\\;\\frac{\\color{Blue} 3}{x^{\\color{Red} 2}}\\;dx\\\\&=&\\int {\\color{Blue} 6}.x^{\\color{Red} -3}-{\\color{Blue} 3}.x^{\\color{Red} -2}\\;dx\\\\&=&\\frac{\\color{Blue} 6}{\\color{Red} -3}+1\\;x^{\\color{Red} -3}+1-\\frac{\\color{Blue} 3}{\\color{Red} -2}+1\\;x^{\\color{Red} -2}+1+C\\\\&=&-3x^{-2}-(-3)x^{-1}+C\\\\&=&-\\frac{3}{x^2}+\\frac 3x+C\\end{align\*}
    
4.  Tentukan integral dari $f(x)=2\\sqrt x+3x\\sqrt x$ !!!!
    
    Jawab :
    
    Ingat …. nyatakan dalam bentuk perpangkatan terlebih dulu tiap sukunya !!!
    
    \\begin{align\*}\\int f(x)dx&=&\\int 2\\sqrt x+3x\\sqrt x\\;dx\\\\&=&\\int {\\color{Blue} 2}.x^{\\color{Red} \\frac 12}+{\\color{Blue} 3}.x^{\\color{Red} \\frac 32}\\;dx\\\\&=&\\frac{\\color{Blue} 2}{\\color{Red} \\frac 12}+1\\;x^{\\color{Red} \\frac 12}+1+\\frac{\\color{Blue} 3}{\\color{Red} \\frac 32}+1\\;x^{\\color{Red} \\frac 32}+1+C\\\\&=&\\frac{\\;2\\;}{\\frac 32}x^{\\frac 32}+\\frac{\\;3\\;}{\\frac 52}x^{\\frac 52}+C\\\\&=&2.\\frac 23\\;x^{\\frac 32}+3.\\frac 25\\;x^{\\frac 52}+C\\\\&=&\\frac 43\\;x\\sqrt x+\\frac 65\\;x^2\\sqrt x+C \\end{align\*}
    

ayoooooo silahkan dicoba dengan soal-soal yang lain ya…..

tunggu materi integral yang selanjutnya yoooo !!!!
