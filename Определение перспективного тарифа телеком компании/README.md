# Определение перспективного тарифа телеком компании

##  Задача проекта 

На основании исторических данных о клиентах оператора сотовой связи проанализировать поведение их поведение и предложить оптимальный тариф. 


## Комфортный просмотр приведенных здесь файлов Jupiter Noutebook 

Для комфортного просмотра приведенных здесь файлов используйте сервис:
https://nbviewer.org/ 
Для того, чтобы открыть файлы - добавьте в сервис ссылку на мой репозитарий.

## Использованные библиотеки

```
pandas 
seaborn 
matplotlib
numpy
scipy 
```

## Выводы по проекту


1. Мы загрузили все исходные датасеты, подключили все необходимые бибилиотеки и предварительно просмотрели данные, выявили ошибки в типах данных, определели причины возникновения пропусков и необходимость их заполнения. 

2. Мы привели данные к нужным типам, нашли и исправили ошибки. Разобрались с причинами их возникновения. На основе данных сделали вывод о том, что заполнять пропуски в данных нет необходимости, так как это может исказить датасеты. Соеденили все таблицы в общий датасет, при этом как и многие коллеги не с первого раза все получилось, в итоге сгруппировали таблицу со звонками по идентификационному номеру пользователя и месяцу предоставления услуги. Затем присоеденили полученный датафрейм с таблицей пользователей и тарифами, после этого последовательно присоеденили таблицы сообщений и интернета. Посчитали для каждого пользователя количество израсходованных минут, сообщений и интернет-трафика. После проделанных операций вычислили помесячную выручку с каждого пользователя.

3. Мы описали поведение клиентов оператора, рассчитали сколько в среднем нужно пользователям каждого тарифа минут, сообщений и интнернет-трафика. Вычислили дисперсию и стандартное отклонения для каждой из величин. Построили гистограммы, из которых сделали вывод о характере их распределния, оценили раличия между тарифами. 

4. Мы проверили выдвинутые в задании гипотезы. Первая нулевая гипотеза "Средняя выручка тарифов "Ультра" и "Смарт" равны" была отвергнута. Вторую же нулевую гепотезу отвергнуть не получилось. 



**Тариф "Ультра" в среднем приносит на 40 % больше выручки нежели тариф "Смарт"**
