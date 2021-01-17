# Arrow function exercise
In this exercise, you’ll refactor some ES5 code into ES2015.
### ES5 Map callback

```javascript
function double(arr){
    return arr.map(val => val * 2)
}
```

### ES2015 Arrow Functions Shorthand
Refactor the above code to use two arrow functions. Turn it into a one-liner.
```javascript 
const double = arr => arr.map(val => val * 2)
```

### Refactor the following function to use arrow functions:
Replace ALL functions with arrow functions:

```javascript
    const squareAndFindEvens = numbers=>
    numbers.map(num => num ** 2).filter(square => square % 2 ===  0)
```