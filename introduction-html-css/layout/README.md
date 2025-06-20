# Вёрстка блока с кратким описанием языка HTML

### Реализация

**В песочнице CodePen.** Перед началом работы сделайте форк пена на [странице](https://codepen.io/Netology/pen/aaYoKM?editors=1100#0). Внесите изменения во вкладке HTML пена. CSS менять не надо.

**Важно.** Общую структуру документа создавать не надо. Вкладка «HTML» в CodePen работает, как тег `<body>`.
Изучите [инструкцию по работе с CodePen](https://github.com/netology-code/guides/tree/master/codepen).

Редактор CodePen больше недоступен в РФ. Если вы не можете сделать задание в нём, то предлагаем вам альтернативное решение - JS Bin. Создайте аккаунт, перенесите стили из репозитория GitHub и выполняйте задания в JS Bin. [Подробная инструкция](https://disk.360.yandex.ru/i/dTjR9F-QJOgMfw)

---

## Описание

Поздравляю! Вы присоединились к команде вёрстки сайта «Википедии», и для вас есть первая задача. Нужно разметить текст блока с кратким описанием языка HTML. Сейчас блок выглядит так:

![](https://netology-code.github.io/html-2-homeworks/sources/lection-1-1-task-1-block-before.png)

Вам нужно добиться следующего результата:

![](https://netology-code.github.io/html-2-homeworks/sources/lection-1-1-task-1-block-after.png)

## Процесс реализации

1. Оберните текст «HTML» парным тегом `<span>` с атрибутом `class` и значением `term`.
2. Оберните текст «HyperText Markup Language» парным тегом `<span>` с атрибутом `class` и значением `hint`.
3. Оберните текст «Всемирной паутине» парным тегом `<a>` с атрибутом `href` и значением   `https://ru.wikipedia.org/wiki/Всемирная_паутина`.
4. Весь текст оберните парным тегом `<p>`.
5. Оберните тег `<p>` парным тегом `<main>` с атрибутом `class` и значением `content`.
6. Убедитесь, что результат соответствует описанию. Для этого перейдите в режим FullPage ([скриншот](/sources/screen.md)). Если режим FullPage View выдал ошибку, вам нужно подтвердить свою учётную запись в CodePen, пройдя по ссылке из письма от CodePen, тогда всё должно начать работать корректно.

