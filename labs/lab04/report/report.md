---
## Front matter
title: "Отчёт по лабораторной работе №4"
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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.

# Задание

1. Установка NASM
2. Создание программы Hello World!
3. Компиляция и запуск программы

# Теоретическое введение

![Структурная схема ЭВМ](image/pic5.png)

![64-битный регистр процессора 'RAX'](image/pic6.png)

# Выполнение лабораторной работы

Загружаю ассемблер NASM.

![Установка ассемблера NASM](image/pic1.png)

Создаю новый каталог, перехожу в него.

![Создание каталога 'lab04'](image/pic2.png)

Создаю программу 'Hello, World!', набираю код с помощью gedit.

![Исходный код программы 'Hello, World!'](image/pic3.png)

Создаю ассемблерную программу, запускаю ее, получаю желаемый результат.

![Процесс создания и запуска ассемблерной программы](image/pic4.png)

# Выполнение самостоятельной работы

Копирую файл лабораторной, переименовываю его.

![Создание файла для самостоятельной](image/pic7.png)

Переписываю программу так чтобы она выводила мое имя и фамилию, получаю желаемый результат.

![Создание и запуск файла](image/pic8.png)

# Выводы

В результате проделанной работы я освоил процедуры компиляции и сборки программ, написанных на ассемблере NASM.
