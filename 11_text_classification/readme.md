# Определение токсичных комментариев


## Описание проекта

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

## Цели проекта
Обучить модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок.
Значение метрики качества F1 у модели должно быть не меньше 0.75. 

## Описание данных

Столбец text в нём содержит текст комментария, а toxic — целевой признак.

## Используемый стек инструментов

- **pandas**
- **numpy**
- **re**
- **nltk**
- **matplotlib**
- **tf-idf**
- **spacy**

