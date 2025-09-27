# Адаптивный дизайн

## Медиа-запросы

Это технология, позволяющая применять стили в зависимости от различных характеристик устройства

Данное свойство примениться только к экранам, чье разрешение будет меньше 600 пикселей:
```css
@media screen and (max-width: 600px) {
    /* Свойство1: Значение*/
    /* Свойство2: Значение*/
    /* СвойствоN: Значение*/
}
```

Больше про медиазапросы: [Использование](https://developer.mozilla.org/ru/docs/Web/CSS/CSS_media_queries/Using_media_queries), [Справочная](https://developer.mozilla.org/ru/docs/Web/CSS/@media#media_features)

## Grid

Инструмент для создания гибких и красивых сеток на веб-страницах.

```html
<div class="grid-container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
</div>
```
```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Две колонки с равной шириной */
    gap: 10px; /* Промежуток между ячейками */
}

.item {
    background-color: #3498db;
    color: #fff;
    padding: 20px;
    text-align: center;
}
```

[Пример 1](./Grid-Examples/Grid1.md)  
[Пример 2](./Grid-Examples/Grid2.md)  
[Пример 3](./Grid-Examples/Grid3.md)  

## Flexbox

Инструмент для создания различных адаптивных макетов.

```html
<div class="flex-container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
</div>
```

```css
.flex-container {
    display: flex;
    justify-content: space-between; /* Размещает ячейки с равным пространством между ними */
    align-items: center;
}

/* 
    justify-content:
    flex-start: Items align to the left side of the container.
    flex-end: Items align to the right side of the container.
    center: Items align at the center of the container.
    space-between: Items display with equal spacing between them.
    space-around: Items display with equal spacing around them.
*/

.item {
    background-color: #e74c3c;
    color: #fff;
    padding: 20px;
    text-align: center;
    flex: 1;
    margin: 5px;
}
```

[Пример 1](./Flex-Examples/Flex1.md)  
[Пример 2](./Flex-Examples/Flex2.md)





