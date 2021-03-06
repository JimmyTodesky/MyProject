# Прогнозирование подходящего тарифа телеком компании для рекомендации его пользователям

##  Задача проекта 
Нужно построить модель для задачи классификации, которая выберет подходящий тариф для дальнейшей рекомендации пользователям.

## Комфортный просмотр приведенных здесь файлов Jupiter Noutebook 

Для комфортного просмотра приведенных здесь файлов используйте сервис:
https://nbviewer.org/ 
Для того, чтобы открыть файлы - добавьте в сервис ссылку на мой репозитарий.

## Использованные библиотеки

```
pandas
sklearn
```

## Выводы по проекту

В данном проекте мы провели исследование для выявления наилушей модели для прогнозирования тарифа сотовой компании. В своем исследовании мы построили и обучили все три изученных в спринте модели классификации: 
1. Дерево решений
2. Случайный лес
3. Логистическую регрессию

В результате выбора наилучшей модели за счет изменения гиперпараметров до ее изучения, мы отобрали две - дерево решений и случайный лес. 

Логистическая регрессия показала неудовлетворительный результат ввиду того, что у нее нет гиперпараметров, которые возможно изменить. 

Все модели мы обучали на обучающих выборках, проверяли показатели их качества на валидационных, а уже затем запускали их на тестовую выборку. Сама методика стала более понятна и легкоповторяема.
