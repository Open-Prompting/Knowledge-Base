![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/cover-metaphor-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/cover-metaphor-light.svg#gh-light-mode-only)

# Подобрать метафору для сложного термина
Допустим, вы&nbsp;пишете текст, в&nbsp;котором встречаются незнакомые читателю термины. Чтобы объяснить их&nbsp;простым языком, приходится долго искать метафоры. ЧатГПТ ускоряет такую работу: он&nbsp;умеет предлагать десятки метафор, из&nbsp;которых редактор выберет подходящую.

Если вы работает из России, почитайте [о&nbsp;работе ЧатГПТ в&nbsp;разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).


## Как сделать
1. Описать контекст задачи. Например, если  ваш читатель — новичка, скажите `ты учишь ребёнка программированию`.
2. Скажите ЧатуГПТ придумать несколько вариантов: `предложи десять метафор`.
3. Собрать промт:
```
Ты учишь ребёнка программированию.
Объясни, что такое переменная.
Предложи десять метафор.
```
Результат:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/metaphor-screenshot-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/metaphor-screenshot-dark.png#gh-dark-mode-only" width="70%" height="70%">


## Что может пойти не так
ЧатГПТ предлагает метафоры по&nbsp;убыванию популярности. Если выбрать первый предложенный вариант, то&nbsp;получите самую избитую метафору, какую только знает искусственный интеллект.


## В этой статье

Приёмы: [`Промт с инструкцией`](#), [`ролевой промт`](#)

Инструменты: `ChatGPT`

## 

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты)

[Все приёмы](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты)

