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

In Java, all these classes and methods should have an `access modifier`.

### Access Modifier

It is a special keyword that determines if other methods and classes can access this class or method. The common ones are:
- private
- public

```java
public class Main {
  public static void main() {
    ...
  }
}
```
The above is the basic structure of a java program. `main()` in the program should be always `static`.

### Naming Conventions

- For `classess` we use Pascal. eg: ClassName.
- For `methods` we use camelCase. eg: functionName.

## My first Java Program

- Open intellij ide.
- Create new project.
- Select Java. Make sure `project sdk` is not blank.
- Create project from template. Command Line App.
- Add project name, location and package name. A `package` is a colelction of inter connected classes. Usually package name is `com.companyname`.

## How Java code gets executed?

There are two steps:
- Compilation
- Execution

### Compilation

Source Code (.java) --> Java compilor (SDK) --> Bytes code (.class)

To create the bytes code run the followig in terminal

```bash
javac Main.class
```
 Executing this will create an `out` folder. The compiled `class` file can run on any os that has `Java Runtime Environment (JRE)`

 ### Execution

 `JRE` has `Java Virtual Machine (JVM)`.

 Byte code (.class) --> JVM --> Native code for the os.

 To run:

 ```bash
java full path of class file
```
