# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, const, and var. Const creates immutable variables, let are mutable variables, and var are variables with global scope. 
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a block of code that can be reused and invoked in different sections of code. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single-responsibility, which means dividing the functionality into portions. Open-closed principle, which is similar to single responsibility, and states code should be open to being expanded but closed to being modified. There's the Liskov substitution, which I don't fully understand. Interface segregation principle, which is similar to single-responsibility but for interfaces. The last is dependency inversion principle, which I also don't fully understand. 
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2, arrays start at 0
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->

```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
let yes = true;
if (yes == true){console.log("yes is true")}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
Harrison calls it an "afterthought" I think, but it could also be an incrementer or decrementer. i++ would add one each iteration. 
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. index.html 
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
array, boolean, null, undefined, number, bigInt, string, symbol, and object. 
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is the sticky note applied to the value being passed into the function, and this value or variable is the argument. 
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
It's like the difference between actual data and creating pointers to said data. Two arrays of identical data aren't strictly equal, but if you have one array of data and then a separate array assigned to the first array, they are strictly equal. This post helped me: https://stackoverflow.com/a/13268731/16329596
```