# Задание для Урока 3: Структура HTML-документа

## Описание задания
В этом задании вы будете практиковать создание структуры HTML-документа. Вам предстоит создать простую веб-страницу с использованием различных тегов HTML, таких как заголовки, параграфы, списки и ссылки. Это поможет вам закрепить полученные знания и развить навыки работы с базовыми элементами HTML.

## Цели задания:
- Создать базовую структуру HTML-документа.
- Работать с различными тегами: заголовки, параграфы, списки, ссылки.
- Проверить правильность структуры документа и его отображение в браузере.

## Инструкция:
1. **Создайте HTML-документ**:
    - Используйте `<!DOCTYPE html>`, чтобы указать тип документа.
    - Убедитесь, что ваш файл начинается с тега `<html>` и содержит обязательные мета-теги в `<head>`.
    - В разделе `<body>` добавьте следующие элементы:

2. **Добавьте следующие элементы в раздел `<body>`**:
    - **Заголовок первого уровня (`<h1>`)** с текстом, например, "Добро пожаловать на мой сайт".
    - **Параграф (`<p>`)** с текстом, который кратко объясняет, о чем будет ваш сайт.
    - **Заголовок второго уровня (`<h2>`)** с текстом, например, "Мои увлечения".
    - **Маркированный список (`<ul>`)** с тремя элементами `<li>`, например:
        - Программирование
        - Чтение книг
        - Путешествия
    - **Заголовок третьего уровня (`<h3>`)** с текстом, например, "Контакты".
    - **Ссылку (`<a>`)** на вашу электронную почту, используя атрибут `href="mailto:ваша_почта"`.
    - **Дополнительно:** Добавьте хотя бы один дополнительный элемент, который вы считаете полезным (например, изображение или видео).

3. **Отображение в браузере**:
    - После того как вы создали HTML-файл, откройте его в браузере, чтобы убедиться, что все элементы отображаются корректно.
    - Если что-то не отображается, проверьте структуру тегов и их закрытие.

## Пример итогового кода:
```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой первый сайт</title>
</head>
<body>
    <h1>Добро пожаловать на мой сайт!</h1>
    <p>Этот сайт создан с помощью HTML. Здесь будет размещен основной контент.</p>

    <h2>Мои увлечения</h2>
    <ul>
        <li>Программирование</li>
        <li>Чтение книг</li>
        <li>Путешествия</li>
    </ul>

    <h3>Контакт</h3>
    <p>Если у вас есть вопросы, пишите мне на <a href="mailto:example@example.com">email</a>.</p>
</body>
</html>
```

## Дополнительные рекомендации:
- Используйте **валидатор HTML**, чтобы проверить правильность вашего кода.
- Убедитесь, что вы следуете правильной иерархии заголовков (`<h1>` > `<h2>` > `<h3>`, и так далее).
- Прочитайте [документацию HTML на MDN](https://developer.mozilla.org/ru/docs/Web/HTML), чтобы лучше понять все элементы.

## Критерии оценки:
- **Правильная структура документа**: все теги открыты и закрыты корректно.
- **Использование различных типов тегов**: заголовки, параграфы, списки, ссылки.
- **Отображение в браузере**: страница корректно отображается, без ошибок.
