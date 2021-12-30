# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Kind of like a filesystem, it defines and shares where you are working logically. 
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class is similar to a model, or a form that objects adhere to. A structure is similar to a class but it stores value types instead of reference and is more restricted. 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
typeof()
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The type of data that it returns, since "Vroooom" is a string.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The method is never instantiated directly.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The method can be redefined in derived classes. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only code in the same class or struct. 
```