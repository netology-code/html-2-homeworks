# Виджет новой статьи в блоге «Нетологии»

## Описание

Вдруг что-то пошло не так, и в блоге «Нетологии» пропали виджеты у новых статей! Вам поручили ответственную задачу &mdash; всё поправить. Сейчас виджет сам на себя не похож:

![](https://netology-code.github.io/html-2-homeworks/sources/lection-1-1-task-3-widget-before.png)

Менеджер звонит и умоляет как можно скорее сделать по-старому:

![](https://netology-code.github.io/html-2-homeworks/sources/lection-1-1-task-3-widget-after.png)

## Процесс реализации

1. Оберните текст «Первое издание…» тегом `<p>`
2. Оберните текст «Секреты JavaScript ниндзя. Джон Резиг, Беэр Бибо, Иосип Марас» тегом `<h1>`
3. Оберните ранее созданные элементы тегом `<div>` с атрибутом `class` и значением `card-content`
4. Перед элементом `<div>` с атрибутом `class` и значением `card-content` добавьте тег `<img>`
5. Тегу `<img>` добавьте атрибут `src` со значением [https://netology.ru/ckfinder/userfiles/images/Секреты%20JavaScript%20ниндзя.png](https://netology.ru/ckfinder/userfiles/images/Секреты%20JavaScript%20ниндзя.png)
6. Тегу `<img>` добавьте атрибут `class` со значением `card-img`
7. Тегу `<img>` добавьте атрибут `alt` со значением «Обложка книги Cекреты JavaScript»
8. Все текущие теги оберните тегом `<div>` с атрибутом `class` и значением `card`
9. Создайте новое CSS-правило, в котором используется селектор `.card-content`
10. В `.card-content` объявите свойство `margin-left` со значением `30px`
11. Создайте новое CSS-правило, в котором используется селектор `.card-name`
12. В `.card-name` объявите свойство `margin-top` со значением `0`
13. Добавьте в `.card-name` еще одно свойство `font-size` со значением `24px`

---

### Реализация

#### В песочнице CodePen

Перед началом работы сделайте форк пена на [https://codepen.io/Netology/pen/RYMbva](https://codepen.io/Netology/pen/RYMbva?editors=1100#0). Вносите изменения во вкладках HTML и CSS.

##### Внимание: Общую структуру документа создавать не надо, вкладка Codepen «HTML» работает, как тег `<body>`
см. [инструкцию по работе с Codepen](https://netology-university.bitbucket.io/guides/wm/codepen-guide/)