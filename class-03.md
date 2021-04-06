# Class 3

* ## Maps, primitives, File I/O
* * Primitives vs. Objects

### Primitive Data Types 
The Java programming language is statically-typed, which means that all variables must first be declared before they can be used.

Doing so tells your program that a field named "gear" exists, holds numerical data, and has an initial value of "1". A variable's data type determines the values it may contain, plus the operations that may be performed on it. In addition to int, the Java programming language supports seven other primitive data types. A primitive type is predefined by the language and is named by a reserved keyword. Primitive values do not share state with other primitive values. The eight primitive data types supported by the Java programming language are: byte/short/int/long

### Objects 

Java is an object-oriented programming language.

Everything in Java is associated with classes and objects, along with its attributes and methods. For example: in real life, a car is an object. The car has attributes, such as weight and color, and methods, such as drive and brake.

---
* * Exceptions in Java 

1- What Is an Exception?

When an error occurs within a method, the method creates an object and hands it off to the runtime system. The object, called an exception object, contains information about the error, including its type and the state of the program when the error occurred. Creating an exception object and handing it to the runtime system is called throwing an exception.


2- The Catch or Specify Requirement

The Java runtime system requires that a method must either catch or specify all checked exceptions that can be thrown by that method. This requirement has several components that need further description: "catch," "specify," "checked exceptions," and "exceptions that can be thrown by that method."

3- How to Throw Exceptions

It is important to understand how to throw exceptions in Java. This will allow you to create higher quality code where errors are checked at compile time instead of runtime, and create custom exceptions that make debugging and recovery easier.

---
* * Scanner to read in a file in Java

The `Scanner` class is used to get user input, and it is found in the `java.util` package.

To use the `Scanner` class, create an object of the class and use any of the available methods found in the Scanner class documentation. In our example, we will use the `nextLine()` method, which is used to read Strings