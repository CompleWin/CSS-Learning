# Cвойства шрифтов

## Размер шрифта

```css
.text-area {
    font-size: 24px;
}
```
```css
.text-area {
    font-size: 24pt;
}
```
```css
.text-area {
    font-size: 120%;
}
```
```css
.text-area {
    font-size: 1.2em;
}
```
```css
.text-area {
    font-size: 1.5rem;
}
```

1px (пиксель) -- абсолютная единица измерения и обозначает один пиксель на экране.  
Реальный размер в пикселях будет зависеть от плотности пикселей на экране (DPI)

1pt (пункт) -- относительная единица измерения, используемая в печати. 1 пункт равен приблизительно 1/72 дюйма.  
В веб-дизайне, размер в пунктах может варьироваться в зависимости от настроек пользователя и устройства.

### em
```css
body {
    font-size: 16px;
}

p {
    font-size: 1.2em;
    /* Размер шрифта будет 1.2 * 16px = 19.2px */
    /* Размер шрифта определяется относительно размера родительского элемента*/
}
```

### rem (root element)
```css
html {
    font-size: 20px;
}

p {
    font-size: 1.5rem;
    /* Размер шрифта будет 1.5 * 20px = 30px */
    /* Размер шрифта определяется относительно размера корневого элемента*/
}
```

## Насыщенность шрифта

```css
h1 {
    font-weight: normal;
}
```
```css
h1 {
    font-weight: bold;
}
```
```css
h1 {
    font-weight: 300;
}
```

## Стиль шрифта

```css
h1 {
    font-style: italic;
}
```
```css
h1 {
    font-style: oblique;
}
```

## Выбор шрифта

```css
body {
    font-family: "Helvetica", Arial, sans-serif;
}
```
```css
body {
    font-family: ..., ..., serif;
}
```
```css
body {
    font-family: ..., ..., sans-serif;
}
```
```css
body {
    font-family: ..., ..., Monospace;
}
```
```css
body {
    font-family: ..., ..., Cursive;
}
```
```css
body {
    font-family: 
                 "Какой-то шрифт1",
                 "Какой-то шрифт2",
                 "Какой-то шрифт3",
                 "Семейство шрифтов";
}
```

## text-align: Горизонтальное выравнивание текста

```css
.article-text {
    text-align: center;
}
```
Выравнивание текста:
- left: по левому краю
- right: по правому краю
- center: по центру
- justify: по обоим краям (по ширине)
