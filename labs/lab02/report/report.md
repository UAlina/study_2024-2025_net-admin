---
## Front matter
title: "Лабораторная работа №2"
author: "Уткина Алина Дмитриевна"

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
mainfont: PT Sans
romanfont: PT Sans
sansfont: PT Sans
monofont: PT Sans
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

Целью данной работы является приобретение практических навыков начального конфигурирования оборудования Cisco.

# Задание 

1. Сделать предварительную настройку маршрутизатора.

2. Сделать предварительную настройку коммутатора.

# Выполнение лабораторной работы

В логической рабочей области Packet Tracer разместим коммутатор, маршрутизатор и 2 оконечных устройства типа PC, соединим один PC с маршрутизатором, другой PC — с коммутатором (рис. [-@fig:001]).

![Схема устройств](image/1.jpg){#fig:001 width=70%}

Проведем настройку маршрутизатора в соответствии с заданием (рис. [-@fig:002]), (рис. [-@fig:003]), (рис. [-@fig:004]).

![Конфигурация маршрутизатора](image/2.jpg){#fig:002 width=70%}

![Конфигурация маршрутизатора](image/3.jpg){#fig:003 width=70%}

![Конфигурация маршрутизатора](image/4.jpg){#fig:004 width=70%}

Проведем настройку коммутатора в соответствии с заданием (рис. [-@fig:005]).

![Конфигурация коммутатора](image/5.jpg){#fig:005 width=70%}

Проверим работоспособность соединений с помощью команды ping (рис. [-@fig:006]), (рис. [-@fig:007]).

![Проверка подключения](image/6.jpg){#fig:006 width=70%}

![Проверка подключения](image/7.jpg){#fig:007 width=70%}

# Выводы

В ходе данной лабораторной работы были приобретены практические навыки начального конфигурирования оборудования Cisco.