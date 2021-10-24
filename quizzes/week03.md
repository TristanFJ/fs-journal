# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction (hiding implementation details), encapsulation (making code private), inheritance (extending properties/methods from one object to another), polymorphism (similar types performing similar things). 
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Restricting access to parts of your code, similar to single responsibility
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a blueprint, an instance is the actual thing based on that blueprint
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
It's like a clone or extension of an object that you specify what can happen to the original object 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Several things, segments code so it's more readable and maintainable, creates single responsibility of modules, separates how data is presented and accessed
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Takes in inputs and passes it on
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Business processing logic
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Data structure separate from user interface, receives input from controller
```
