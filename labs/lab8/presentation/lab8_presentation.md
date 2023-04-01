# Российский университет дружбы народов

## Факультет физико-математических и естественных наук
***
# Лабораторная работа №8

**Дисциплина:** Математическое моделирование

**Студент** Оразгелдиева Огулнур

**Группа:** НПИбд-02-20

2023, Москва

***

## Структура презентации:

1. Цель лабораторной работы
2. Задачи выполнения лабораторной работы
3. Результаты выполнения лабораторной работы и вывод

***



## Цель лабораторной работы

Построить график для модели конкуренции двух фирм с помощью julia, openmodelica
***

## Задачи выполнения

Вариант 62

Случай 1. Рассмотрим две фирмы, производящие взаимозаменяемые товары 
одинакового качества и находящиеся в одной рыночной нише. Считаем, что в рамках 
нашей модели конкурентная борьба ведётся только рыночными методами. То есть, 
конкуренты могут влиять на противника путем изменения параметров своего производства: себестоимость, время цикла, но не могут прямо вмешиваться в 
ситуацию на рынке («назначать» цену или влиять на потребителей каким-либо иным 
способом.) Будем считать, что постоянные издержки пренебрежимо малы, и в 
модели учитывать не будем. В этом случае динамика изменения объемов продаж 
фирмы 1 и фирмы 2 описывается следующей системой уравнений.

Случай 2. Рассмотрим модель, когда, помимо экономического фактора
влияния (изменение себестоимости, производственного цикла, использование 
кредита и т.п.), используются еще и социально-психологические факторы –
формирование общественного предпочтения одного товара другому, не зависимо от 
их качества и цены. В этом случае взаимодействие двух фирм будет зависеть друг 
от друга, соответственно коэффициент перед 
M M1 2
будет отличаться. Пусть в 
рамках рассматриваемой модели динамика изменения объемов продаж фирмы 1 и 
фирмы 2 описывается следующей системой уравнений



***
## Выполнение

![Рисунок 1. Код на julia](https://i.imgur.com/KyrY4CD.png)



Рисунок 1. Код на julia 

![Рисунок 2. Код openmodelica](https://i.imgur.com/xz99UU7.png)

Рисунок 2. Код openmodelica 

![График на julia](https://i.imgur.com/6TLEgH4.png)

Рисунок 3. График на julia

![Рисунок 4. График на openmodelica](https://i.imgur.com/Nx09J4o.png)

Рисунок 4. График на openmodelica

![Рисунок 5. График на julia](https://i.imgur.com/yBElzma.png)

Рисунок 5. График на julia

![Рисунок 6. График на openmodelica](https://i.imgur.com/jjqFldS.png)

Рисунок 6. График на openmodelica

***

## Результаты и вывод

В ходе лабораторной работы: 

Построили график для модели конкуренции двух фирм с помощью julia, openmodelica

***

