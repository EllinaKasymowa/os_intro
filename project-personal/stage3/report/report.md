---
## Front matter
title: ИНдивидуальный проект 3 этап
subtitle: Операционные системы
author: Касымова Эллина
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

Добавить к сайту достижения.

Цель данного шаблона --- максимально упростить подготовку отчётов по
лабораторным работам.  Модифицируя данный шаблон, студенты смогут без
труда подготовить отчёт по лабораторным работам, а также познакомиться
с основными возможностями разметки Markdown.

# Задание


1. Список достижений.
        Добавить информацию о навыках (Skills).
        Добавить информацию об опыте (Experience).
        Добавить информацию о достижениях (Accomplishments).
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
        Легковесные языки разметки.
        Языки разметки. LaTeX.
        Язык разметки Markdown.

# Выполнение лабораторной работы

1. В папке контент открыла файл индекс и ввела информацию о навыках.

![Название рисунка](image/1.png){#fig:001 width=90%}

![Название рисунка](image/2.png){#fig:002 width=90%}

2. В папке контент открыла файл индекс и ввела информацию об опыте.

![Название рисунка](image/3.png){#fig:003 width=90%}

3. В папке контент открыла файл индекс и ввела информацию о достижениях.

![Название рисунка](image/4.png){#fig:004 width=90%}

4. Проверяем на сайте.

![Название рисунка](image/5.png){#fig:005 width=90%}

![Название рисунка](image/6.png){#fig:006 width=90%}

5. Делаю Пост по прошедшей недели.

![Название рисунка](image/7.png){#fig:007 width=90%}

6. Делаю пост на тему языки разметки. LaTeX.

![Название рисунка](image/8.png){#fig:008 width=90%}

7. Проверяю на сайте.

![Название рисунка](image/9.png){#fig:009 width=90%}

8. Захожу в кадый пост и уточняю сохранилась ли оинформация в посте.

![Название рисунка](image/10.png){#fig:010 width=90%}

![Название рисунка](image/11.png){#fig:011 width=90%}


# Выводы

Поделав данный этап мы научились редактировать сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::
