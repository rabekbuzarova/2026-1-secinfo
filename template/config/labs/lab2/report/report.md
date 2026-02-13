---
title: "Математические основы защиты информации и информационной безопасности"
subtitle: "Отчёт по лабораторной работе №2: Шифрование гаммированием"
author: "Бекбузарова Роза Алисхановна"

lang: ru-RU
toc-title: "Содержание"

bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

toc: true
toc-depth: 2
lof: true
lot: true
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt

polyglossia-lang:
  name: russian
  options:
    - spelling=modern
    - babelshorthands=true
polyglossia-otherlangs:
  name: english

babel-lang: russian
babel-otherlangs: english

mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9

biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric

figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lolTitle: "Листинги"

indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float}
  - \floatplacement{figure}{H}
---
# Цель работы

Реализовать шифры: маршрутное шифрование, шифрование с помощью решеток и таблица Виженера

# Выполнение лабораторной работы

## Маршрутное шифрование

![](image/1.PNG)

## Шифрование с помощью решеток

![](image/2.PNG)
![](image/3.PNG)

## Таблица Виженера

![](image/4.PNG)
![](image/5.PNG)

# Вывод

В ходе выполнения лабораторной работы были реализованы три метода шифрования