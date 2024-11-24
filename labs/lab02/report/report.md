---
## Front matter
title: "Отчет по лабораторной работе №2"
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

Целью работы является изучить идеологию и применение средств контроля версий. Приобрести практические навыки по работе с системой git.

# Задание

1. Настройка GitHub
2. Базовая настройка git
3. Создание SHH ключа
4. Создание рабочего пространства и репозитория курса на основе шаблона
5. Создание репозитория курса на основе шаблона
6. Настройка каталога курса

# Теоретическое введение

![Основные команды git (1)](image/1.png)

![Основные команды git (2)](image/2.png)

# Выполнение лабораторной работы

Учетная запись github у меня уже была поэтому пропускаю этот шаг. Произвожу первоначальную настройку git.

![Настройка git (1)](image/3.png)

![Настройка git (2)](image/4.png)

Создаю ключ ssh.

![Создание ssh ключа](image/5.png)

Создаю директорию в которой будет храниться копия репозитория.

![Создание папки для клонирования репозитория](image/6.png)

Клонирую репозиторий в раннее созданную папку.

![Клонирование репозитория](image/7.png)

Создаю необходимые каталоги

![Создание каталогов](image/8.png)

Сохраняю проделанные изменения, отправляю файлы на сервер.

![Загрузка изменений на сервер](image/9.png)

# Выполнение самостоятельной работы

Самостоятельная работа предполагает загрузку этой лабораторной работы на github, поэтому не смогу прикрепить фото. Но вот как это делается на примере прошлой лабораторной работы.

![Загрузка лабораторной №1 на github](image/10.png)

# Выводы

Во время данной работы я изучил идеологию и применение средств контроля версий. Приобрел практические навыки по работе с системой git.