# 12. Предсказание оттока клиентов

## Описание проекта
Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

### Цели проекта  

- Спрогнозировать отток клиентов мобильного оператора для планирования предиктивных мер (скидок, особых условий).  
Для выборки клиентов доступны персональные данные, информация о тарифах и договорах.  
- Построить модель со значением метрики качества ROC_AUC не меньше 0.88.  
Дополнительно зафиксировать accuracy модели.  

### План проекта:

1. Разведывательный анализ данных
- первичное изучение данных, обработка синтаксиса и смена формата там, где необходимо.
- Первичная визуальная оценка полноты данных, локализация пропусков.
- изучение кореляции признаков для исключения мультиколеарности признаков.

2. Иследовательский анализ данных
- Объединение таблиц в один датафрейм
- Создание новых признаков на основе имеющихся
- Удаление лишних признаков
- Сравнение признаков для двух категорий клиентов: ушедших и оставшихся

3. Подготовка данных к обучению
- Разделение выборок
- Кодирование бинарных признаков
- Оучение моделей с подбором гиперпараметров

4. Тестирование моделей
- Тестирование лучшей модели
- Проверка модели на адекватность

5. Вывод

6. Отчёт

### Используемый стек инструментов

- python
- pandas
- numpy
- sklearn
- matplotlib
- seaborn
- catboost  

