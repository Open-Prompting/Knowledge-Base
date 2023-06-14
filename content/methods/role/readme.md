# Задать роль

Один из способов уточнить задачу нейросети — описать ролевую ситуацию. Назовите профессию или известную личность для которой такая задача типична:
```
Картина Ван Гога: подсолнухи в вазе.
```
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/testing/content/methods/role/media/van-gogh.png" width="70%" height="70%">

Такой запрос называют «ролевым промтом». Он заменит более сложную и развёрнутую инструкцию:
```
Картина маслом: на фоне голубая стена в четыре пятые полтона, в центре ваза с желто-красными подсолнухами
```
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/testing/content/methods/role/media/like-van-gogh.png" width="70%" height="70%">

## Как задать роль
Чтобы задать ролевую модель, назовите нейросети имя или профессию человека, который лучше всего справился бы с задачей. Начните промт со слов `представь, что ты…` или `действуй как…`.

Другой способ задать роль — описать ситуацию или собеседника нейросети: `представь, что разговариваешь с ребёнком`.

## Что может пойти не так
Нейросеть может не знать роль, которую должна исполнить. Так, ЧатГПТ обучался преимущественно на английских текстах, поэтому лучше знаком с англоязычными фигурами, а не российскими:

<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/methods/role/media/screenshot-role-editor-light.png#gh-light-mode-only" width="70%" height="70%">
<img src="https://github.com/Open-Prompting/Knowledge-Base/blob/main/content/methods/role/media/screenshot-role-editor-dark.png#gh-dark-mode-only" width="70%" height="70%">

Нейросеть недостаточно знает про Максима Ильяхова, поэтому такая роль её путает. Про книгу Странка ЧатГПТ знает и с этой ролью справляется лучше. Если вовсе не присвоить роль, нейросеть не догадается, в чём проблема фразы «футболист нанёс удар по мячу».

## Рецепты с ролевым промтом
[Подобрать метафору для сложного термина](https://github.com/Open-Prompting/Knowledge-Base/tree/main/content/recipes/metaphor)
