# Array.prototype.reduce()

Executes a reducer function on each element of the array,
resulting in a single output value.

```js
const numberGroupToBeReduced = [2, 4, 6, 8]

const reducer = (accumulator, currentValue) => accumulator + currentValue

const numberGroupReduced = numberGroupToBeReduced.reduce(reducer)

console.log(numberGroupReduced) // logs: 20
```
