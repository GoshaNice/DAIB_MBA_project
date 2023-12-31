# Анализ рыночной корзины и ассоциативных правил на основе клиентских данных 

Студенты: [Гончаров Фёдор](http://t.me/fmgoncharov), [Писцов Георгий](http://t.me/GoshaNice), [Дмитриев Иван](http://t.me/iudmitriev), [Никитин Александр](http://t.me/nikitinalex)


В данном проекте наша команда провела анализ рыночной корзины и ассоциативных правил на основе клиентских данных в рамках весеннего проекта по АДВБ. Финальный код приведен в [ноутбуке](DAIB_MBA.ipynb). Также доступна [презентация](https://github.com/GoshaNice/DAIB_MBA_project/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%80%D1%8B%D0%BD%D0%BE%D1%87%D0%BD%D0%BE%D0%B9%20%D0%BA%D0%BE%D1%80%D0%B7%D0%B8%D0%BD%D1%8B%20%D0%B8%20%D0%B0%D1%81%D1%81%D0%BE%D1%86%D0%B8%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B5%20%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0%20%D0%BD%D0%B0%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D1%81%D0%BA%D0%B8%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.pdf) для защиты

## Распределение задач

| **Задача**                                                          | **Выполнил**                                 |
|---------------------------------------------------------------------|----------------------------------------------|
| Заполнение и удаление пропусков                                     | Писцов Георгий                               |
| Исследование данных                                                 | Никитин Александр                            |
| Анализ значений и поиск выбросов по заказам                         | Никитин Александр                            |
| Формирование финальной витрины по клиентам                          | Писцов Георгий                               |
| Кластеризация при помощи K-Means                                    | Писцов Георгий                               |
| Кластеризация при помощи EM, сравнение алгоритмов кластеризации     | Дмитриев Иван                                |
| Профилирование классов                                              | Дмитриев Иван                                |
| Ассоциативные правила по сегментам и их анализ                      | Гончаров Фёдор                               |
| Витрина по сегментам с лучшими правилами. Сравнение алгоритмов      | Гончаров Фёдор                               |

## Результаты

В качестве основных результатов и выводов мы можем выделить: 
1. Проведена чистка и анализ данных
2. Проведено сравнение методов кластеризации. Найдено оптимальное количество сегментов - 6
3. Найдено по 126, 38 и 16 зависимых товарных наборов в сегментах 1, 2 и 5 соответственно - эти кластеры хорошо поддаются поиску ассоциативных правил
4. По лучшим правилам в сегментах проведен анализ и предложены маркетинговые акции


