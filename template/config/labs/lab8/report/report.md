---
## Front matter
title: "Математические основы защиты информации и информационной безопасности"
subtitle: "Отчет к лабораторной №8: Целочисленная арифметика многократной точности"
author: "Бекбузарова Роза"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
  - \usepackage{unicode-math}
  - \setmathfont{Latin Modern Math}
---

# Цель работы
Основной целью работы является реализовать разными алгоритмами целочисленную арифметику многократной точности.

# Выполнение лабораторной работы

## Алгоритм 1 (сложение неотрицательных целых чисел)
![](image/1.PNG)

## Алгоритм 2 (вычитание неотрицательных целых чисел)
![](image/2.PNG)

## Алгоритм 3 (умножение неотрицательных целых чисел столбиком)
![](image/3.PNG)

## Алгоритм 4 (быстрый столбик)
![](image/4.PNG)

## Алгоритм 5 (деление многоразрыдных целых чисел)
![](image/5.PNG)

# Вывод
В ходе выполнения лабораторной работы было реализован разными алгоритмами целочисленную арифметику многократной точности.