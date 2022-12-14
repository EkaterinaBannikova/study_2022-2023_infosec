---
## Front matter
lang: ru-RU
title: Лабораторная №7
subtitle: Основы информационной безопасности
author:
  - Банникова Екатерина Алексеевна
institute:
  - Российский университет дружбы народов, Москва, Россия
  - НПМбд-01-19

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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Элементы криптографии. Однократное гаммирование

## Цель лабораторной работы

* Получить практические навыки по работе с однокрастным гаммированием


## Задачи лабораторной работы

1. Написать функцию шифровки и дешифровки данных в режиме однократного гаммирования
2. Определить вид шифротекста при известном ключе и октрытом тексте
3. Определить ключ, преобразующий шифротекст в один из вариантов прочтения открытого текста

## Выполнение

Создаем функцию, которая осуществляет однократное гаммирование посредством побитового XOR

![Функция шифрования](image/1.PNG){ #fig:1 width=50% }

## Выполнение

Задаем текстовую строку и создаем случайный символьный ключ такой длины
  
![Исходные данные](image/2.PNG){ #fig:2 width=50% }

## Выполнение
  
Запускаем функцию. В первом случае получаем зашифрованный текст. 
Используя тот же ключ, осуществляем дешифровку текста. 
Зная оригинальный текст и его шифровку, может получить ключ.

![Результат работы программы](image/3.PNG){ #fig:3 width=35% }


## Выводы

Освоено на практике применение режима однократного гаммирования.
  
  



