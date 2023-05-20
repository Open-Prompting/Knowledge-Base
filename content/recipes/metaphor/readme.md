![cover](https://github.com/Open-Prompting/Open-Prompting/blob/12addf4dacaf9c8905a5a475510253c2b0cb96ca/images/cover-metaphor-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Open-Prompting/blob/12addf4dacaf9c8905a5a475510253c2b0cb96ca/images/cover-metaphor-light.svg#gh-light-mode-only)

# Подобрать метафору для сложного термина
Вы&nbsp;пишете текст, в&nbsp;котором встречаются незнакомые читателю термины. Чтобы объяснить их&nbsp;простым языком, приходится долго искать метафоры. ЧатГПТ ускоряет такую работу: он&nbsp;умеет предлагать десятки метафор, из&nbsp;которых остаётся выбрать подходящую.

Если вы работает из России, почитайте [о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/content/articles/ruchatgpt/ruchatgpt.md).


# Что сделать
1. Описать контекст задачи. Например, если пишите для новичка, скажите `ты учишь ребёнка программированию`.
2. Дать ЧатуГПТ несколько попыток: `предложи десять метафор`. Обычно с&nbsp;одной попытки чат-бот не&nbsp;предложит идеальный вариант.
3. Собрать промт:
```
Ты учишь ребёнка программированию.
Объясни, что такое переменная.
Используй десять разных метафор.
```
ЧатГПТ выдаст ответ:

<img src="https://github.com/Open-Prompting/Open-Prompting/blob/11d51b0ed814049dfeeeec52b4dbfbc75184b45c/images/meta.webp" width="70%" height="70%">

ЧатГПТ предлагает метафоры по&nbsp;убыванию популярности. Если выбрать первый предложенный вариант, то&nbsp;получите самую избитую метафору, какую только знает искусственный интеллект.

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты)

[Предложить свой рецепт](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/contributing/contributing.md)
