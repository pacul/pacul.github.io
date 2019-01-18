---
published: true
layout: post
date: '2019-01-14 15:24:31 +0700'
categories:
  - Fungsi
tags: Materi
permalink: materi-komposisi-fungsi.html
title: Komposisi Fungsi
---
Komposisi fungsi merupakan penggabungan operasi dua fungsi secara berurutan yang akan menghasilkan sebuah fungsi baru.

Komposisi dua fungsi $f(x)$ dan $g(x)$ dinotasikan dengan simbol $(f \\circ g)(x)$ atau $(g \\circ f)(x)$.

dimana :

*   $(f\\circ g)(x)=f(g(x))$
    
*   $(g\\circ f)(x)=g(f(x))$
    

Sifat Komposisi Fungsi
----------------------

$(g \\circ f)(x) \\neq (f \\circ g)(x)$ $(f\\circ (g\\circ h))(x)=((f\\circ g)\\circ h)(x)$

Contoh :

diberikan fungsi :

*   ${\\color{Red} f(x)=2x+1}$
    
*   ${\\color{Blue} g(x)=3x^2}$
    
*   ${\\color{DarkGreen} h(x)=\\frac{1}{x+4}}$
    

1.  $(f\\circ g)(x)$ = ….?
    
    fungsi $g(x)$ disubtitusikan ke fungsi $f(x)$
    
    \\begin{align\*}(f\\circ g)(x)&=&{\\color{Red} f}({\\color{Blue} g(x)})\\\\&=&{\\color{Red} f}({\\color{Blue} 3x^2})\\\\&=&{\\color{Red} 2(}{\\color{Blue} 3x^2}{\\color{Red} )+1}\\\\(f\\circ g)(x)&=&6x^2+1 \\end{align\*}
    
2.  $(g\\circ h)(x)$ = ….?
    
    fungsi h(x) disubtitusikan ke fungsi g(x)
    
    \\begin{align\*}(g\\circ h)(x)&=&{\\color{Blue} g}({\\color{DarkGreen} h(x)})\\\\&=&{\\color{Blue} g}({\\color{DarkGreen} \\frac{1}{x+4}})\\\\&=&{\\color{Blue} 3}\\left ({\\color{DarkGreen} \\frac{1}{x+4}} \\right )^{\\color{Blue} 2}\\\\&=&3\\left (\\frac{1}{x^2+8x+16} \\right )\\\\(g\\circ h)(x)&=&\\frac{3}{x^2+8x+16} \\end{align\*}
    
3.  $(h\\circ g\\circ f)(x)$ =…?
    
    fungsi $f(x)$ disubtitusikan terlebih dahulu ke fungsi $g(x)$ nah, hasilnya baru disubtitusikan ke fungsi $h(x)$, perhatikan warna mewakili subtitusi ….ok!
    
    \\begin{align\*}(h\\circ g\\circ f)(x)&=&{\\color{DarkGreen} h}({\\color{Blue} g}({\\color{Red} f(x)}))\\\\&=&{\\color{DarkGreen} h}({\\color{Blue} g}({\\color{Red} 2x+1}))\\\\&=&{\\color{DarkGreen} h}({\\color{Blue} 3}({\\color{Red} 2x+1})^{\\color{Blue} 2})\\\\&=&{\\color{DarkGreen} h}(3(4x^2+4x+1))\\\\&=&{\\color{DarkGreen} h}(12x^2+12x+3)\\\\&=&\\frac{\\color{DarkGreen} 1}{\\left (12x^2+12x+3 \\right ){\\color{DarkGreen} +4}}\\\\&=&\\frac{1}{12x^2+12x+7}\\end{align\*}
    

Bagaimana contoh diatas? sudah cukup jelas,kan ?!

Berhati-hatilah dalam mensubtitusikan ya….

Mencari salah satu fungsi jika komposisi fungsi diketahui

1.  Mencari $g(x)$ jika $f(x)$ dan $(f\\circ g)(x)$ diketahui
    
    _contoh soal dan pembahasan :_
    
    Diketahui $(f\\circ g)(x)=19-6x$ dan ${\\color{Red} f(x)=3x+1}$
    
    Tentukan fungsi ${\\color{Blue} g(x)}$ !
    
    Jawab :
    
    \\begin{align\*}(f\\circ g)(x)&=&19-6x\\\\{\\color{Red} f}({\\color{Blue} g(x)})&=&19-6x\\\\{\\color{Red} 3(}{\\color{Blue} g(x)}{\\color{Red} )+1}&=&19-6x\\\\{\\color{Red} 3(}{\\color{Blue} g(x)}{\\color{Red} )}&=&19-6x{\\color{Red} -1}\\\\{\\color{Blue} g(x)}&=&\\frac{18-6x}{3}\\\\{\\color{Blue} g(x)}&=&6-2x \\end{align\*}
    
2.  Mencari $f(x)$ jika $g(x)$ dan $(f\\circ g)(x)$ diketahui
    
    _contoh soal dan pembahasan :_
    
    Diketahui $(f\\circ g)(x)=2x+1$ dan ${\\color{Blue} (g)(x)=x+3}$
    
    Tentukan ${\\color{Red} f(x)}$ !
    
    Jawab :
    
    \\begin{align\*}(f\\circ g)(x)&=&2x+1\\\\f({\\color{Blue} g(x)})&=&2x+1\\\\f({\\color{Blue} x+3})&=&2x+1\\end{align\*}
    
    Kita misalkan dulu :
    
    \\begin{align\*}{\\color{Blue} x+3}&=&{\\color{DarkGreen} y}\\\\x&=&{\\color{DarkGreen} y-3}\\end{align\*}
    
    Subtitusikan kembali ke fungsi :
    
    \\begin{align\*}f({\\color{Blue} x+3})&=&2x+1\\\\f({\\color{DarkGreen} y})&=&2({\\color{DarkGreen} y-3})+1\\\\f({\\color{DarkGreen} y})&=&2y-6+1\\\\f({\\color{DarkGreen} y})&=&2y-5\\\\f(x)&=&2x-5\\end{align\*}
    

Selamat mencoba…dan jangan pernah putus asa.
