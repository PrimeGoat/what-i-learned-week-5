# What I Learned in Week 5

## Week 4 was about arrays.  I learned to declare and modify arrays using array syntax and array methods.

### Arrays
Arrays are ordered lists in JavaScript.  Each array element is associated with its array index, which is numerical and starts with `0`.

Arrays are expressed as a list of items within brackets (`[` and `]`) with each element separated by a comma (`,`).  Arrays can contain arrays nested within them.  Here's an example of an array declaration and array element access below:
```
const myArray = [1, 2, 3, "four", ["red", "green", "blue"]];
myArray[0];     // 1
myArray[3];     // "four"
myArray[4];     // ["red", "green", "blue"]
myArray[4][1];  // "green"
```

### Array Methods
There are a number of array methods that allow for the manipulation of arrays.

- `pop()`: Removes an element from the end of an array and returns its value.
- `push(item1, item2, ...)`: Adds elements to the end of an array and returns the array length.
- `shift()`: Removes an element from the beginning of an array and returns its value.
- `unshift(item1, item2, ...)`: Inserts elements to the beginning of an array and returns the array length.
- `includes(item)`: Searches for a value within the array and returns a boolean value representing whether the value was found or not.
- `reverse()`: Reverses the elements in the array.
- `split(splitChar)`: Splits a string into an array using `splitChar` as a separator that splits the string into pieces and returns the new array.
- `join(joinChar)`: Joins an array's elements into a string, optionally separated by `joinChar`.
- `slice(start, end)`: Returns an array consisting of a slice of the original array starting from the `start` index, going all the way to but not including the `end` index.
- `splice(start, count, replacement1, replacement2, ...)`: Replaces elements in an array, modifying the original array.  Removes `count` elements starting from `start` index and optionally inserts an arbitrary amount of elements into the array where the elements were removed from.  If `count` is `0` and no elements are removed, new elements are inserted before the indexed element.
