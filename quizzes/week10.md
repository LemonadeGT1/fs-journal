# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It's used to declare a scope that contains a set of related objects.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class is a reference type, while a struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
the constructor
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
return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
it is preventing instantiation
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
the method may be overridden
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private, public, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the class or method itself
```