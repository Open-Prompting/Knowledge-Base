![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/cover-metaphor-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/metaphor/media/cover-metaphor-light.svg#gh-light-mode-only)

# Подобрать метафору для сложного термина
Допустим, вы пишете текст, в котором встречаются незнакомые читателю термины. Чтобы объяснить их простым языком, приходится долго искать метафоры. ЧатГПТ ускоряет такую работу: он умеет предлагать десятки метафор, из которых редактор выберет подходящую.

Если вы находитесь в России, почитайте [о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).


## Как сделать
1. Описать контекст задачи. Например, если ваш читатель — новичка, скажите `ты учишь ребёнка программированию`.
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
ЧатГПТ предлагает метафоры по убыванию популярности. Если выбрать первый предложенный вариант, то получите самую избитую метафору, какую только знает искусственный интеллект.


## В этой статье

Приёмы: [`промт с инструкцией`](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE), [`ролевой промт`](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE)

Инструменты: `ChatGPT`

## 

[Все рецепты](https://github.com/Open-Prompting/Knowledge-Base/tree/main#%D1%80%D0%B5%D1%86%D0%B5%D0%BF%D1%82%D1%8B)

[Все приёмы](https://github.com/Open-Prompting/Knowledge-Base/tree/main#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE) 

[Как добавить рецепт рецепт](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/articles/contributing)
