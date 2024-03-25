# Lista

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li

## Lista HTML sin ordenar (unordered list)
Una lista sin ordenar comienza con la etiqueta `<ul>`. Cada elemento de la lista empieza con la etiqueta
`<li>`. Los elementos de la lista estarán marcados con viñetas (pequeños círculos negros) de forma
predeterminada:
```html
<ul>
    <li>Manzana</li>
    <li>Pera</li>
    <li>Piña</li>
</ul>
```

## Lista HTML ordenada (ordered list)
Una lista ordenada comienza con la etiqueta `<ol>`. Cada elemento de la lista
empieza con la etiqueta `<li>`.
Estos elementos estarán marcados con números de forma predeterminada:
```html
<ol>
    <li>Manzana</li>
    <li>Pera</li>
    <li>Piña</li>
</ol>
```

## Listas HTML de descripción
HTML también permite listas de descripción.
Una lista de descripción es una lista de términos con una descripción para cada uno.
La etiqueta `<dl>` define la lista de descripción, la etiqueta `<dt>` define el término (nombre), y la
etiqueta `<dd>` describe cada término:
```html
<dl>
    <dt>Manzana</dt>
    <dd>-verdes o rojas</dd>
    <dt>Pera</dt>
    <dd>-amarillas o rojas</dd>
</dl>
```

## Lista anidada (nested)
Anidado: algo organizado en una serie de capas, una dentro de la otra.
```html
<h1>Example 2</h1>
<ul>
    <li>computers</li>
    <li>cars</li>
    <ul>
        <li>Ford</li>
        <li>BMW</li>
    </ul>
    <li>Skoda</li>
</ul>
```
![](/01-html/images/list-tag.png)

Crea un archivo HTML con los siguientes atributos:
1. Crea un título h1 que contenga "Mis mejores amigos".
2. Crea una lista de tus mejores amigos