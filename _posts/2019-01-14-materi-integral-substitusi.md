---
published: true
layout: post
date: '2019-01-14 15:24:31 +0700'
categories:
  - Integral
tags: Materi
title: Integral Substitusi
permalink: materi-integral-substitusi.html
redirect_from: "/161235-materi-integral-subtitusi.html"
---
Yuuuuuuk belajar lagi…!!!!

Kali ini khusus kita bahas tentang integral subtitusi, contoh soal dan pembahasannya ok…!!!

Jangan sampai ketinggalan ya…

Jika u suatu fungsi yang dapat didiferensialkan dan r suatu bilangan rasional tak nol, maka

$\\int {\\color{Red} (u(x))^r.\\;u'(x)}\\;dx={\\color{Red} \\frac {1}{r+1}(u(x))^{r+1}+c}$ di mana $c$ adalah konstanta dan $r\\neq -1$

Nah…udah lihat rumus integral yang di atas sono tuh…???

Pusing,tidak..??? hehehe…lebih baik langsung di contohin aja ya….

contoh soal dan pembahasan integral subtitusi :

1.  $\\int (5x-3)^4dx = $....
    
    Jawab :
    
    *   kita misalkan $u=5x-3$ dan fungsi $u$ dapat diturunkan menjadi
    
    \\begin{align}{\\color{Red} u}&=&{\\color{Red} 5x-3}\\\\\\frac{du}{dx}&=&5\\\\dx&=&{\\color{Blue} \\frac 15\\;du} \\end{align}
    
    *   Baru kita subtitusikan ke soal :
    
    \\begin{align\*}\\int({\\color{Red} 5x-3})^4{\\color{Blue} dx}&=&\\int {\\color{Red} u}^4.{\\color{Blue} \\frac 15\\;du}\\\\&=&{\\color{Blue} \\frac 15}.\\frac{1}{4+1}.{\\color{Red} u}^{4+1}+C\\\\&=&\\frac{1}{25}\\;{\\color{Red} u}^5+C\\\\&=&\\frac{1}{25}\\;({\\color{Red} 5x-3})^5+C\\end{align\*}
    
    Jangan sampai lupa untuk mengembalikan permisalan kita $u\\; =\\;{\\color{Red} 5x-3}$ ya…..
    
2.  $\\int (2x-1)(3x^2-3x+5)^8\\;dx = $...
    
    Jawab :
    
    *   kita misalkan $u=3x^2-3x+5$ dan fungsi $u$ dapat diturunkan menjadi :
    
    \\begin{align\*}{\\color{Red} u}&=&{\\color{Red} 3x^2-3x+5}\\\\\\frac {du}{dx}&=&6x-3\\\\dx&=&{\\color{Blue} \\frac{1}{6x-3}\\;du}\\end{align\*}
    
    *   Baru kita subtitusikan ke soal :
    
    \\begin{align\*}\\int (2x-1)(3x^2-3x+5)^8\\;dx&=&\\int (2x-1).{\\color{Red} u}^8\\;{\\color{Blue} \\frac{1}{6x-3}\\;du}\\\\&=&\\int \\frac{2x-1}{\\color{Blue} 3(2x-1)}\\;{\\color{Red} u}^8\\;{\\color{Blue} du}\\\\&=&\\int \\frac{1}{3}\\;{\\color{Red} u}^8\\;{\\color{Blue} du}\\\\&=&\\frac 13.\\frac{1}{8+1}.{\\color{Red} u}^{8+1}+C\\\\&=&\\frac{1}{27}.{\\color{Red} u}^9 +C\\\\&=&\\frac{1}{27}({\\color{Red} 3x^2-3x+5})^9+C\\end{align\*}
    
3.  $\\int x^2\\sqrt{2x^3+1}\\;dx \\;=\\; $...
    
    Jawab :
    
    *   kita misalkan $u=2x^3+1$ dan fungsi $u$ dapat diturunkan menjadi
    
    \\begin{align\*}{\\color{Red} u}&=&{\\color{Red} 2x^3+1}\\\\\\frac{du}{dx}&=&6x^2\\\\dx&=&{\\color{Blue} \\frac{1}{6x^2}\\;du} \\end{align\*}
    
    *   Baru kita subtitusikan ke soal :
    
    \\begin{align\*}\\int x^2\\sqrt{2x^3+1}\\;dx&=&\\int x^2.\\sqrt{\\color{Red} u}\\;.{\\color{Blue} \\frac{1}{6x^2}\\;du}\\\\&=&\\int \\frac{x^2}{\\color{Blue} 6x^2}.{\\color{Red} u}^{\\frac 12}\\;{\\color{Blue} du}\\\\&=&\\int \\frac{1}{6}.{\\color{Red} u}^{\\frac 12}\\;{\\color{Blue} du}\\\\&=&\\frac 16.\\frac{1}{\\frac 12+1}\\;{\\color{Red} u}^{\\frac 12+1}+C\\\\&=&\\frac 16.\\frac 23\\;{\\color{Red} u}^{\\frac 32}+C\\\\&=&\\frac 19\\;{\\color{Red} u}\\sqrt {\\color{Red} u}+C\\\\&=&\\frac 19({\\color{Red} 2x^3+1})\\sqrt{\\color{Red} 2x^3+1}+C\\end{align\*}
    
4.  $\\int sin\\;x.cos^2x\\;dx = …$
    
    Jawab :
    
    *   kita misalkan $u=cos\\;x$ maka
    
    \\begin{align\*}{\\color{Red} u}&=&{\\color{Red} cos\\;x}\\\\\\frac{du}{dx}&=&-sin\\;x\\\\du&=&-sin\\;x\\;dx \\end{align\*}
    
    *   sehingga :
    
    \\begin{align\*}\\int sin\\;x.{\\color{Red} cos}^2{\\color{Red} x}\\;dx&=&\\int -{\\color{Red} u}^2\\;du\\\\&=&-\\frac 13.{\\color{Red} u}^3+C\\\\&=&-\\frac 13.{\\color{Red} cos}^3{\\color{Red} x}+C\\end{align\*}
    
5.  $\\int cos\\;5x\\;sin^4\\;5x\\;dx= …$
    
    Jawab :
    
    *   kita misalkan $u=sin\\;5x$ maka :
    
    \\begin{align\*}{\\color{Red} u}&=&{\\color{Red} sin\\;5x}\\\\\\frac{du}{dx}&=&5.cos\\;5x\\\\\\frac{du}{5}&=&cos\\;5x\\;dx\\end{align\*}
    
    *   sehingga :
    
    \\begin{align\*}\\int cos\\;5x\\;{\\color{Red} sin}^4\\;{\\color{Red} 5x}\\;dx&=&\\int \\frac 15.{\\color{Red} u}^4\\;du\\\\&=&\\frac 15.\\frac 15.{\\color{Red} u}^5+C\\\\&=&\\frac {1}{25}{\\color{Red} sin}^5\\;{\\color{Red} 5x}+C\\end{align\*}
    

latihan soal dan pembahasan integral subtitusi aljabar dan trigonometri-nya dicukupkan dulu ya, kapan-kapan ditambah lagi soalnya.

Selamat belajar ………..!!!!
