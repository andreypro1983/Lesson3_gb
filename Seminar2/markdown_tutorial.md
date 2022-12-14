# Tutorial по языку разметки MarkDown

## Работа с заголовками

Для создания заголовков в MarkDown, необходимо перед заголовком поставить (#)
Заголовки бывают нескольких уровней, отличаются количеством указанных знаков (#) подряд

Пример:

### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6

В декоративных целях заголовки можно «закрывать» с
обратной стороны.

## Работа со списками

Для разметки неупорядоченных списков можно использовать или
(*) или (-) , или (+) :
Вложенные пункты создаются четырьмя пробелами перед маркером
пункта:
* элемент 1
* элемент 2
* элемент ...
 - элемент 1
 - элемент 2
    + вложенный элемент 2.1
    + вложенный элемент 2.2

Упорядоченный список:

1. элемент 1
2. элемент 2

   1. вложенный
   2. вложенный
3. элемент 3


На самом деле не важно как в коде пронумерованы пункты,
главное, чтобы перед элементом списка стояла цифра
(любая) с точкой. Можно сделать и так:

0. элемент1
0. элемент2
0. элемент3
0. элемент4   



## Работа с изображениями


Чтобы добавить изображения в MarkDown, используйте конструкцию:

!["Альтернативныйтекст"](https://ixbt.online/live/topics/preview/00/01/15/34/a04d403520.jpg)



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


Цитаты в MarkDown оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:
> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе
вложенные цитаты:
> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.
>
>This is a header.
> >Вложенная цитата.
>
>Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");





