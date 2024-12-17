---
## Front matter
title: "Отчёт по лабораторной работе №7"
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

Изучение команд условного и безусловного переходов. Приобретение навыков написания
программ с использованием переходов. Знакомство с назначением и структурой файла
листинга.

# Задание

1. Ознакомление с арифметическими операциями
2. Ознакомление с остальными операциями
3. Символьные и численные данные в NASM 

# Теоретическое введение

![Арифметические операции в nasm](image/pic1.png)

![Команды умножения в nasm](image/pic2.png)

# Выполнение лабораторной работы

Создаю директорию.

![Создание директории](image/pic3.png)

Перехожу в директорию.

![Переход в директорию](image/pic4.png)

Создаю новый файл.

![Создание нового файла](image/pic5.png)

Набираю исходный код программы в редакторе.

![Окно исходного кода программы](image/pic6.png)

# Выполнение самостоятельной работы

Компилирую программу.

![Компиляция программы](image/pic7.png)

Компилирую программу с использованием функций, получаю желаемый результат.

![Компиляция и запуск программы](image/pic7.png)

# Выводы

В результате проделанной работы я освоил арифметические инструкции языка ассемблера NASM.
