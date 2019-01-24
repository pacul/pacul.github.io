---
published: true
layout: post
date: '2019-01-15 16:06:31 +0700'
categories:
  - Turunan
tags: Materi
permalink: materi-turunan-fungsi-aljabar.html
title: Turunan Fungsi Aljabar
redirect_from: "/3922-materi-turunan-fungsi-aljabar.html"
---
Materi Turunan (derivatif) mencakup materi turunan fungsi aljabar, turunan fungsi trigonometri, gradien garis singgung dan persamaan garis singgung pada suatu kurva tertentu, titik stasioner, fungsi naik dan fungsi turun. Lumayan banyak juga,yah…kita coba mulai dari fungsi aljabar dulu.

Turunan fungsi $f ‘ (x)$ didefinisikan sebagai :

$\\Large f' (x) = \\underset{h\\rightarrow 0}{lim}\\:\\frac{f(x + h) - f(x)}{h}$

Rumus-rumus Turunan :

untuk a = konstanta

*   $\\large f(x) = ax^n$ maka $\\large f'(x) = an.x^{n-1}$
*   $\\large f(x) = a$ maka $\\large f'(x) = 0$
*   $\\large f(x) = x$ maka $\\large f'(x) = 1$

jika $U = u(x) dan V = v(x)$ adalah suatu fungsi

$f(x) = U + V$ maka $f'(x) = U' + V'$

$f(x) = U - V$ maka $f'(x) = U' - V'$

$f(x) = U\\times V$ maka $f'(x) = U'.V + V'.U$

$f(x) = \\frac UV$ maka $f'(x) = \\frac {U'.V - V'.U}{V^2}$

$f(x) = U^n$ maka $f'(x) = n.U^{n-1}.U'$ dinamakan aturan rantai

Jangan sampai lupa yah, setiap fungsi yang hendak diturunkan, pastikan dinyatakan dalam bentuk perpangkatan terlebih dulu, let’s cekidot …

Contoh dan pembahasan turunan fungsi:

1.  Tentukan turunan pertama dari :
    
    $f(x) = 2x^5$
    
    Jawab :
    
    \\begin{array}{rcl} f'(x) & = & 2.5.x^{5-1}\\\\ & = & 10x^4\\end{array}
    
2.  $f(x) = \\frac 3x$
    
    Jawab :
    
    nyatakan dalam bentuk pangkat terlebih dulu menjadi $f(x) = 3.x^{-1}$ maka :
    
    \\begin{align\*}f'(x) & = & 3.(-1).x^{-1-1}\\\\ & = & (-3).x^{-2}\\\\ & = & -\\frac{3}{x^2}\\end{align\*}
    
3.  $f(x) = \\sqrt{7x}$
    
    Jawab :
    
    nyatakan dalam bentuk pangkat terlebih dulu menjadi $f(x) = \\sqrt7 .\\;x^{\\frac{1}{2}}$ maka :
    
    \\begin{align\*}f'(x) & = & \\sqrt 7. \\frac 12.x^{\\frac 12-1}\\\\ & = & \\frac 12. \\sqrt 7.x^{-\\frac{1}{2}}\\\\ & = & \\frac 12. \\sqrt 7. \\frac{1}{\\sqrt x}\\\\ & = & \\frac{\\sqrt 7}{2\\sqrt x}.\\frac{\\sqrt x}{\\sqrt x}\\\\ & = & \\frac{\\sqrt{7x}}{2x}\\end{align\*}
    
4.  $\\large f(x) = \\frac{3x-2}{x+1}$
    
    Jawab :
    
    kita misalkan \\begin{array}{rcl} U=3x-2 & maka & U'=3\\\\ V=x+1 & maka & V'=1\\end{array}
    
    maka :
    
    \\begin{align\*}f'(x) & = & \\frac{U'.V-V'.U}{V^2}\\\\ & = & \\frac{(3)(x+1)-(1)(3x-2)}{(x+1)^2}\\\\ & = & \\frac{3x+3-3x+2}{(x+1)^2}\\\\ & = & \\frac{5}{(x+1)^2}\\end{align\*}
    
5.  $f(x) = (3x^2 -5)^4$
    
    Jawab :
    
    kita misalkan $U = 3x^2 -5$
    
    maka :
    
    $U'=6x$ dan $n = 4$
    
    lalu kita pakai $f'(x) = n.U^{n-1}.U'$ ( aturan rantai )
    
    \\begin{align\*}f'(x) & = & 4.(3x^2-5)^{4-1}.6x\\\\ & = & 24x(3x^2-5)^3\\end{align\*}
    

berlatihlah untuk mencari turunan fungsi yang sederhana terlebih dahulu, lalu kembangkan dengan berlatih mencari turunan perkalian dan pembagian fungsi, setelah itu yang soal aturan rantai baru dimantapkan dengan sungguh-sungguh karena seringkali keluar sebagai soal ujian.
