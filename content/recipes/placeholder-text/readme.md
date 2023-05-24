![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/cover-placeholder-text-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/cover-placeholder-text-light.svg#gh-light-mode-only)

# Создать «рыбный текст» для дизайнерского макета

Допустим,вы&nbsp;делаете прототип социальной сети. Но&nbsp;вместо дизайна, вы&nbsp;тратите время на&nbsp;рыбный текст: придумываете имена пользователей и&nbsp;вручную добавляете их&nbsp;в&nbsp;макет. Такую работу упростит ГПТ Мейт. Это плагин для Фигмы, который генерирует текст и&nbsp;вставляет его в&nbsp;макет.

Если вы находитесь в России, почитайте [о&nbsp;работе ЧатГПТ в&nbsp;разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).

## Как сделать
1. [Получить ключ ОпенАИ](https://platform.openai.com/account/api-keys).
2. [Установить плагин ГПТ Мэйт для Фигмы](https://www.google.com/url?q=https://www.figma.com/community/plugin/1223951614916514138/GPT-Mate&amp;sa=D&amp;source=docs&amp;ust=1684725850872053&amp;usg=AOvVaw3wXg4bpF9PzN3QxsXenKfI).
3. Выделить текстовые блоки.
3. Открыть в&nbsp;окне плагина вкладку Settings и&nbsp;ввести ключ.
4. Перейти во&nbsp;вкладку Command и&nbsp;ввести промт: 
```
Напиши случайное имя и фамилию на русском языке
Не добавляй точки или запятые
```

Результат:

<img src="media/placeholder-screenshot-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/placeholder-screenshot-dark.png#gh-dark-mode-only">

## Что может пойти не так

ГПТ Мэйт посылает в&nbsp;ЧатГПТ новый запрос для каждого выделенного поля. Поэтому важно описывать в&nbsp;промте содержание одного поля, а&nbsp;не&nbsp;всех. Например, если написать &laquo;случайные русские имена&raquo;, ГПТ Мэйт добавит в&nbsp;каждое поле несколько имён.

Если в&nbsp;промте нет строчки о&nbsp;знаках препинания, ЧатГПТ иногда будет добавлять лишние знаки к&nbsp;именам.

## В этом рецепте
Приёмы:[`Промт с инструкцией`](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE)

Инструменты: `ChatGPT`, `OpenAI API`, `Figma`, `GPT Mate`

## 

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты)

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты)

[Предложить свой рецепт](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/articles/contributing)
