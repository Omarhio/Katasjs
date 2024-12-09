# Minimum

Write a function min that takes two arguments and returns their minimum.


```
console.log(min(0, 10));
// → 0
console.log(min(0, -10));
// → -10

```

```js
function min(number1, number2) {

    if (number1 < number2) {
        return number1;
    } else {
        return number2;
    }
}
console.log(min(0, 10));