# Блок выбора города

### Реализация

#### В песочнице CodePen

Перед началом работы сделайте форк пена на [https://codepen.io/Netology/pen/gBRbZV](https://codepen.io/Netology/pen/gBRbZV?editors=0100#0). Вносите изменения только во вкладке CSS.

##### Внимание: Общую структуру документа создавать не надо, вкладка Codepen «HTML» работает, как тег `<body>`
см. [инструкцию по работе с Codepen](https://github.com/netology-code/guides/tree/master/codepen).

---

## Описание

Помимо страницы «Направления Нетологии» дизайнер Вася создал для сайта Нетологии новый блок выбора города. Но Вася не знает, как сделать так, чтобы селект выглядел точно так же, как в его макете. Придется вам снова ему помочь!

Исходный внешний вид блока и вид конечного результата будут незначительно отличаться в зависимости от операционной системы, под управлением которой работает ваш компьютер.

Сейчас на компьютере с операционной системой Microsoft Windows блок выбора города выглядит следующим образом:

![](https://netology-code.github.io/html-2-homeworks/sources/3-2/city-select-win-before.jpg)

а на компьютере с операционной системой MacOS &mdash; так:

![](https://netology-code.github.io/html-2-homeworks/sources/3-2/city-select-before.jpg)

Если вы работаете на компьютере с операционной системой Microsoft Windows, вам нужно привести блок к виду:

![](https://netology-code.github.io/html-2-homeworks/sources/3-2/city-select-win-after.jpg)

А если вы работаете на компьютере с операционной системой MacOS &mdash; то к виду:

![](https://netology-code.github.io/html-2-homeworks/sources/3-2/city-select-after.jpg)

## Процесс реализации

1. Отключите стандартную стрелочку у элемента с классом `select`.
2. Добавьте фоновую иконку [https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/select-arrows.svg](https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/select-arrows.svg) для элемента с классом `select`.  
3. Отключите повторение иконки.
4. Расположите иконку на расстоянии `5px` от правой границы элемента и посередине по вертикали.
5. Создайте пустой псевдоэлемент `::before` для элемента с классом `checkbox-text`.
6. Сделайте псевдоэлемент `::before` строчно-блочным.
7. Расположите псевдоэлемент `::before` по центру по вертикали.
8. Сделайте размер псевдоэлемента `::before` `20px` на `20px`.
9. Добавьте к псевдоэлементу `::before` фоновую иконку [https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/checkbox-unchecked.svg](https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/checkbox-unchecked.svg)
10. Отключите повторение иконки для псевдоэлемента `::before`.
11. Расположите иконку по центру по горизонтали и по вертикали для псевдоэлемента `::before`.
12. Установите размер иконки `20px` для псевдоэлемента `::before`.
13. Сделайте так, что когда чекбокс выделен, то у него поменялась иконка на [https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/checkbox-checked.svg](https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/checkbox-checked.svg)
14. Скройте элемент `input` с типом `checkbox`.
15. Убедитесь, что результат соответствует описанию. Для этого перейдите в режим FullPage ([скриншот](/sources/screen.md)). Если режим FullPage View выдал ошибку - вам нужно подтвердить свою учетную запись в codepen, пройдя по ссылке из письма, пришедшего от codepen, тогда все должно начать работать корректно.

Не требуется вносить какие-либо другие правки в CSS или писать дополнительные правила, кроме тех, что предусмотрены заданием.
