![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/1da4d236fd3b673b92087a1bf1935fc223e79b2f/content/recipes/spreadsheet/media/cover-spreadsheet-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/1da4d236fd3b673b92087a1bf1935fc223e79b2f/content/recipes/spreadsheet/media/cover-spreadsheet-light.svg#gh-light-mode-only)

# Собрать данные и вывести их в таблицу

Вы&nbsp;оцениваете рынок городов в&nbsp;Европе. Для этого нужны данные о&nbsp;населении крупнейших городов. Чтобы собрать эту информацию в&nbsp;Гугле, придётся потратить минут сорок. Попросите ЧатГПТ найти данные и&nbsp;заполнить гугль-таблицу.

Если вы работает из России, почитайте [о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/content/articles/ruchatgpt/ruchatgpt.md).


## Что сделать
1. [Получить ключ ОупенЭйАй](https://platform.openai.com/account/api-keys).
2. [Установить расширение для гугль-таблиц&nbsp;&mdash; GPT For Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654).
3. Открыть в&nbsp;Гуль-таблицах новый файл.
4. Ввести в настройках расширения ключ АПИ. В главном меню выбрать Расширения → GPT for Sheets and Docs. Нажать пункт Set API key и ввести в него ключ.
5. Написать в&nbsp;любой ячейке функцию и&nbsp;в&nbsp;скобках указать аргумент&nbsp;&mdash; промт с&nbsp;инструкцией:
```
=gpt_table(10 крупнейших городов европы, 
страна, 
население, 
процент от&nbsp;населения страны, 
координаты, 
телефонный код страны,
язык)
```

Этот метод не&nbsp;подойдёт, когда нужны актуальные данные, ChatGPT использует информацию до&nbsp;2021&nbsp;года.

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты)

[Предложить свой рецепт](#)
