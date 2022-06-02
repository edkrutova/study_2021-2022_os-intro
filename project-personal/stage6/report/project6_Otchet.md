---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 6"
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

Выполнить шестой этап, разместив двуязычный сайт на Github.

# Задание

1. Сделать сайт на двух языках:

    - Сделать поддержку английского и русского языков.

    - Разместить элементы сайта на обоих языках.

    - Разместить контент на обоих языках.

2. Дописать посты:

    - Сделать пост по прошедшей неделе.

    - Добавить пост на тему по выбору (на двух языках).

# Выполнение лабораторной работы

Основные преобразования были в файлах из скопированных директорий (Рис. [-@fig:001]-[-@fig:004])

![Папки, где будут основные изменения](proj6/Screenshot_1.jpg){ #fig:001 width=70% }

![Папки содержимого на двух языках](proj6/Screenshot_2.jpg){ #fig:002 width=70% }

![Меню на двух языках](proj6/Screenshot_3.jpg){ #fig:003 width=70% }

![Добавленные посты на двух языках](proj6/Screenshot_4.jpg){ #fig:004 width=70% }

После изменений необходимо было "запушить" всё на сайт. (Рис. [-@fig:005])

![Отправка на сайт](proj6/Screenshot_7.jpg){ #fig:005 width=70% }

# Выводы

Я выполнила шестую часть проекта. Итог этапа на рис. [-@fig:006]-[-@fig:007].

![Добавленная русская версия](proj6/Screenshot_5.jpg){ #fig:006 width=70%}

![Созданные посты](proj6/Screenshot_6.jpg){ #fig:007 width=70%}


# Контрольные вопросы