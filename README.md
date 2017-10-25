# Map

### Explanation
You will need to use the `.map()` method to complete these exercises.


### Setup


### Reminder
The map method is executed on an array and returns a new transformed array.

It accepts a function as an argument.

The function-argument that you pass to `.map()` will be executed each element in the array.

Inside the function-argument, you will need to return a value. This value is added to the returned array.


```js
let originalArray = ['wow', 'cool', 'superb']

let someNewArray = originalArray.map(function(arrayElement, index, originalArray){
   return arrayElement.length
})

originalArray //=> ['wow', 'cool', 'superb']
someNewArray //=> [3,4,6]
```
