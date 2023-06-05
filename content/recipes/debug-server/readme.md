![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/testing/content/recipes/debug-server/media/cover-spreadsheet-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/testing/content/recipes/debug-server/media/cover-spreadsheet-light.svg#gh-light-mode-only)

# Починить веб-сервер без администратора
Допустим, ваш веб-сервер упал с ошибкой 500. Вы понимаете, что проблему надо устранить, но не знаете как, а спросить не у кого. Чтобы починить веб-сервер, воспользуйтесь ЧатГПТ и общайтесь с ним как с живым администратором: задавайте вопросы, просите объяснить, как работают технологии.

Если вы в России, почитайте о работе ЧатГПТ в разных регионах.

## Как сделать
1. Подключиться к серверу через терминал.
2. Ввести промт:
```
Мой сайт выдаёт ошибку 500.
Как это исправить?
Дай подробную инструкцию
```
3. Следуйте советам нейросети. Например, если ЧатГПТ спросит о логах сервера, скопируйте их в чат. Если сомневаетесь, как выполнить инструкцию нейросети, попросите её объяснить подробнее.

Результат:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/testing/content/recipes/debug-server/media/screenshot-debug-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/testing/content/recipes/debug-server/media/screenshot-debug-light.png#gh-dark-mode-only" width="70%" height="70%">

## Что может пойти не так
Если ЧатГПТ не справляется с проблемой, попробуйте ему помочь. Например, если найдете подсказку в интернете, дайте её ЧатуГПТ.

## В этой статье
Приёмы: `промт с инструкцией`

Инструменты: `ChatGPT`