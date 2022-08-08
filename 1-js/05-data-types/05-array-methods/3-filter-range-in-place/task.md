importance: 4

---

# Filter range "in place"

Napisz funkcję `filterRangeInPlace(arr, a, b)` która bierze tablicę `arr`i usuwa z niej wszystkie wartości poza tymi między  `a` i `b`. Testem jest: `a ≤ arr[i] ≤ b`.

Funkcja powinna zmieniać tylko tablice. Nie powinna zwracać byle czego.

Dla przykładu:
```js
let arr = [5, 3, 8, 1];

filterRangeInPlace(arr, 1, 4); // usuwa numery poza 1 i 4.

alert( arr ); // [3, 1]
```
