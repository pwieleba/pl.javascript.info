```js run demo
function filterRange(arr, a, b) {
  // dodaje nawiasy wokół ciała funkcji dla lepszej czytelności for 
  return arr.filter(item => (a <= item && item <= b));
}

let arr = [5, 3, 8, 1];

let filtered = filterRange(arr, 1, 4);

alert( filtered ); // 3,1 (podobne wartości)

alert( arr ); // 5,3,8,1 (nie zmienione)
```
