---
# Front matter
lang: ru-RU
title: " Отчет по Лабораторной работе №3"
subtitle: "Дисциплина: Операционные системы"
author: "Саттаров Константин Григорьевич"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Ход выполнения лабораторной работы

1. Первым делом заполняем титульный лист
![Создание титульника](image/11.png)
<center>Рис 1</center>
2. Используем шаблон дляоформления документа
![Копипаст шаблона](image/12.png)
<center>Рис 2</center>
3. Затем начинаем заполнять поля, стараясь повторить оформление Лабораторной работы 2
![Заполняем поля](image/13.png)
<center>Рис 3</center>
Самое тяжелое это понять как это будет выглядеть и криво ли получается
4. Заполняем последний абзац "Вывод"
![Последний пункт](image/14.png)
<center>Рис 4</center>
5. С помощью необходимых команд превращаем файл из md в docx и pdf
# Вывод
Суммарно вышло почти на 112 срок, но большую часть занимает шаблон оформления.(.space)
В данной лабораторно работе я узнал много нового о markdown, а так же попытался сделать красивый документ
