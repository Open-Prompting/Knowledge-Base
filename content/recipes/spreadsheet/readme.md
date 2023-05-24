![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/cover-spreadsheet-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/cover-spreadsheet-light.svg#gh-light-mode-only)

# Собрать данные и&nbsp;вывести их&nbsp;в&nbsp;таблицу

Допустим, вы&nbsp;оцениваете рынок городов в&nbsp;Европе. Для этого нужны данные о&nbsp;населении крупнейших городов. Чтобы собрать эту информацию в&nbsp;Гугле, придётся потратить минут сорок. Попросите ЧатГПТ найти данные и&nbsp;заполнить Гугль-таблицу.

Если вы работает из России, почитайте [о&nbsp;работе ЧатГПТ в&nbsp;разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).


## Как сделать
1. [Получить ключ ОупенЭйАй](https://platform.openai.com/account/api-keys).
2. [Установить расширение для Гугль-таблиц&nbsp;&mdash; GPT For Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654).
3. Открыть в&nbsp;Гуль-таблицах новый файл.
4. Ввести в настройках расширения ключ АПИ. В&nbsp;главном меню выбрать Расширения → GPT for Sheets and Docs → Set&nbsp;API&nbsp;key. В&nbsp;появившемся окне ввести ключ.
5. Написать в&nbsp;любой ячейке функцию и&nbsp;в&nbsp;скобках указать аргумент&nbsp;&mdash; промт:
```
=gpt_table("10 крупнейших городов Европы, 
страна, население, процент от населения страны, 
координаты, телефонный код страны, язык")
```
Результат:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/sheet-screenshot-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/sheet-screenshot-dark.png#gh-dark-mode-only" width="70%" height="70%">


## Что может пойти не так
Этот метод не&nbsp;подойдёт, когда нужны актуальные данные, ЧатГПТ использует информацию до&nbsp;2021&nbsp;года.

## В этой статье
Приёмы: `Промт с инструкцией`

Инструменты: `ChatGPT`, `OpenAI API`, `Google Sheets`, `GPT For Sheets and Docs`

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты), [Предложить свой рецепт](#)
