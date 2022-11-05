# Вёрстка текста по PSD-макету

### Реализация

**В песочнице CodePen.** Перед началом работы сделайте форк пена на [странице](https://codepen.io/Netology/pen/MPGeOK?editors=0100#0). Вносите изменения только во вкладке CSS.

**Важно.** Общую структуру документа создавать не надо, вкладка CodePen «HTML» работает, как тег `<body>`.
Изучите [инструкцию по работе с CodePen](https://github.com/netology-code/guides/tree/master/codepen).

---

## Описание

Вам нужно доработать вёрстку с учётом PSD-макета.

Страница со статьёй:

![](https://netology-code.github.io/html-2-homeworks/sources/4-2/font-face-before.jpg)

Нужно стилизовать надпись, чтобы вёрстка выглядела так:

![](https://netology-code.github.io/html-2-homeworks/sources/4-2/font-face-after.jpg)

## Процесс реализации

1. Скачайте [архив с исходными файлами задания](https://netology-code.github.io/html-2-homeworks/flex-elements-positioning/font-face/materials/task-4-2.zip).
2. Установите шрифт `Lobster-Regular.ttf` в вашу операционную систему.
3. Измерьте в макете и установите размер текста для элемента с классом `container`.
4. Измерьте в макете и установите цвет текста для элемента с классом `container`.
5. Измерьте в макете и установите междустрочное расстояние для элемента `p`.
6. Подключите шрифт `lobster`, используя директиву `font-face`. В качестве пути (`src`) используйте [файл](https://netology-code.github.io/html-2-homeworks/flex-elements-positioning/font-face/fonts/lobster-regular.woff), в настройках укажите `font-family: lobster`, `font-weight: 400` и `font-style: normal`.
7. Установите `font-family: lobster` для элемента с классом `container`.
8. Убедитесь, что результат соответствует описанию. Для этого перейдите в режим FullPage ([скриншот](/sources/screen.md)). Если режим FullPage View выдал ошибку, вам нужно подтвердить свою учётную запись в CodePen, пройдя по ссылке из письма от CodePen, тогда всё должно заработать корректно.


Не нужно вносить другие правки в CSS или писать дополнительные правила, кроме тех, что предусмотрены заданием.
