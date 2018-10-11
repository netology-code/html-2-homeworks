# Блок выбора города

## Описание

Помимо страницы «Направления Нетологии» дизайнер Вася создал для сайта Нетологии новый блок выбора города. Но Вася не знает, как сделать так, чтобы селект выглядел точно так же, как в его макете. Придется вам снова ему помочь!

Сейчас блок выбора города выглядит следующим образом: 

![](https://netology-code.github.io/html-2-homeworks/sources/3-2/city-select-before.jpg)

Ваша задача состоит в том, чтобы привести блок к виду:

![](https://netology-code.github.io/html-2-homeworks/sources/3-2/city-select-after.jpg)


## Процесс реализации


1. Отключите стандартную стрелочку у элемента `.select`
2. Для элемента `.select` добавьте фоновую иконку [https://netology-code.github.io/form-elements/city-select/img/select-arrows.svg](https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/select-arrows.svg)
3. Отключите повторение иконки
4. Иконка должна располагаться на расстоянии `5px` от правой границы элемента, и посередине по вертикали
5. Создайте пустой псевдоэлемент `::before` для элемента `.checkbox-text`
6. Сделайте псевдоэлемент строчно-блочным
7. По вертикали элемент должен располагаться по центру
8. Сделай размер элемента `20px` на `20px`
9. Добавьте к псевдоэлементу фоновую иконку [https://netology-code.github.io/form-elements/city-select/img/checkbox-unchecked.svg](https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/checkbox-unchecked.svg)
10. Отключите повторение иконки
11. Расположите икону по центру по горизонтали и по вертикали
12. Установите размер иконки `20px`
13. Сделайте так, что когда чекбокс выделен, то у него поменялась иконка на [https://netology-code.github.io/form-elements/city-select/img/checkbox-checked.svg](https://netology-code.github.io/html-2-homeworks/form-elements/city-select/img/checkbox-checked.svg)
14. Скройте элемент `input` с типом `checkbox`

Правильный результат должны иметь вид:

![](https://netology-code.github.io/html-2-homeworks/sources/3-2/city-select-after.jpg)

Не требуется вносить какие-либо другие правки в CSS или писать дополнительные правила.


---

### Реализация

#### В песочнице CodePen

Перед началом работы сделайте форк пена на [https://codepen.io/Netology/pen/gBRbZV](https://codepen.io/Netology/pen/gBRbZV?editors=0100#0). Вносите изменения только во вкладке CSS.

##### Внимание: Общую структуру документа создавать не надо, вкладка Codepen «HTML» работает, как тег `<body>`
см. [инструкцию по работе с Codepen](https://netology-university.bitbucket.io/guides/wm/codepen-guide/)
