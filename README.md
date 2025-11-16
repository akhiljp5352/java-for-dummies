# java-for-dummies

## Download java jdk

## Download an editor

Popular ones are 
- netbeans
- eclipse
- intellij

## Anatomy of Java Programs

The smallest building blocks are `functions`. A `function` is a block of code that performs a task.

### Functions

```java
returnType functionName(params) {
  ...
}
```

`returnType` is the type of the data that is returned by the function. If the function doesn't return anything, keyword `void` is used.

Every Java program should have a `main()` function. `main()` is the entry point. Whenever a Java program is called, the `main()` is executed.

`Functions` cannot exist independently. They must always belong to a class.

### Class

A class is a container for one or more related functions. Every Java program must contain one class that contain the `main()`, that class is also `main`.

```java
class Main {
  void main() {
    ...
  }
}
```
We refer the `functions` inside the class as `methods`.

In Java, all these classes and methods should have `access modifiers`.

