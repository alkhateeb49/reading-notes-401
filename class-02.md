# Class 2

* ## Java Imports 
* * Package declaration

Packages: The first statement, other than comments, in a Java source file, must be the package declaration.

Default package. all Java classes are in a directory, it's possible to omit the package declaration. For small programs it's common to omit it, in which case Java creates what it calls a default package. Sun recommends that you do not use default packages.



* * Package declaration syntax

To create a package, you choose a name for the package (naming conventions are discussed in the next section) and put a package statement with that name at the top of every source file that contains the types (classes, interfaces, enumerations, and annotation types) that you want to include in the package.

The package statement (for example, package graphics;) must be the first line in the source file. There can be only one package statement in each source file, and it applies to all types in the file.


* * Imports: three options

The JOptionPane class is in the swing package, which is located in the javax package. The wildcard character (*) is used to specify that all classes with that package are available to your program. This is the most common programming style.

---

* ## Different types of loops in Java
In programming languages, loops are used to execute a set of instructions/functions repeatedly when some conditions become true. There are three types of loops in Java.

* * for loop
* * while loop
* * do-while loop