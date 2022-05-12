---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 3"
author: "Крутова Екатерина Дмитриевна"

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

# Цель работы:

Выполнить второй этап, добавив к сайту достижения.

# Задание

## Обновить данные:

- Добавить информацию о навыках (Skills).

- Добавить информацию об опыте (Experience).

- Добавить информацию о достижениях (Accomplishments).

## Дописать посты:

- Сделать пост по прошедшей неделе.

- Добавить пост на тему "Языки разметки. LaTeX."

# Выполнение лабораторной работы

Основные преобразования были в файлах из скопированных директорий (Рис. [-@fig:001]-[-@fig:002])

![Папка Post с добавленными постами](proj3/Screenshot_3.jpg){ #fig:001 width=70% }

![Папка Home с изменёнными файлами](proj3/Screenshot_2.jpg){ #fig:002 width=70% }

После изменений необходимо было "запушить" всё на сайт.

# Выводы

Я выполнила третью часть проекта. Итог этапа на рис. [-@fig:003]-[-@fig:004].

![Обновлённая страница](proj3/Screenshot_4.jpg){ #fig:003 width=70%}

![Созданные посты](proj3/Screenshot_1.jpg){ #fig:004 width=70%}
