![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/cover-spreadsheet-dark.svg#gh-dark-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/cover-spreadsheet-light.svg#gh-light-mode-only)

# Собрать данные и вывести их в таблицу

Допустим, вы оцениваете рынок городов в Европе. Для этого нужны данные о населении крупнейших городов. Чтобы собрать эту информацию в Гугле, придётся потратить минут сорок. Попросите ЧатГПТ найти данные и заполнить Гугль-таблицу.

Если вы в России, почитайте [о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).

## Как сделать
1. [Получить ключ ОпенАИ](https://platform.openai.com/account/api-keys).
2. [Установить расширение для Гугль-таблиц &mdash; GPT For Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654).
3. Открыть в Гуль-таблицах новый файл.
4. Ввести в настройках расширения ключ АПИ. В главном меню выбрать Расширения → GPT for Sheets and Docs → Set API key. В появившемся окне ввести ключ.
5. Написать в любой ячейке функцию и в скобках указать аргумент &mdash; промт:
```
=gpt_table("10 крупнейших городов Европы, 
страна, население, процент от населения страны, 
координаты, телефонный код страны, язык")
```
Результат:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/sheet-screenshot-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/spreadsheet/media/sheet-screenshot-dark.png#gh-dark-mode-only" width="70%" height="70%">


## Что может пойти не так
Этот метод не подойдёт, когда нужны актуальные данные, ЧатГПТ использует информацию до 2021 года.

## В этом рецепте
Приёмы: [`промт с инструкцией`](https://github.com/Open-Prompting/Knowledge-Base#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE)

Инструменты: `ChatGPT`, `OpenAI API`, `Google Sheets`, `GPT For Sheets and Docs`

## 
[Все рецепты](https://github.com/Open-Prompting/Knowledge-Base/tree/main#%D1%80%D0%B5%D1%86%D0%B5%D0%BF%D1%82%D1%8B)

[Все приёмы](https://github.com/Open-Prompting/Knowledge-Base/tree/main#%D0%BF%D1%80%D0%B8%D1%91%D0%BC%D1%8B-%D1%81%D0%BA%D0%BE%D1%80%D0%BE) 

[Как добавить рецепт](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/articles/contributing)

