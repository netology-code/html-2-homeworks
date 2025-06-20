# Виджет новой статьи в блоге Нетологии

### Реализация

**В песочнице CodePen.** Перед началом работы сделайте форк пена на [странице](https://codepen.io/Netology/pen/RYMbva?editors=1100#0). Вносите изменения во вкладках HTML и CSS.

**Важно.** Общую структуру документа создавать не надо, вкладка CodePen «HTML» работает, как тег `<body>`.
Изучите [инструкцию по работе с CodePen](https://github.com/netology-code/guides/tree/master/codepen).

Редактор CodePen больше недоступен в РФ. Если вы не можете сделать задание в нём, то предлагаем вам альтернативное решение - JS Bin. Создайте аккаунт, перенесите стили из репозитория GitHub и выполняйте задания в JS Bin. [Подробная инструкция](https://disk.360.yandex.ru/i/dTjR9F-QJOgMfw)

---

## Описание

Вдруг что-то пошло не так, и в блоге Нетологии пропали виджеты у новых статей. Вам поручили ответственную задачу &mdash; всё поправить. Сейчас виджет выглядит так:

![](https://netology-code.github.io/html-2-homeworks/sources/lection-1-1-task-3-widget-before.png)

Менеджер звонит и просит как можно скорее вернуть прежний вид:

![](https://netology-code.github.io/html-2-homeworks/sources/lection-1-1-task-3-widget-after.png)

## Процесс реализации

1. Оберните весь текст параграфа, который начинается с «Первое издание…» парным тегом `<p>`.
2. Оберните текст «Секреты JavaScript ниндзя. Джон Резиг, Беэр Бибо, Иосип Марас» парным тегом `<h1>`.
3. Тегу `<h1>` добавьте атрибут `class` со значением `card-name`.
4. Оберните ранее созданные элементы парным тегом `<div>` с атрибутом `class` и значением `card-content`.
5. Перед элементом `<div>` с атрибутом `class` и значением `card-content` добавьте непарный тег `<img>`.
6. Тегу `<img>` добавьте атрибут `src` со значением `https://netology-code.github.io/html-2-homeworks/introduction-html-css/widget/img/Секреты-JavaScript-ниндзя.jpg`.
7. Тегу `<img>` добавьте атрибут `class` со значением `card-img`.
8. Тегу `<img>` добавьте атрибут `alt` со значением «Обложка книги Cекреты JavaScript».
9. Все текущие теги оберните парным тегом `<div>` с атрибутом `class` и значением `card`.
10. Создайте новое CSS-правило, в котором используется селектор `.card-content`.
11. В `.card-content` объявите свойство `margin-left` со значением `30px`.
12. Создайте новое CSS-правило, в котором используется селектор `.card-name`.
13. В `.card-name` объявите свойство `margin-top` со значением `0`.
14. Добавьте в `.card-name` ещё одно свойство `font-size` со значением `24px`.
15. Убедитесь, что результат соответствует описанию. Для этого перейдите в режим FullPage ([скриншот](/sources/screen.md)). Если режим FullPage View выдал ошибку, вам нужно подтвердить свою учётную запись в CodePen, пройдя по ссылке из письма от CodePen, тогда всё должно заработать корректно.
