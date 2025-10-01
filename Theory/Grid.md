# Grid

Позволяет создавать сетки, состоящие из строк и столбцов, по которым можно размещать элементы. 

```css
.grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-gap: 10px;
}

.item {
    background-color: #3498db;
    color: white;
    padding: 20px;
}

<div class="grid-container">
    <div class="item">Элемент 1</div>
    <div class="item">Элемент 2</div>
    <div class="item">Элемент 3</div>
</div>
```

## Немного примеров

[Пример 1](/Theory/Grid-Examples/Grid4.md)  
[Пример 2](/Theory/Grid-Examples/Grid5.md)


