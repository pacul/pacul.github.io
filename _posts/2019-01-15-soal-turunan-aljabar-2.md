---
published: true
layout: post
date: '2019-01-15 16:07:31 +0700'
categories:
  - Turunan
tags: Soal
permalink: soal-2-turunan-aljabar.html
title: Soal 2 Turunan Aljabar
---
Setelah mencoba soal turunan bagian pertama, mari kita coba latihan soal turunan dan pembahasan soal turunan yang lain yuk ……..jangan lupa rumus-rumus turunan kemarin yah !!!

{:start="6"}
6.  Jika $g(x)=\\left ( 5-3x \\right )^{10}$ maka $g ‘(2) = $ ….
    
    A. -30
    
    B. -10
    
    C. 30
    
    D. 60
    
    E. 90
    
    Jawab :
    
    *   misal $u=5-3x$ maka $u'=-3$ $n=10$
        
    *   kita pakai aturan rantai sehingga :
        
        \\begin{align\*}g'(x) & = & {\\color{Red} n.u^{n-1}.u'}\\\\ & = & 10.(5-3x)^{10-1}.(-3)\\\\ & = & (-30)(5-3x)^9\\\\g'(2) & = & (-30)(5-3.2)^9\\\\ & = & (-30)(-1)^9\\\\ & = & 30 \\end{align\*}
        
7.  Jika $f(x)=x^3-\\frac{x}{x^2-1}$ maka $f ‘(x) = $…
    
    A. $3x^2+\\frac{x^2+1}{(x^2-1)^2}$
    
    B. $3x^2-\\frac{x^2-1}{(x^2-1)^2}$
    
    C. $x^2+\\frac{3x+1}{(x^2-1)^2}$
    
    D. $x^2-\\frac{3x+1}{(x^2-1)^2}$
    
    E. $3x^2-\\frac{3x+1}{(x^2-1)^2}$
    
    Jawab :
    
    *   terdapat dua suku yang harus diturunkan, kita turunkan suku yang pertama secara langsung dan suku yang kedua menggunakan rumus ${\\color{Red} y=\\frac uv}\\;\\;\\; maka\\;\\;\\;{\\color{Red} y'=\\frac{u'v-v'u}{v^2}}$
        
    *   perhatikan suku kedua misalkan :
        
        \\begin{array}{lcl}u=x & \\Leftrightarrow & u'=1\\\\v=x^2-1 & \\Leftrightarrow & v'=2x \\end{array}
        
        maka
        
        \\begin{align\*}f(x) & = & x^3-\\frac{x}{x^2-1}\\\\f'(x) & = & 3x^2-\\left \[ \\frac{u'.v-v'.u}{v^2} \\right \]\\\\ & = & 3x^2-\\left \[ \\frac{1.(x^2-1)-2x(x)}{(x^2-1)^2} \\right \]\\\\ & = & 3x^2-\\left \[ \\frac{x^2-1-2x^2}{(x^2-1)^2} \\right \]\\\\ & = & 3x^2-\\left \[ \\frac{-x^2-1}{(x^2-1)^2} \\right \]\\\\ & = & 3x^2+\\frac{x^2+1}{(x^2-1)^2} \\end{align\*}
        
8.  Turunan pertama dari $\\frac{(x+2)(x+1)}{(x+3)}$ adalah …..
    
    A. ${y}'=\\frac{x^2+9x+7}{x^2+9}$
    
    B. ${y}'=\\frac{x^2+6x+11}{x^2+6x+9}$
    
    C. ${y}'=\\frac{x^2+6x+7}{x^2+6x+9}$
    
    D. ${y}'=\\frac{x^2+9x+11}{x^2+6x+9}$
    
    E. $\\frac{x^2+6x+11}{x^2+9}$
    
    Jawab :
    
    *   untuk model soal yang seperti ini kita kalikan pembilangnya sehingga menjadi bentuk kuadrat, didapat $y=\\frac{x^2+3x+2}{x+3}$ baru kita gunakan ${\\color{Red} y=\\frac uv}\\;\\;\\;maka\\;\\;\\;{\\color{Red} y'=\\frac{u'v-v'u}{v^2}}$
        
    *   misalkan
        
        \\begin{array}{lcl}u=x^2+3x+2 & \\Leftrightarrow & u'=2x+3\\\\v=x+3 & \\Leftrightarrow & v'=1 \\end{array}
        
    *   maka :
        
        \\begin{align\*}y' & = & \\frac{u'.v-v'u}{v^2}\\\\ & = & \\frac{(2x+3)(x+3)-(1)(x^2+3x+2)}{(x+3)^2}\\\\ & = & \\frac{2x^2+9x+9-x^2-3x-2}{(x+3)^2}\\\\ & = & \\frac{x^2+6x+7}{x^2+6x+9} \\end{align\*}
        
9.  Diketahui $y=\\sqrt{3-4x}$ maka $ \\frac{\\partial y}{\\partial x}=$ ….
    
    A. $\\frac{1}{2\\sqrt{3-4x}}$
    
    B. $\\frac{1}{\\sqrt{3-4x}}$
    
    C. $\\frac{2}{\\sqrt{3-4x}}$
    
    D. $\\frac{-1}{\\sqrt{3-4x}}$
    
    E. $\\frac{-2}{\\sqrt{3-4x}}$
    
    Jawab :
    
    *   nyatakan y dalam bentuk pangkat menjadi $y=\\left ( 3-4x \\right )^{\\frac 12}$
        
    *   nah…ingat kita pakai aturan rantai
        
        \\begin{align\*}y' & = & n.u^{n-1}.u'\\\\ & = & \\frac 12.(3-4x)^{\\frac{1}{2}-1}.(-4)\\\\ & = & (-2)(3-4x)^{-\\frac 12}\\\\ & = & \\frac{-2}{\\sqrt{3-4x}}\\end{align\*}
        
10. Jika $f(3+2x)=4-2x+x^2$ maka $f ‘ (1)$ = …
    
    A. -4
    
    B. -2
    
    C. -1
    
    D. 0
    
    E. $\\frac{1}{2}$
    
    Jawab :
    
    *   masih ingatkah materi komposisi fungsi ….???
    *   kita misalkan : \\begin{align\*}{\\color{Blue} 3+2x} & = & {\\color{Blue} y}\\\\ {\\color{Red} x} & = & \\frac{y-3}{2}\\end{align\*}
        
    *   subitusikan ke $f(3+2x)=4-2x+x^2$ menjadi : \\begin{align\*}f({\\color{Blue} 3+2x}) & = & 4-2{\\color{Red} x}+{\\color{Red} x}^2 \\\\f({\\color{Blue} y}) & = & 4-2\\left ( \\frac{y-3}{2} \\right )+\\left (\\frac{y-3}{2} \\right )^2\\\\f(y) & = & 4-y+3+\\left ( \\frac{y^2-6y+9}{4} \\right )\\\\ & = & \\frac{16-4y+12+y^2-6y+9}{4}\\\\f(y) & = & \\frac{y^2-10y+37}{4}\\\\f(x) & = & \\frac {1}{4}x^2-\\frac{10}{4}x+\\frac{37}{4}\\end{align\*}
        
    *   baru kita turunkan tiap sukunya \\begin{align\*}f(x) & = & \\frac 14x^2-\\frac{10}{4}x+\\frac{37}{4}\\\\f'(x) & = & \\frac 12x^2-\\frac{10}{4}\\\\f'(1) & = & \\frac 12-\\frac 52\\\\f'(1) & = & -\\frac 42\\\\ & = & -2\\end{align\*}
        

Selamat belajar…..yang semangat yah !!!!
