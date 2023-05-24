![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/cover-metaphor-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/cover-metaphor-light.svg#gh-light-mode-only)

# Подобрать метафору для сложного термина
Допустим, вы&nbsp;пишете текст, в&nbsp;котором встречаются незнакомые читателю термины. Чтобы объяснить их&nbsp;простым языком, приходится долго искать метафоры. ЧатГПТ ускоряет такую работу: он&nbsp;умеет предлагать десятки метафор, из&nbsp;которых редактор выберет подходящую.

Если вы находитесь в России, почитайте [о&nbsp;работе ЧатГПТ в&nbsp;разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).


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

Приёмы: [`Промт с инструкцией`](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE), [`ролевой промт`](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE)

Инструменты: `ChatGPT`

## 

[Все рецепты](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/recipes)

[Все приёмы](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE)

[Предложить свой рецепт](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/articles/contributing)

