---
lang: ru-RU
title: "Отчёт по лабораторной работе 7"
subtitle: "дисциплина: Математическое моделирование"

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



--- 
![]()

# Российский университет дружбы народов

## Факультет физико-математических и естественных наук
***

# Отчёт по лабораторной работе №7

**Дисциплина:** Математическое моделирование

**Студент:** Оразгелдиева Огулнур

**Группа:** НПИбд-02-20

---

**Лабораторная работа №6**

**Цель работы**

Построить график для задачи об эффективности рекламы.


**Теоретическое введение**[1]

Модель рекламной кампании описывается следующими величинами. 
Считаем, что $dn/dt$ - скорость изменения со временем числа потребителей, 
узнавших о товаре и готовых его купить, 
t - время, прошедшее с начала рекламной 
кампании, 
n(t) - число уже информированных клиентов. Эта величина 
пропорциональна числу покупателей, еще не знающих о нем, это описывается 
следующим образом $a1(t)(N-n(t))$,где 
N - общее число потенциальных 
платежеспособных покупателей, a1(t)>0
- характеризует интенсивность 
рекламной кампании (зависит от затрат на рекламу в данный момент времени). 
Помимо этого, узнавшие о товаре потребители также распространяют полученную 
информацию среди потенциальных покупателей, не знающих о нем (в этом случае 
работает т.н. сарафанное радио). Этот вклад в рекламу описывается величиной $a2(t)n(t)(N-n(t))$,  t n t n t  , эта величина увеличивается с увеличением потребителей 
узнавших о товаре. Математическая модель распространения рекламы описывается 
уравнением $dn/dt=a1(t)+a2(t)n(t)(N-n(t))$.

**Задание**

Вариант 62

Постройте график распространения рекламы, математическая модель которой описывается 
следующим уравнением:

1) $dn/dt=(0.815+0.000033n(t))(N-n(t))$

2) $dn/dt=(0.000044+0.27n(t))(N-n(t))$

3) $dn/dt=(0.5t+0.8cos(t)n(t))(N-n(t))


**Выполнение работы**

Напишем программму на julia для трех случаев (см. рис. 1-3)соответсвенно.

![Рисунок 1. Код для случая 1](https://i.imgur.com/aNxc12D.png)

Рисунок 1. Код для случая 1

![Рисунок 2. Код для случая 2](https://i.imgur.com/NnmqKEs.png)

Рисунок 2. Код для случая 2

![Рисунок 3. Код для случая 3](https://i.imgur.com/FCdibN4.png)

Рисунок 3. Код для случая 3

Получили соответсвующие графики (см. рис. 4-6)

![Рисунок 4. График для случая 1](https://i.imgur.com/tzy0Zqo.png)

Рисунок 4. График для случая 1

![Рисунок 5. График для случая 2](https://i.imgur.com/ThZ9O5e.png)

Рисунок 5. График для случая 2


![Рисунок 6. График для случая 3](https://i.imgur.com/A8u0xBf.png)

Рисунок 6. График для случая 3


Написали программы на Openmodelica для 1-3 случая соответсвенно(см. рис. 7-9) 

![Рисунок 7. Код для случая 1](https://i.imgur.com/0NjeGQA.png)

Рисунок 7. Код для случая 1

![Рисунок 8. Код для случая 2](https://i.imgur.com/ZKR8D3I.png)

Рисунок 8. Код для случая 2

![Рисунок 9. Код для случая 3](https://i.imgur.com/cjMueIb.png)

Рисунок 9. Код для случая 3

Теперь получаем графики (см. рис. 10-12)

![Рисунок 10. График для случая 1](https://i.imgur.com/prdLQy0.png)

Рисунок 10. График для случая 1

![Рисунок 11. График для случая 2](https://i.imgur.com/mi1zRzS.png)

Рисунок 11. График для случая 2

![Рисунок 12. График для случая 3](https://i.imgur.com/zLPLMLq.png)

Рисунок 12. График для случая 3

---

**Вывод:** построили график для задачи об эффективности рекламы.


---

**Список литературы**

1. Лабораторная работа №7











