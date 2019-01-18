---
published: true
layout: post
date: '2019-01-15 16:10:31 +0700'
categories:
  - Turunan
tags: Soal
permalink: soal-turunan.html
title: Contoh Soal Turunan
---
Berikut ini adalah jawaban dari pertanyaan-pertanyaan yang masuk

Semoga membantu

Tanya :

Tentukan turunan dari $\\large f(x)=log\\;2\\left (\\frac{sin\\;x^2+e^{x^2}}{x+1} \\right )$

Jawab :

*   turunan fungsi logaritma :
    
    ${\\color{Red} f(x)=^alog\\;g(x)}\\;\\;\\;\\;maka\\;\\;\\;\\;\\;{\\color{Red} f'(x)=\\frac{g'(x)}{g(x)}\\;^alog\\;e}$
    
*   $f(x)=log\\;2\\left (\\frac{sin\\;x^2+e^{x^2}}{x+1} \\right )$ adalah fungsi logaritma dengan bilangan basis $a = 10$ , dan $g(x)= 2\\left (\\frac{sin\\;x^2+e^{x^2}}{x+1} \\right )$
    
*   kita cari turunan dari fungsi $g(x)$ terlebih dahulu :
    
    \\begin{align\*}g(x) & = & 2\\left (\\frac{sin\\;x^2+e^{x^2}}{x+1} \\right )\\\\ & = & \\frac{2sin\\;x^2+2e^{x^2}}{x+1}\\end{align\*}
    
    ingat turunan fungsi pembagian !! kita misalkan :
    
    \\begin{array}{lcl}u=2sin\\;x^2+2e^{x^2} & maka & u'=4x.cos\\;x^2+4x.e^{x^2}\\\\v=x+1 & maka & v'=1\\end{array}
    
    maka :
    
    \\begin{align\*}g'(x) & = & \\frac{u'.v-v'.u}{v^2}\\\\ & = & \\frac{4x.cos\\;x^2+4x.e^{x^2}(x+1)-1.(2.sin\\;x^2+2.e^{x^2})}{(x+1)^2}\\\\ & = & \\frac{4x^2.cos\\;x^2+4x^2.e^{x^2}+4x.cos\\;x^2+4x.e^{x^2}-2.sin\\;x^2-2.e^{x^2}}{(x+1)^2}\\\\ & = & \\frac{2(2x^2.cos\\;x^2+2x^2.e^{x^2}+2x.cos\\;x^2+2x.e^{x^2}-sin\\;x^2-e^{x^2})}{(x+1)^2}\\end{align\*}
    
    kembali ke fungsi $f(x)$ , maka kita akan dapatkan turunan :
    
    \\begin{align\*}f'(x) & = & \\frac{g'(x)}{g(x)}\\;^alog\\;e\\\\ & = & \\left (\\frac{\\frac{2(2x^2.cos\\;x^2+2x^2.e^{x^2}+2x.cos\\;x^2+2x.e^{x^2}-sin\\;x^2-e^{x^2})}{(x+1)^2}}{\\frac{2(sin\\;x^2+e^{x^2})}{(x+1)}} \\right )log\\;e\\\\ & = & \\left (\\frac{2x^2.cosx^2+2x^2.e^{x^2}+2x.cosx^2+2x.e^{x^2}-sinx^2-e^{x^2}}{(x+1)(sinx^2+e^{x^2})} \\right )log\\;e\\\\ & = & \\left (\\frac{2x^2.cosx^2+2x^2.e^{x^2}+2x.cosx^2+2x.e^{x^2}-sinx^2-e^{x^2}}{x.sinx^2+sinx^2+x.e^{x^2}+e^{x^2}} \\right )log\\;e\\end{align\*}
    
    Nah…seperti inilah hasil turunannya :
    
    \\begin{align\*}f'(x) & = & \\frac{g'(x)}{g(x)}\\;^alog\\;e\\\\ & = & \\left (\\frac{\\frac{2(2x^2.cos\\;x^2+2x^2.e^{x^2}+2x.cos\\;x^2+2x.e^{x^2}-sin\\;x^2-e^{x^2})}{(x+1)^2}}{\\frac{2(sin\\;x^2+e^{x^2})}{(x+1)}} \\right )log\\;e\\\\ & = & \\left (\\frac{2x^2.cosx^2+2x^2.e^{x^2}+2x.cosx^2+2x.e^{x^2}-sinx^2-e^{x^2}}{(x+1)(sinx^2+e^{x^2})} \\right )log\\;e\\\\ & = & \\left (\\frac{2x^2.cosx^2+2x^2.e^{x^2}+2x.cosx^2+2x.e^{x^2}-sinx^2-e^{x^2}}{x.sinx^2+sinx^2+x.e^{x^2}+e^{x^2}} \\right )log\\;e\\end{align\*}
