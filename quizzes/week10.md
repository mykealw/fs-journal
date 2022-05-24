# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes are private by default and structs are public by default. 

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Methods that have no return are a "Void". 

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
The access modifier in the example above is "public".

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
In the above example string is indicitive of the reference type!

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
In the example above abstract that cannot be instantiated but it can be inherited. 

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method, property, indexer, or event declaration and allow for it to be overridden in a derived class. For example, this method can be overridden by any class that inherits it.

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Four access modifier are:
1)public 
2)private 
3)protected 
4)internal 

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The type or member can be accessed only by code in the same class or struct.

```