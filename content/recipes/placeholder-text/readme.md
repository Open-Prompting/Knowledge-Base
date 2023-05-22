# Создать рыбу текста для дизайнерского макета

Вы&nbsp;делаете прототип социальной сети. Но&nbsp;вместо дизайна, вы&nbsp;тратите время на&nbsp;рыбный текст: придумываете имена пользователей и&nbsp;вручную добавляете их&nbsp;в&nbsp;макет. Такую работу упростит ГПТ Мейт. Это плагин для Фигмы, который генерирует текст и&nbsp;вставляет его в&nbsp;макет.

Если вы&nbsp;работаете из&nbsp;России, почитайте о&nbsp;работе ЧатГПТ в&nbsp;разных регионах.

## Как сделать
1. [Получить ключ ОпенАИ](https://platform.openai.com/account/api-keys)
2. [Установить плагин ГПТ Мейт для Фигмы](https://www.google.com/url?q=https://www.figma.com/community/plugin/1223951614916514138/GPT-Mate&amp;sa=D&amp;source=docs&amp;ust=1684725850872053&amp;usg=AOvVaw3wXg4bpF9PzN3QxsXenKfI).
3. Выделить текстовые блоки.
3. Открыть в&nbsp;окне плагина вкладку Settings и&nbsp;ввести ключ.
4. Перейти во&nbsp;вкладку Command и&nbsp;ввести промт: 
```
Напиши случайное имя и фамилию на русском языке
Не добавляй точки или запятые
```

Плагин добавит текст в&nbsp;макет:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/figma-light.jpg#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/placeholder-text/media/figma-dark.png#gh-dark-mode-only" width="70%" height="70%">

ГПТ Мейт посылает в&nbsp;ЧатГПТ новый запрос для каждого выделенного поля. Поэтому важно описывать в&nbsp;промте содержание одного поля, а&nbsp;не&nbsp;всех. Например, если написать &laquo;случайные русские имена&raquo;, ГПТ Мейт добавит в&nbsp;каждое поле несколько имён.

Если в&nbsp;промте нет строчки о&nbsp;знаках препинания, ЧатГПТ иногда будет добавлять лишние знаки к&nbsp;именам.

[Все рецепты](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/recipes)

[Предложить свой рецепт](#)
