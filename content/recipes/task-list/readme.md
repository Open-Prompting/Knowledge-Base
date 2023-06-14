![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/task-list/media/cover-task-list-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/task-list/media/cover-task-list-light.svg#gh-light-mode-only)

# Составить список задач по проектированию интерфейса
Допустим, вы разрабатываете дизайн мобильного приложения для сервиса доставки еды. Чтобы оценить, сколько времени займёт проект, сначала потребуется определить объём работы. Попросите ЧатГПТ составить список задач для вашего проекта.

Если вы в России, почитайте [о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).

## Как сделать
1. Описать контекст: `мы разрабатываем мобильное приложение для сервиса доставки еды`
2. Дать задание: `создай подробный список задач по проектированию интерфейса для дизайнера`
3. Собрать всё в промт:
```
Мы разрабатываем мобильное приложение для сервиса доставки еды.
Создай подробный список задач по проектированию интерфейса для дизайнера.
```

Результат:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/task-list/media/screenshot-tasks-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/task-list/media/screenshot-tasks-dark.png#gh-dark-mode-only" width="70%" height="70%">

## Что может пойти не так
ЧатГПТ может предложить длинный список из слишком общих пунктов. Если вам не подходит большая часть списка, попробуйте переформулировать промт и добавить в него больше контекста.

## В этой статье
Приёмы: [`дать инструкцию`](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/methods/instruction/)

Инструменты: `ChatGPT`
