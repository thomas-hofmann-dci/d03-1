## Basic String Methods:
- Converting case with:
  `String.prototype.toUpperCase()`, `String.prototype.toLowerCase()`
- Extracting parts of a string: `String.prototype.substring()`
- Checking if a string is inside another string: `String.prototype.includes()`
- Removing padding spaces: `String.prototype.trim()`

## Number:
- Combining strings and numbers with +
- Integers vs. Floats
- Converting strings into Numbers: `parseInt()`, `parseFloat()`
- Using modulo

## Math:
- Rounding up with `Math.ceil()`
- Rounding down with `Math.floor()`
- Getting random numbers with `Math.random()`
- Maximum and minimum with `Math.max()`, `Math.min()`

## Number Pitfalls:
- Dealing with NaN: `isNaN(<expression>)`, `typeof NaN`
- Very long numbers: `e`, rounding errors
- Dealing with rounding errors: `Number.prototype.toFixed()` [MDN: toFixed()](https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed)
- Division pitfalls: Dealing with `Infinity`
