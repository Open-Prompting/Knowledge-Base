![cover](https://github.com/Open-Prompting/Open-Prompting/blob/ce565a41c1629b22a152379900b6faafe32b0163/images/cover-data-light.svg#gh-light-mode-only)
![cover](https://github.com/Open-Prompting/Open-Prompting/blob/ce565a41c1629b22a152379900b6faafe32b0163/images/cover-data-dark.svg#gh-dark-mode-only)

# Собрать данные и вывести их в таблицу

Вы&nbsp;оцениваете рынок городов в&nbsp;Европе. Для этого нужны данные о&nbsp;населении крупнейших городов. Чтобы собрать эту информацию в&nbsp;Гугле, придётся потратить минут сорок. Попросите ЧатГПТ найти данные и&nbsp;заполнить гугль-таблицу.

[Если вы работает из России, почитайте о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/4bc207e6c151bc60f8d44f9064425be4a603e976/content/articles/ruchatgpt/ruchatgpt.md)

## Что сделать
1. [Получить ключ OpenAI](https://platform.openai.com/account/api-keys).
2. [Установить расширение для гугль-таблиц&nbsp;&mdash; GPT For Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654).
3. Открыть в&nbsp;Google Sheets новый файл.
4. Ввести в&nbsp;настройках расширения API-ключ. Выбрать в&nbsp;меню Google Sheets пункт &laquo;Расширения&raquo; и&nbsp;открыть GPT for Sheets and Docs. Там найти пункт Set API key и&nbsp;ввести в&nbsp;него ключ OpenAI.
5. Написать в&nbsp;любой ячейке функцию и&nbsp;в&nbsp;скобках указать аргумент&nbsp;&mdash; промт с&nbsp;инструкцией:
> =gpt_table(10 крупнейших городов европы, страна, население, процент от&nbsp;населения страны, координаты, телефонный код страны, язык)

Этот метод не&nbsp;подойдёт, если вам нужны актуальные данные, ChatGPT использует информацию до&nbsp;2021&nbsp;года.

[Все рецепты](https://github.com/Open-Prompting/Open-Prompting/blob/main/README.md#user-content-рецепты)

[Предложить свой рецепт](#)
