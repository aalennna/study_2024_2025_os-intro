---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
subtitle: Операционные системы
author:
  - Учаева А.С.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 08 марта 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Учаева Алёена Сергеевна
  * Студент НКАбд-05-24
  * Российский университет дружбы народов
  * [1132246728@rudn.ru](mailto:1132246728@rudn.ru)

:::
::: {.column width="30%"}


:::
::::::::::::::
## Цель работы

Целью данной лабораторной работы является научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

## Задание

1. Сделать отчет по лабораторной работе №2.
2. Предоставить отчет в трех форматах: pdf,docx,md.

## Теоретическое введение 

Чтобы создать заголовок, используйте знак ( # )
Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки
Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:
Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные
звездочки
Блоки цитирования создаются с помощью символа >
Неупорядоченный (маркированный) список можно отформатировать с помощью звез-
дочек или тире
Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка
Упорядоченный список можно отформатировать с помощью соответствующих цифр
Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка
Синтаксис Markdown для встроенной ссылки состоит из части [link text] , представ-
ляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла,
на который дается ссылка:
1 [link text](file-name.md)

##

Markdown поддерживает как встраивание фрагментов кода в предложение, так и их
размещение между предложениями в виде отдельных огражденных блоков. Огражденные
блоки кода — это простой способ выделить синтаксис для фрагментов кода. 
Для обработки файлов в формате Markdown будем использовать Pandoc
https://pandoc.org/. Конкретно, нам понадобится программа pandoc ,
pandoc-citeproc https://github.com/jgm/pandoc/releases, pandoc-crossref
https://github.com/lierdakil/pandoc-crossref/releases.

## Выполнение лабораторной работы 

Устанавливаю текстовый редактор gedit.

![Установка gedit](image/1.jpg){#fig:001 width=70%}

##

Открываю через текстовый редактор файл с шаблоном отчета.

![Редактирование отчета](image/2.jpg){#fig:002 width=70%}

##

Указываю основную информацию.

![Заполнение информации](image/3.jpg){#fig:003 width=70%}

##

Указываю цель работы,задание и теоретический материал.

![Цель работы,задание,теоретическое введение](image/4.jpg){#fig:004 width=70%}

##

Описываю выполнение лабораторной работы(рис. [-@fig:005]).

![Выполнение лабораторной работы](image/5.jpg){#fig:005 width=70%}

## Выводы

В результате данной лабораторной работы я научилась оформлять отчёты с помощью легковесного языка разметки Markdown.
