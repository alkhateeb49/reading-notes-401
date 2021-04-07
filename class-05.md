# Class 5

* ## Linked Lists
* * What is a Linked List<br/>
a linked list is a linear collection of data elements whose order is not given by their physical placement in memory. Instead, each element points to the next. It is a data structure consisting of a collection of nodes which together represent a sequence. In its most basic form, each node contains: data, and a reference (in other words, a link) to the next node in the sequence. This structure allows for efficient insertion or removal of elements from any position in the sequence during iteration.

* * What does it look like<br/>
![Linked Lists](img/LinkedList.png)<br/>
The best way to approach a traversal is through the use of a `while()` loop. This allows us to continually check that the `Next` node in the list is not `null`. If we accidentally end up trying to traverse on a node that is `null`, a `NullReferenceException` gets thrown and our program will crash/end.

---
* ## What’s a Linked List, Anyway

* * Linear data structures:<br/>
A Linear data structure have data elements arranged in sequential manner and each member element is connected to its previous and next element. This connection helps to traverse a linear data structure in a single level and in single run. Such data structures are easy to implement as computer memory is also sequential. Examples of linear data structures are List, Queue, Stack, Array etc.<br/>
* * Memory management:<br/>
Memory management is the process of controlling and coordinating computer memory, assigning portions called blocks to various running programs to optimize overall system performance. Memory management resides in hardware, in the OS (operating system), and in programs and applications.<br/>
* * Big O<br/>
Big O notation is a mathematical notation that describes the limiting behavior of a function when the argument tends towards a particular value or infinity. Big O is a member of a family of notations invented by Paul Bachmann,[1] Edmund Landau,[2] and others, collectively called Bachmann–Landau notation or asymptotic notation.<br/>
In computer science, big O notation is used to classify algorithms according to how their run time or space requirements grow as the input size grows.[3] In analytic number theory, big O notation is often used to express a bound on the difference between an arithmetical function and a better understood approximation; a famous example of such a difference is the remainder term in the prime number theorem. Big O notation is also used in many other fields to provide similar estimates.<br/>
* * Growing a linked list<br/>
LinkedList is a linear data structure where each element is an object. Unlike Array, LinkedList is doesn't have a contiguous memory structure. Each element is linked to the next through a pointer.<br/>

---