## "Shapes" of `Object`s

Many functions operate on `Object` types that need to have particular keys with corresponding values of specific data types. In
such cases, it's useful to name the 'shapes' of `Object` that functions expect.
You might say that a 'Person' is an `Object` that has keys 'name' and 'age'. You
might write:

```js
// Person: {
//  name: string,
//  age: number,
// }
```

to represent the 'shape' of a Person.

When you have functions like the following, you can use the shorthand to write
the type of the input and output.

```js
function getName(person) {
  return person.name;
}

function getAge(person) {
  return person.age;
}

function makePerson(name, age) {
  return {
    name: name,
    age: age
  };
}

function birthday(person) {
  person.age += 1;
  return person;
}

// Point: {
// x: number
// y: number
// name: string
//}

function getDistance(pointA, pointB) {
  return Math.sqrt((pointA.x - pointB.x) ** 2 + (pointA.y - pointB.y) ** 2);
}
```

### Fill in the table referencing the functions above and using the 'shape' shorthand

| Function      | types of inputs | type of output |
| ------------- | --------------- | -------------- |
| `getName`     | _Person: {_     | _string_       |
|               | _name: string,_ |                |
|               | _age: number,_  |                |
|               | }               |                |
| `getAge`      | Person          | number         |
| `makePerson`  | string, age     | Person         |
| `birthday`    | Person          | Person         |
| `getDistance` | Point, Point    | number         |


[Main menu](README.md) | [Exercise 3 - Function Signatures](ex3.md)
