# CSS - Selectors

Es gibt verschiedene Selektoren, um die verschiedenen Elemente in CSS anzusprechen.

- id - selector: spricht das Element mit einer bestimmten ID an. IDs sind nicht wiederverwendbar (wie z.B. classes) und hart zu überschreiben.

```css
#id {
  color: blue;
}
```

- class - selector: spricht Elemente einer bestimmten Klasse an. Es können mehrere Elemente die gleiche Klasse haben.

```css
.class {
  background-color: green;
}
```

- attribute - selector: wählt Elemente an, die über ein bestimmtes Attribut verfügen. Das Attribut wird in eckigen KLammern angegeben.

```css
[attribute] {
  ...;
}
```

Hier werden alle Elemente mit der class "Card" und dem attribute "role = list" angesprochen:

```css
.card[role="list"] {
  ...;
}
```

## Pseudo-Klassen

Manchmal möchte man ein HTML anders stylen, wenn es sich in einem bestimmten Zustand befindet. Das kann man mit **Pseudoklassen** machen. Pseudoklassen werden einem Selector mit ":" angehängt.

- hovered Elements:

```css
h2:hover {
  ...;
}
```

- active Elements (z.B. gedrückter Button):

```css
button:active {
  ...;
}
```

- geklickte Links

```css
a:visited {
  ...;
}
```

- ausgewähltes form-input Element:

```css
input:focus {
  ...;
}
```

Es gibt noch weitere Pseudoklassen.

## Pseudo-Elemente

Mit Pseudo-Elementen lassen sich bestimmte Teile eines Elementes stylen, z.B. die erste Zeile von einem p-Element, oder der erste Buchstabe. Pseudo-Elemente werden dem Selector mit "::" angehängt.

- erste Zeile von Paragrafen:

```css
p::first-line {
  ...;
}
```

---

## Combinator

Mit Combinators kann man verschiedene Selektoren verknüpfen.

- `(space)` : a specific element somewhere inside another specific element (regardless of nesting
  level)
  - `h2 span`: any span inside an h2
  - `.card button`: all buttons inside an element with the class "card"
- `>` : targeting a direct descendant of another element
  - `h2>span`: all spans which are direct children of an h2
  - `.card>button`: all buttons which are direct children of an element with the class "card"
- `~` : any later sibling element after another element
  - `h2~span`: any span which is a later sibling of an h2
- `+` : the direct sibling element after another element
  - `.card+button`: a button coming directly after an element with the class "card"
