# **Формирование рекомендаций по привлечению подписчиков в телеграмм канал Кинопоиска.**

## Часть 1. Подготовка данных и предобработка
## Часть 2. Исследование

## Данные
- публикации  канала (посты)
- комментарии и реакции читателей
- количество и динамика подписчиков 

## Задача 
- Выявить наиболее эффективные и точные метрики для еженедельного/ежемесячного анализа работы.
- Сформировать список KPI для дальнейшей работы и отслеживания заказчиком совместно с маркетологами.

## Цель
Привлечение подписчиков в телеграмм канал Кинопоиска.


## В исследовании
- Произведем загрузку в рабочую папку предоставленных таблиц
- Проведем исследовательский анализ данных
- Выявим и изучим темы постов Кинопоиска
- Выведем метрики эффективности поста
- Выделим наиболее часто встречающиеся слова во всех публикациях в целом. И выделим для каждой публикации (поста) количество наиболее часто встречающихся слов.
- Определим зависимость популярности поста от месяца, дня недели, времени суток публикации и определим в результате лучшее время для публикаций 
- Проведем семантический анализ комментариев к постам:
  - попытаемся выяснить, к каким действиям какие посты побуждают людей. В первую очередь нам интересна [вирусность](https://livedune.com/ru/blog/virusnyj-kontent) постов - способность контента распространяться по сети без особых усилий автора, лишь потому что он зацепил пользователей и **они сами охотно его репостят, отправляют друзьям и обсуждают.**
- Призведем анализ реакций читателей на сообщения.   
- Проведем Анализ эмодзи. Аналогично предыдущему пункту посчитаем количество эмодзи в зависимости от темы, типа публикаций, использованных слов, объема текста, сложностью текста.
  - При возможности установим зависимость от положительных и отрицательных эмодзи.

## Ход исследования
- Загрузка данных из предоставленных файлов и подготовка их к анализу
- Обработка данных, Изучение общей информации о датафрейме
- Расчет и определение дополнительных данных
- Объединение данных в сводную таблицу
- Исследовательский анализ данных
- Выводы и заключения

## Используемые библиотеки
- **pandas**  
- **matplotlib** 
- **seaborn** 
- **plotly** 
- **numpy** 
- **scipy** 
- **datetime** 
- **gspread**
- **string**
- **nltk**
- **pymorphy2**
- **re**
- **wordcloud**
- **math**
- **openpyxl**
- **google.colab**


## Выводы


## Рекомендуемые метрики (KPI):
- Количество слов в публикации - до 50 слов. По меньшей мере - от 50 до 120 слов.
- Средняя длина слова - от 3 до 6 символов. По меньшей мере - от 7 до 9 символов
- Количество знаков препинания  - один на 7 слов или более
- Для публикации постов, мотивирующих к переезду или предполагающих монетизацию:
  - День недели  - воскресенье и вторник
  - Тема публикации – События в Иннополисе и университет Иннополис
  - Тип публикации – с приложением видео
