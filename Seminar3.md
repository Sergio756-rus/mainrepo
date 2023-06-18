# Инструкция-туториал по разметке Markdown.


## Заголовки

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. Например:

# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6

В декоративных целях заголовки можно «закрывать» с
обратной стороны.





## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на буквеЁ) до и после кода. Также можно указать язык исходного кода.

```html
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
 <span class="comment-count">0
комментариев</span>
 <span class="comment-countplaceholder">Комментарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
 <a href="#" class="dropdown-toggle" datatoggle="dropdown">
    <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```

Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.




## Таблицы

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

Для всего остального есть обычный HTML.




## Изображения

**Чтобы добавить изображения, воспользуйтесь следующей командой:**

```
![Альтернативный текст](название этого фото)
```
Пример:

![Басист](DSC_0366.jpg)

**Если фото с сайта - то указываем ссылку на это фото:**

![Нажми-и увидишь чудо!](https://avatars.dzeninfra.ru/get-zen_doc/5212831/pub_62d1da0c1af13a7a72445ec2_62d1db5bf42581431ef146a6/scale_1200)

**Если мы хотим добавить изображения-ссылки, то нашу конструкцию надо сделать такой:**

```
![[альтернативный текст(ссылка)]](ссылка на другую картинку - наш перевертыш)
```

[![Нажми - и увидишь чудо](https://i2.wp.com/cdn.unitycms.io/image/ocroped/1200,1200,1000,1000,0,0/R4bX6-f77G4/Cr9xwn5p4pZATzILeebaiN.jpg)](https://dzen.ru/a/ZEO0TgbAd2-HHM2S)

Тест