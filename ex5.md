## Higher-order functions

Higher-order functions are functions that take in other functions as arguments. 
The functions they take in as arguments are 'callback functions'. If the callback 
functions will be called with particular types of arguments, it's helpful to
specify the type of function that will be passed in.

> Note: you may see the word `void` meaning 'this function does not return anything'

### Fill in the rest of the table.
For more examples of function signatures, see the Exercise 3.

| Function                       | types of inputs                                                        | type of output | function signature                                               | _resources_                                                                                              |
| ------------------------------ | ---------------------------------------------------------------------- | -------------- | ---------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `EventTarget.addEventListener` | _string, handler(e: Event): void_                                      | _void_         | _addEventListener(type: string, handler: function): void_        | [addEventListener](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)        |
| `window.setTimeout`            | callback, number                                                       | number         | setTimeout(callback: function, delay: number): timeoutID: number | [setTimeout](https://developer.mozilla.org/en-US/docs/Web/API/setTimeout)                                |
| `Array.prototype.map`          | callbackFn(element, (index, array))                                    | array          | map(callback: function): array                                   | [.map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)       |
| `Array.prototype.find`         | callbackFn(element, (index, array)): bool                              | element        | find(callback: function): element                                | [.find](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)     |
| `Array.prototype.filter`       | callbackFn(element, (index, array)): bool                              | array          | filter(callback: function): array                                | [.filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) |
| `Array.prototype.reduce`       | callbackFn(accumulator, currentVal, (currentIdx, array)), initialValue | accumulator    | reduce(callback: function): accumulator                          | [.reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce) |
                                                                                                       |



[Main menu](README.md) | [Exercise 3 - Function Signatures](ex3.md)