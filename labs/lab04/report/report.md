---
## Front matter
title: "Лабораторная работа №4"
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

Целью данной работы является приобретение практических навыков проведения подготовительных работ по первоначальной настройке коммутаторов сети.

# Задание 

Требуется сделать первоначальную настройку коммутаторов сети, представленной на схеме L1 предыдущей работы. Под первоначальной настройкой понимается указание имени устройства, его IP-адреса, настройка доступа по паролю к виртуальным терминалам и консоли, настройка удалённого доступа к устройству по ssh. 

При выполнении работы необходимо учитывать соглашение об именовании

# Выполнение лабораторной работы

В логической рабочей области Packet Tracer разместим коммутаторы и оконечные устройства согласно схеме сети L1 и соединим их через соответствующие интерфейсы (рис. [-@fig:001]).

![Размещение коммутаторов и оконечных устройств согласно схеме сети L1](image/1.jpg){#fig:001 width=70%}

Используя типовую конфигурацию коммутатора, настроим все коммутаторы, изменяя название устройства и его IP-адрес согласно плану IP: msk-pavlovskaya-adutkina-sw-1 (рис. [-@fig:002]), msk-donskaya-adutkina-sw-1 (рис. [-@fig:003]), msk-donskaya-adutkina-sw-2 (рис. [-@fig:004]), msk-donskaya-adutkina-sw-3 (рис. [-@fig:005]), msk-donskaya-adutkina-sw-4 (рис. [-@fig:006]).

![Настройка коммутатора msk-pavlovskaya-adutkina-sw-1](image/2.jpg){#fig:002 width=70%}

![Настройка коммутатора msk-donskaya-adutkina-sw-1](image/3.jpg){#fig:003 width=70%}

![Настройка коммутатора msk-donskaya-adutkina-sw-2](image/4.jpg){#fig:004 width=70%}

![Настройка коммутатора msk-donskaya-adutkina-sw-3](image/5.jpg){#fig:005 width=70%}

![Настройка коммутатора msk-donskaya-adutkina-sw-4](image/6.jpg){#fig:006 width=70%}

# Выводы

В ходе данной лабораторной работы были приобретены практические навыки проведения подготовительной работы по первоначальной настройке коммутаторов сети.