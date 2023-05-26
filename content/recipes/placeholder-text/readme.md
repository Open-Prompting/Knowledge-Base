![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/cover-placeholder-text-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/cover-placeholder-text-light.svg#gh-light-mode-only)

# Создать «рыбный текст» для дизайнерского макета

Допустим, вы делаете прототип социальной сети. Но вместо дизайна, вы тратите время на рыбный текст: придумываете имена пользователей и вручную добавляете их в макет. Такую работу упростит GPT Mate. Это плагин для Фигмы, который генерирует текст и вставляет его в макет.

Если вы находитесь в России, почитайте [о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).

## Как сделать
1. [Получить АПИ-ключ OpenAI](https://platform.openai.com/account/api-keys).
2. [Установить плагин GPT Mate для Фигмы](https://www.figma.com/community/plugin/1223951614916514138/GPT-Mate&amp;sa=D&amp;source=docs&amp;ust=1684725850872053&amp;usg=AOvVaw3wXg4bpF9PzN3QxsXenKfI).
3. Выделить текстовые блоки.
3. Открыть в окне плагина вкладку Settings и ввести ключ.
4. Перейти во вкладку Command и ввести промт: 
```
Напиши случайное имя и фамилию на русском языке
Не добавляй точки или запятые
```

Результат:

<img src="media/placeholder-screenshot-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/placeholder-screenshot-dark.png#gh-dark-mode-only">

## Что может пойти не так

GPT Mate посылает в ЧатГПТ новый запрос для каждого выделенного поля. Поэтому важно описывать в промте содержание одного поля, а не всех. Например, если написать &laquo;случайные русские имена&raquo;, GPT Mate добавит в каждое поле несколько имён.

Если в промте нет строчки о знаках препинания, ЧатГПТ иногда будет добавлять лишние знаки к именам.

## В этом рецепте
Приёмы: [`промт с инструкцией`](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE)

Инструменты: `ChatGPT`, `OpenAI API`, `Figma`, `GPT Mate`

## 

[Все рецепты](https://github.com/Open-Prompting/Knowledge-Base/tree/main#%D1%80%D0%B5%D1%86%D0%B5%D0%BF%D1%82%D1%8B)

[Все приёмы](https://github.com/Open-Prompting/Knowledge-Base/tree/main#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE) 

[Как добавить рецепт рецепт](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/articles/contributing)
