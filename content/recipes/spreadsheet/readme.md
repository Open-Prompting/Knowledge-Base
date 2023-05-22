![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/cover-spreadsheet-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/cover-spreadsheet-light.svg#gh-light-mode-only)

# Собрать данные и вывести их в таблицу

Вы&nbsp;оцениваете рынок городов в&nbsp;Европе. Для этого нужны данные о&nbsp;населении крупнейших городов. Чтобы собрать эту информацию в&nbsp;Гугле, придётся потратить минут сорок. Попросите ЧатГПТ найти данные и&nbsp;заполнить гугль-таблицу.

Если вы работает из России, почитайте [о&nbsp;работе ЧатГПТ в&nbsp;разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).


## Как сделать
1. [Получить ключ ОупенЭйАй](https://platform.openai.com/account/api-keys).
2. [Установить расширение для гугль-таблиц&nbsp;&mdash; GPT For Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654).
3. Открыть в&nbsp;Гуль-таблицах новый файл.
4. Ввести в настройках расширения ключ АПИ. В главном меню выбрать Расширения → GPT for Sheets and Docs. Нажать пункт Set API key и ввести в него ключ.
5. Написать в&nbsp;любой ячейке функцию и&nbsp;в&nbsp;скобках указать аргумент&nbsp;&mdash; промт:
```
=gpt_table(10 крупнейших городов европы, 
страна, 
население, 
процент от населения страны, 
координаты, 
телефонный код страны,
язык)
```

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

## Обратите внимание
Этот метод не&nbsp;подойдёт, когда нужны актуальные данные, ЧатГПТ использует информацию до&nbsp;2021&nbsp;года.

## В этой статье
Приёмы: `Промт с инструкцией`

Инструменты: `ChatGPT`, `OpenAI API`, `Google Sheets`, `GPT For Sheets and Docs`

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты), [Предложить свой рецепт](#)
