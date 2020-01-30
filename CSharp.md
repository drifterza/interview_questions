## Interview Questions for C#

#### (Q1) What is an Object and a Class?

**Answer:**
``` 
A Class is an encapsulation of properties and methods that are used to represent a real-time entity. 
It is a data structure that brings all the instances together in a single unit.

An Object in an instance of a Class. Technically, it is just a block of memory allocated 
that can be stored in the form of Variables, Array or a Collection.
```
+ Score out of 2 : 

#### (Q2) What are the fundamental OOP concepts?

**Answer:**

The four fundamental concepts of Object Oriented Programming are:

```
Encapsulation – The Internal representation of an object is hidden from the view outside
object’s definition. Only the required information can be accessed whereas the rest of the data implementation is hidden.

Abstraction – It is a process of identifying the critical behavior and data of an object and eliminating the irrelevant details.

Inheritance – It is the ability to create new classes from another class. It is done by accessing, modifying and extending the behavior of objects in the parent class.

Polymorphism – The name means, one name, many forms. It is achieved by having multiple methods with the same name but different implementations
```
+ Score out of 4 : 

#### (Q3) What is Managed and Unmanaged code?

**Answer:**

```
Managed code is a code which is executed by CLR (Common Language Runtime) i.e all application code based on .Net Platform. It is considered as managed because of the .Net framework which internally uses the garbage collector to clear up the unused memory.

Unmanaged code is any code that is executed by application runtime of any other framework apart from .Net. The application runtime will take care of memory, security and other performance operations.
```
+ Score out of 2 : 


#### (Q4) What is an Interface?

**Answer:**

```
An Interface is a class with no implementation. The only thing that it contains is the declaration of methods, properties, and events.
```
+ Score out of 1 : 

#### (Q5) What are the different types of classes in C#?

**Answer**

The different types of class in C# are:

```
Partial class – Allows its members to be divided or shared with multiple .cs files. It is denoted by the keyword Partial.

Sealed class – It is a class which cannot be inherited. To access the members of a sealed class, we need to create the object of the class.  It is denoted by the keyword Sealed.

Abstract class – It is a class whose object cannot be instantiated. The class can only be inherited. It should contain at least one method.  It is denoted by the keyword abstract.

Static class – It is a class which does not allow inheritance. The members of the class are also static.  It is denoted by the keyword static. This keyword tells the compiler to check for any accidental instances of the static class.
```
+ Score out of 4 : 


#### (Q6) Explain Code compilation in C#.

**Answer:**

There are four steps in code compilation which include:

```
Compiling the source code into Managed code by C# compiler.

Combining the newly created code into assemblies.

Loading the Common Language Runtime(CLR).

Executing the assembly by CLR.
```
+ Score out of 4: 

#### (Q7) What is the difference between Virtual method and Abstract method?

**Answer:**

```
A Virtual method must always have a default implementation. However, it can be overridden in the derived class, though not mandatory. It can be overridden using override keyword.

An Abstract method does not have an implementation. It resides in the abstract class. It is mandatory that the derived class implements the abstract method. An override keyword is not necessary here though it can be used.
```
+ Score out of 2 : 

#### (Q8) Explain Namespaces in C#.

**Answer:**

```
They are used to organize large code projects. “System” is the most widely used namespace in C#. We can create our own namespace and use one namespace in another, which are called Nested Namespaces.
```
+ Score out of 1 :

#### (Q9) How is Exception Handling implemented in C#?

**Answer:**

Exception handling is done using four keywords in C#:

```
try – Contains a block of code for which an exception will be checked.
catch – It is a program that catches an exception with the help of exception handler.
finally – It is a block of code written to execute regardless whether an exception is caught or not.
Throw – Throws an exception when a problem occurs.
```
+ Score out of 4: 

#### (Q10) What is the difference between Continue and Break Statement?

**Answer:**

```
Break statement breaks the loop. It makes the control of the program to exit the loop.

Continue statement makes the control of the program to exit only the current iteration. It does not break the loop.
```
+ Score out of 2:

#### Q #11) What is an Escape Sequence? 

Name some String escape sequences in C#.

**Answer:**

```
An Escape sequence is denoted by a backslash (\). The backslash indicates that the character that follows it should be interpreted literally or it is a special character. An escape sequence is considered as a single character.

String escape sequences are as follows:

\n – Newline character
\b – Backspace
\\ – Backslash
\’ – Single quote
\’’ – Double Quote
```
+ Score out of 5: 
___
+ Total Scores: 30 + 1 bonus
