## JS Data Types Review Questions

1. What are the basic data types in JavaScript? Fill in the table of types below
   with descriptions of the types and the operators that work on them.

2. `Object` is the basic data type that we use to build other, more specialized
   'types' of data. Name some of the ways that `Object` is used in JavaScript
   (e.g. what other types are really `Object` underneath).

## Exercise - Thinking in Types

When writing a function, it's often helpful to start by considering the inputs
and the output. In particular, knowing the data type of the inputs and the data
type of the outputs lets you know what kinds of operations are allowed on those
arguments. They also hint at what the 'right' operations to do are.

### For the following functions, fill in the table with the types of the inputs and the types of the outputs.

| Function                                              | types of inputs | type of output | _resources_                                                                                               |
| ----------------------------------------------------- | --------------- | -------------- | --------------------------------------------------------------------------------------------------------- |
| `function subtractThree(number) { return number - 3}` | _number_        | _number_ | [Subtraction(-)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Subtraction) |
| `function addFive(number) { return number + 5}`       |                 |                | [Addition(+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition)       |
| `function sum(A, B) { return A + B }`                 |                 |                | [Addition(+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition)       |
| `function concat(A, B) { return "" + A + B }`         |                 |                | [Addition(+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition)       |
| `document.querySelector`                              |                 |                | [querySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)                  |
| `window.fetch`                                        |                 |                | [fetch](https://developer.mozilla.org/en-US/docs/Web/API/fetch)                                           |


[Main menu](README.md) | [Exercise 2 - Shapes of Objects](ex2.md)