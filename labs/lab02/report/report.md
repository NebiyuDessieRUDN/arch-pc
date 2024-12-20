---
## Front matter
title: "Отчёт по лабораторной работе 2"
subtitle: "Архитектура компьютеров"
author: "Тефера Небию Десси"

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

Изучить идеологию и научиться применять средства контроля версий. Получить практические навыки по работе с системой git.
  
# Ход работы

Я уже раньше зарегистрировался на гитхаб, когда начал делать лаб работы с 5й. 
Вот мой аккаунт(рис. [-@fig:001])

![Данные аккаунта на Гитхабе](image/01.png){ #fig:001 width=70%, height=70% }

Вот мой сетевой репозиторий (рис. [-@fig:002])

![Репозиторий на сайте гитхаб](image/02.png){ #fig:002 width=70%, height=70% }

Вот мой Локальный репозиторий на компьютере (рис. [-@fig:003])

![ Папка репозитория](image/03.png){ #fig:003 width=70%, height=70% }

![Отправка данных на Гитхаб ](image/04.png){ #fig:004 width=70%, height=70% }

# Выводы

Я получил навыки по работе с системой контроля версий GitHub.