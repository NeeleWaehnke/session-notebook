# CSS Basics

Mit CSS (Cascading Style Sheets) kann man Styling zu einem HTML-Dokument hinzufügen.

## CSS Syntax

Die CSS Synta besteht aus 4 Teilen:

- selector
- property
- property value
- declaration
  Das Ganze wird auch "ruleset" genannt.
  ![CSS-Syntax](./assets/css-syntax.png)

| Part           | Description                                                                                       |
| -------------- | ------------------------------------------------------------------------------------------------- |
| Selector       | Addresses the element(s) to style                                                                 |
| Declaration    | Defines what to change and contains pairs of `property` and `property value`                      |
| Property       | The name of the property to change                                                                |
| Property Value | The value assigned to the property, e.g for the property `color` we use the property value `blue` |

Ein ruleset kann mehrere declarations enthalten. Es können auch mehrere elemente mit einem ruleset gestylt werden.

## CSS Selectors

Es gibt verschiedene Selektoren, mit denen Elemente angesprochen werden können.

- universal Selektor: spricht alle Elemente an
- Element/ type selector: wählt Elemente eines bestimmten Typs aus
- class selector: wählt Elemente aus, die eine bestimmte Klasse haben

## Box Model

Alle Elemente sind in einem "Box-Model" angeordnet. Dadurch können Größe und Position festgelegt werden
Die Box besteht aus 4 Teilen:

- content
- padding
- margin
- border

![Box-model](./assets/css-basics.png)

## Google Fonts einbinden

- Ordner für Font im File der Website erstellen
- font.tff Datei im Ordner speichern
  -.ttf verlinken

```css
@font-face {
  font-family: "Name of the font";
  src: url("path/to-the/font.woff");
}
```

## Weiteres

- die letzte angewandte Regel wird ausgeführt
- Google Fonts immer runterladen
- box-sizing property sollte immer border-box sein (wichtig - im universal selector anwenden)

### Stylesheet in HTML verlinken

```html
<head>
  ...
  <link rel="stylesheet" href="styles.css" />
</head>
```
