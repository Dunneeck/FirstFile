# Инструкция по работе с Git

Начальная работа с системой контроля версий. 

**git --version** - команда для проверки версии git 

**git init** - инициализация пустого репозитория

**git status** - проверка текущего состояния файлов

**git add** - добавление версионности файлу

**git commit -m "Сообщение"** - команда для фиксации изменений файлов

**git log** - вывод истории комитов в хронологическом порядке
**git log --graph** - вывод фиксаций(коммитов) в виде дерева, для просмотрка всех веток

**git diff** - вывод изменений на текущий момент по отношению к последнему комиту

**git checkout master** или **git checkout хеш-номер_комита** - переход между изменениями либо возврат к текущему состоянию

**git reflog** - краткая история всех действий с репозиторием

**git reser --hard "хэшкод"** - сбросить всё до определённого коммита
___

## Работа с ветками

**git branch "имя ветки без ковычек"** - создаёт новую ветку

**git branch -D ""name"** - полное удаление ветки

**git merge** - слияние веток, основной и пробной.

**git branch -m "было имя" "стало"** - переименование ветки 

**git branch -d "имя ветки"** - удаляет ветку.

**git switch "name"** - переход на др ветку

**git switch -c "name"** - создание и переход на др ветку

В новой ветке можно работать и это не повлияет на другую ветку(основную). можно проверить тут код и если он норм работает можно его перенести на основную ветку!

___

## Как добавлять разные файлы, ссылки, цитаты и прочее.

как добавлять картинку (восклицательный знак)[надпись если нету фото](имя файла)

\!\[надпись вместо картинки](имя картинки с расширением)

> Запомни! Одна ошибка и ты ошибся... 
© Джейсон Стетхам

Цитаты делаются с помощью знака  ">"/

Ссылки с помощью квадратных и круглых скобок -  [Название ссылки](сама ссылка)

[Книга по Git](https://git-scm.com/book/ru/v2)

___

## ВТОРОЙ УРОК

## Заголовки

# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6
___

## Ссылки

Это встроенная [ссылка с title элементом]
(http://example.com/link "Я ссылка"). Это — [без title]

(http://example.com/link).

А вот [пример][1] [нескольких][2] [ссылок][id] с
разметкой как у сносок. Прокатит и [короткая запись][]
без указания id.

[1]: http://example.com/ "Optional Title Here"

[2]: http://example.com/some

[id]: http://example.com/links (Optional Title Here)

[короткая запись]: http://example.com/short
Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.

Картинки-ссылки:

[![Alt text](3.jpg)](http://example.com/)
___

## Картинки

Картинка без `alt` текста
![](1.jpg)
Картинка с альтом и тайтлом:
![Alt text](2.jpg "Можно задать title")
Запомнить просто: синтаксис как у ссылок, только перед
открывающей квадратной скобкой ставится восклицательный
знак.
Картинки «сноски»:
![Картинка][image1]

![Картинка][image2]

![Картинка][image3]

[image1]: //placehold.it/250x100

[image2]: //placehold.it/200x100

[image3]: //placehold.it/150x100

Картинки-ссылки:

[![Alt text](3.jpg)](http://example.com/)
___

## Таблиц 

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

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
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

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
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, *наклонный*,
**жирный** или зачеркнутый текст.
Для всего остального есть обычный HTML.
___

