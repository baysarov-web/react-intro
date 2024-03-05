# Create React App

## Summary 

Создание минимального React-приложения требует от разработчика определенных усилий: настройка вебпак, eslint, babel и т.д.

Разработчики Facebook создали утилиту, которая избавляет разработчика от этой рутины. Create React App позволяет создать минимальное React-приложение с предустановленным вебпаком, линтами и всеми другими настройками с помощью одной команды в терминале.

## Releases

### Release 0: создание приложения

Открой терминал Node.js (либо терминал git bash). С помощью команды `cd` перейди в папку, где нужно создать приложение. Обычно это папка Рабочего стола, тогда команда будет `cd Desktop`. Если терминал запущен с помощью git bash, то переходить в папку не нужно, т.к. можно сразу вызвать терминал из нужной папки.

Набери команду `npx create-react-app first-cra-app`. Данная команда начнет скачивание и установку нужных зависимостей в папку `first-cra-app`. По окончании загрузки ты увидишь фразу **Happy hacking**. Проект готов к разработке.

Для запуска приложение набери команду `npm start` из папки приложения. Должна открыться стартовая страница приложения.

### Release 1: структура файлов и папок

Папкой контекста в созданном приложении является папка `/src`. Точкой входа, как обычно, является файл `index.js`. HTML-шаблон находится в папке `/public`.

Измени первый параметр метода `render()`: убери всё, что там есть и выведи свою собственную верстку. Достаточно вывести несколько тегов для проверки. Проверь в браузере результат изменений.

### Releases 2

Удали всё содержимое папки `/src`. Создай заново файл `index.js` и пропиши в нём еще раз код, который выведет небольшую верстку.

## Conclusion

Create React App отлично подходит для разработки учебных, а также продакшн приложений. Выполняя каждый раз новое задание по реакту нужно создавать новое приложение.

В проектах, созданных на Create React App нам часто придется подключать изображения и стили. Как это сделать можно узнать на официальном сайте утилиты: [create-react-app.dev](https://create-react-app.dev/). Смотри разделы [Adding a Stylesheet](https://create-react-app.dev/docs/adding-a-stylesheet) и [Adding Images, Fonts, and Files](https://create-react-app.dev/docs/adding-images-fonts-and-files)
