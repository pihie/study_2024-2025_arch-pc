---
## Front matter
title: "Отчёт по лабораторной работе №5"
author: "Межеловский Александр Игоревич"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение практических навыков работы в Midnight Commander. Освоение инструкций языка ассемблера mov и int.

# Задание

1. Ознакомление с mc
2. Запуск программы без использования функций
3. Запуск программы с использованием функций 

# Теоретическое введение

![Комбинации клавиш для облегчения работы с mc](image/pic1.png)

![Примеры использования директив](image/pic2.png)

# Выполнение лабораторной работы

Запускаю мс.

![Рабочее окно mc](image/pic3.png)

Создаю новый каталог, перехожу в него и создаю новый файл.

![Создание каталога 'lab05'](image/pic4.png)

Компилирую программу, получаю желаемый результат.

![Компиляция и запуск программы](image/pic5.png)

Компилирую программу с использованием функций, программа запускается корректно.

![Компиляция и запуск программы с использованием функций](image/pic6.png)

# Выполнение самостоятельной работы

Запускаю программу без использования функций.

![Компиляция и запуск программы](image/pic7.png)

Компилирую программу с использованием функций, программа запускается корректно.

![Компиляция и запуск программы с использованием функций](image/pic8.png)

# Выводы

В результате проделанной работы я приобрел практические навыки работы в Midnight Commander. Освоил инструкции языка ассемблера mov и int.
