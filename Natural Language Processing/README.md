## Обработка естественного языка
### Описание проекта
Нам дана база твитов с их текстом, локациями и ключевыми словами. Нужно научиться классифицировать, посвящен ли текст твита катастрофе или нет.
### Этапы проекта
- Загрузка датасета и изучение общей информации
- Предобработка данных
- Исследовательский анализ данных
- Прогноз стоимости домов
- Вывод
### Краткий вывод
Для начала мы загрузили датасеты и ознакомились с общей информацией. На этапе предобработки данных мы заполнили пропуски, а затем занялись исследовательским анализом данных. Оказалось, что 70% твитов без ключевого слова повествуют о катастрофах, а 83% твитов из Индии связаны с катастрофами. На следующем этапе мы построили модель (LogisticRegression) для предсказания принадлежности твитов в тестовом датасете.
