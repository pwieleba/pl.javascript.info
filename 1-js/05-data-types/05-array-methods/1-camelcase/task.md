importance: 5

---

# Zamień border-left-width w borderLeftWidth

Napisz funkcję `camelize(str)` która zamienia słowa odseparowane "-" takie jak "my-short-string" w camel-cased "myShortString".

To znaczy: usuń wszystkie myślniki, każde słowo po myślniku powinno zaczynać się z dużej litery.

Przykłady:

```js
camelize("background-color") == 'backgroundColor';
camelize("list-style-image") == 'listStyleImage';
camelize("-webkit-transition") == 'WebkitTransition';
```

P.S. Wskazówka: użyj `split` by podzielić ciąg (string) na tablice (array), przekształć je i  `join` ponownie.
