[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# JavaScript Arrays

## Objectives

By the end of this, developers should be able to:

- Define an array
- Store, access, and update data values in arrays
- Iterate over items in an array


## Preparation

1. Fork and clone this repository
1. Create a new branch, `training`, for your work and change into it.


![images/arrays1](images/arrays1.png)

![images/arrays2](images/arrays2.png)

![images/arrays3](images/arrays3.png)

![images/arrays4](images/arrays4.png)

![images/arrays5](images/arrays5.png)

![images/arrays6](images/arrays6.png)

![images/arrays7](images/arrays7.png)

![images/arrays8](images/arrays8.png)

### Code Along: Arrays

In JavaScript to represent a list we can use an [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).
Elements in an `Array` or items in our list are ordered. JavaScript arrays are
zero-indexed: the first element of an array is at index 0, and the last element
is at the index equal to the value of the array's length property minus 1. Using
an invalid index number returns `undefined`.

```js
// Create an empty array literal
const list = [];

// Create an array literal with values
const anotherList = ['Nelly', 100, false, 2];

// Read value from an Array, use index
anotherList[0]; // 'Nelly'
anotherList[2]; // false

// Update value in an Array, use index
anotherList[2] = true;
anotherList; // ['Nelly', 100, true, 2]

// Add value to an Array, use index
anotherList[5] = 'Add Me';
anotherList; // ['Nelly', 100, true, 2, undefined, 'Add Me']
```

## Array Methods

![images/arrays9](images/arrays9.png)

![images/arrays10](images/arrays10.png)

![images/arrays12](images/arrays12.png)

![images/arrays13](images/arrays13.png)

![images/arrays14](images/arrays14.png)

![images/arrays15](images/arrays15.png)

## Iterating through Arrays


#### Code Along: Iterate through an Array

```js
const developers = ['Ahmad', 'Mike', 'Sami']

// Individually print message for each item in array
console.log('Hello ' + developers[0])
console.log('Hello ' + developers[1])
console.log('Hello ' + developers[2])

// Loop through array using i as the index
for (let i = 0; i < developers.length; i++) {
  console.log('Hello ' + developers[i])
}
```





## Array Resources

- https://javascript.info/array
- https://javascript.info/array-methods
- https://medium.freecodecamp.org/javascript-arrays-and-objects-are-just-like-books-and-newspapers-6e1cbd8a1746
- https://www.codeanalogies.com/objects-arrays-practice/
