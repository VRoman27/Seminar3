# Туториал по языку разметки MarkDown

## Как добавить заголовки

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести:
```
# Заголовок первого уровня
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6
```

Пример:
# Заголовок первого уровня
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6

### Как добавить списки
Для разметки неупорядоченных списков можно использовать
или `*`, или `-`, или `+`:
```
* Первый
- Второй
+ Третий
```
Пример:
* Первый
- Второй
+ Третий

Вложенные пункты создаются четырьмя пробелами перед
маркером пункта:
```
* Основной
    * Вложенный
```
Пример:
* Основной
    * Вложенный

Для упорядоченного списка нужно напечатать любую цифру с точкой вначале строки:
```
1. Первый
2. Второй
3. Третий
0. Четвёртый
9. Пятый
```
Пример:
1. Первый
2. Второй
3. Третий
0. Четвёртый
9. Пятый

Для оформления списка с абзацами необходимо добавить четыре пробела или один tab вначале:
```
    * Раз абзац. Lorem ipsum dolor sit amet, consectetur adipisicing elit.
    * Два абзац. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.
```
Пример:

    * Раз абзац. Lorem ipsum dolor sit amet, consectetur adipisicing elit.
    * Два абзац. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.


## Как добавить исходный код

Чтобы добавить исходный код, необходимо использовать конструкцию следующего вида:
```html
<table><tr><td style="color:#ff7834">Текст</td></tr></table>
```
Пример рабочего кода без кавычек:
<table><tr><td style="color:#FFD700">Текст</td></tr></table>


## Как добавить изображения

Чтобы добавить изображения в разметку MarkDown, используйте следующую инструкцию:
```
![альтернативный текст](ссылка на изображение)
```
Пример:
![кот](https://img3.goodfon.ru/original/1366x768/1/35/britanskaya-korotkosherstnaya-2312.jpg)

Чтобы добавить картинку-ссылку, необходимо модифицировать блок-схему выше следующим образом:
```
[![альтернативный тест](ссылка на изображение само)](ссылка на изображение или страницу)

```
[![альтернативный тест](https://i.pinimg.com/originals/34/5d/06/345d06034d87694738caf3dcaa95a282.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)


## Как добавить ссылки

Чтобы вставить ссылку, используйте следующие конструкции:
```
Ссылка с title элементом:
[ссылка с title элементом](https://www.youtube.com/watch?v=dryXw0G-Xmk)
Ссылка без title элемента: 
https://www.youtube.com/watch?v=ZyrFkGrxEY0
```
Пример:

[Качнуло](https://www.youtube.com/watch?v=dryXw0G-Xmk)

https://www.youtube.com/watch?v=ZyrFkGrxEY0

Можно использовать сноски:
```
Текст, в котором есть [сноска][1], [сноска с id][id] и [сноска с текстом вместо id][]

[1]: http://example.com/ "Optional Title Here"
[id]: http://example.com/links (Optional Title Here)
[сноска с текстом вместо id]: http://example.com/short
```

Текст, в котором есть [сноска][1], [сноска с id][id] и [сноска с текстом вместо id][]

[1]: https://www.youtube.com/watch?v=jSkCg2_q5pc "BLOOD DIVIDE"
[id]: https://www.youtube.com/watch?v=vkxbu1Cl5Mo (ВЕЧНО TEEN SPIRIT)
[сноска с текстом вместо id]: https://www.youtube.com/watch?v=FavUpD_IjVY
