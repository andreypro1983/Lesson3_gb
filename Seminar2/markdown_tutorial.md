# Tutorial по языку разметки MarkDown

## Работа с заголовками

## Работа со списками

## Работа с изображениями

<БЛА БЛА БЛА>
Хочу конфликт


## Работа с таблицами

Для того чтобы добавить в текст таблицу, нужно пойти на следующие ухищрения.
Воспользуемся разметкой GFM. Например:

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.

Для всего остального есть обычный HTML. Воспользуйтесь тегом table:
```HTML
Используйте теги <table><td><tr></tr></td></table>
```
## Работа с цитатами