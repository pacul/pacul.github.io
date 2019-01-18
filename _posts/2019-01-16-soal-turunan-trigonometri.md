---
published: true
layout: post
date: '2019-01-15 16:09:31 +0700'
categories:
  - Turunan
tags: Soal
permalink: soal-turunan-trigonometri.html
title: Contoh Soal Turunan Trigonometri
---
Contoh soal kali ini membahas tentang turunan trigonometri

Yang masih bingung silahkan disimak materi tanya jawab berikut….ok???!!!

Tanya :

Buktikan bahwa :

$y=sin\\;x\\;\\;\\;maka\\;\\;\\;y\\;'=cos\\;x$

dan

$y=cos\\;x\\;\\;\\;maka\\;\\;\\;y\\;'=-sin\\;x$

Jawab :

Kita pakai rumus turunan

$\\Large f'(x)=\\lim\_{h\\rightarrow 0}\\frac{f(x+h)-f(x)}{h}$

diketahui

*   $f(x)=sin\\;x$
    
*   $f(x+h)=sin\\;(x+h)$
    

ingat rumus

${\\color{Red} sin\\;A-sin\\;B=2.cos\\;\\frac 12(A+B).sin\\frac 12(A-B) }$

maka

\\begin{align\*} sin(x+h)-sin\\;x&=&2.cos\\;\\frac 12(x+h+x).sin\\frac 12(x+h-x)\\\\&=&2.cos\\frac 12(2x+h).sin\\frac 12h\\end{align\*}

Kita subtitusikan ke rumus turunan

\\begin{align\*}f'(x)&=&\\lim\_{h \\to 0}\\frac{f(x+h)-f(x)}{h}\\\\&=&\\lim\_{h \\to 0}\\frac{sin\\;(x+h)-sin\\;x}{h}\\\\&=&\\lim\_{h \\to 0}\\frac{2.cos\\frac 12(2x+h).sin\\frac 12h}{h}\\\\&=&\\lim\_{h \\to 0}2.cos\\frac 12(2x+h).\\lim\_{h \\to 0}\\frac{sin\\frac 12h}{h}\\\\&=&\\lim\_{h \\to 0}2.cos\\frac 12(2x+h).\\frac 12\\\\&=&2.cos\\frac 12(2x+0).\\frac 12\\\\&=&2.cos\\;x.\\frac 12\\\\f'(x)&=&{\\color{Red} cos\\;x}\\end{align\*}

Nah… untuk $f(x)=cos\\;x$ berlakui cara yang sama, namun kita pakai rumus yang ini nieh…

$\\Large {\\color{Red} cos\\;A-cos\\;B=-2.sin\\frac 12(A+B).sin\\frac 12(A-B) }$

Silahkan dicoba sendiri yaaaah……

Ok, gud Luck…
