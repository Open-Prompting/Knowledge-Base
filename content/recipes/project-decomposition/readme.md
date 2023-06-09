![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/project-decomposition/media/cover-project-decomposition-light.svg#gh-light-mode-only)
![cover](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/project-decomposition/media/cover-project-decomposition-dark.svg#gh-dark-mode-only)

# Сделать черновик декомпозиции задачи по проекту
Допустим, вы хотите интегрировать СРМ-систему с программой 1С, чтобы создавать счета для клиентов. Чтобы понять, сколько ресурсов уйдёт на этот проект и какие понадобятся инструменты и специалисты, задачу придётся декомпозировать. Нейросети быстрее людей разбивают сложные задачи на более простые. Попросите ЧатГПТ написать черновик декомпозиции задачи по проекту.

Если вы в России, почитайте [о работе ЧатГПТ в разных регионах](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/articles/ruchatgpt/).

## Как сделать
1. Описать проект: `проект — интеграция СРМ-системы с программой 1С`.
2. Добавить контекст: `тип интеграции — выставление счетов`.
3. Дать задание: `декомпозируй задачу`.
4. Ввести промт:
```
Проект — интеграция СРМ-системы с программой 1С.
Тип интеграции — выставление счетов.
Декомпозируй задачу.
```

Результат:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/project-decomposition/media/project-decomposition-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/recipes/project-decomposition/media/project-decomposition-dark.png#gh-dark-mode-only" width="70%" height="70%">

## Что может пойти не так
ЧатГПТ может недостаточно детально декомпозировать сложную задачу. Если нейросеть предложила неполный и недостаточно подробный план, примените итеративный подход. Попросите ЧатГПТ разбить задачу на несколько промежуточных и декомпозируйте каждую из них отдельно.

## В этой статье
Приёмы: [`дать инструкцию`](https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/methods/instruction/)

Инструменты: `ChatGPT`
