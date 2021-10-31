# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code happens "one at a time", so if one section takes some time to complete then it will pause your whole program. Asynchronous can wait for things to happen and return to that once it's ready without stopping all the code. 
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
This is how we used ProxyState. So you can define when something changes, invoke this function. Used in asynchronous operations. 
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-closed. "Software entities ... should be open for extension, but closed for modification." https://web.archive.org/web/20150905081105/http://www.objectmentor.com/resources/articles/ocp.pdf
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
It's a function passed as an argument, or returns a function as its result. 
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
It's a way to create asynchronous code saying "I'll do this and then you do that". You use .catch to catch errors. 
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Post, Get, Put. 
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface. 
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service layer. 
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Hiding or restricting access to data, or making code easier to understand and maintain. 
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200 ok
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Internal server error. Something probably wrong on their end. 
```