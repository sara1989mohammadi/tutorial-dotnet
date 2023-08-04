# tutorial-dotnet
**Q #1) What is C#?**

**Answer:** C# is a computer programming language. Microsoft developed C# in 2000 to provide a modern general-purpose programming language that can be used to develop all kinds of software targeting various platforms, including Windows, Web, and Mobile, using just one programming language. Today, C# is one of the most popular programming languages in the world. Millions of software developers use C# to build all kinds of software. 
C# is the primary language for building Microsoft .NET software applications. Developers can build almost every kind of software using C#, including Windows UI apps, console apps, backend services, cloud APIs, Web services, controls and libraries, serverless applications, Web applications, native iOS and Android apps, AI and machine learning software, and blockchain applications.
C# provides rapid application development with the help of Visual Studio IDE. C# is a modern, object-oriented, simple, versatile, and performance-oriented programming language. C# is developed based on the best features and use cases of several programming languages, including C++, Java, Pascal, and SmallTalk. 
C# syntaxes are like C++. .NET, and the C# library is similar to Java. C# supports modern object-oriented programming language features, including Abstraction, Encapsulation, Polymorphism, and Inheritance. C# is a strongly typed language. Most of the types in .NET are inherited from the Object class.
C# supports concepts of classes and objects. Classes have members such as fields, properties, events, and methods.

**Q #2) What is the latest version of C#?**

**Answer:** Since its inception, C# language has gone through various upgrades. The latest version of C# is C# 11.

**Q #3) What is an object in C#?**

**Answer:** C# language is an object-oriented programming language. Classes are the foundation of C#. A class is a template that defines a data structure and how data will be stored, managed, and transferred. A class has fields, properties, methods, and other members.
While classes are concepts, objects are real. Objects are created using class instances. A class defines the type of an object. Objects store real values in computer memory.
Any real-world entity with certain characteristics or that can perform some work is called an Object. This object is also called an instance, i.e., a copy of an entity in a programming language. Objects are instances of classes.

**Q #4) What is a class in C#?**

**Answer:** In C#, a class is a user-defined blueprint from which objects are created. It brings various types of data together to form a single unit. 


**Q #5) What are the fundamental OOP concepts?**

**Answer:** The four fundamental concepts of Object-Oriented Programming are:

**Encapsulation:** Here, the internal representation of an object is hidden from the view outside the object’s definition. Only the required information can be accessed whereas the rest of the data implementation is hidden.

**Abstraction:** It is a process of identifying the critical behavior and data of an object and eliminating irrelevant details.

**Inheritance:** It is the ability to create new classes from another class. It is done by accessing, modifying, and extending the behavior of objects in the parent class.

**Polymorphism:** The name means one name, many forms. It is achieved by having multiple methods with the same name but different implementations.


**Q #6) What are Properties in C#?**

**Answer:** Properties are the special type of class members that provides a flexible mechanism to read, write, or compute the value of a private field. Properties can be used as if they are public data members, but they are actually special methods called accessors. This enables data to be accessed easily and helps to promote the flexibility and safety of methods. Encapsulation and hiding of information can also be achieved using properties. It uses pre-defined methods which are “get” and “set” methods which help to access and modify the properties.

**Accessors:** The block of “set” and “get” is known as “Accessors”. It is very essential to restrict the accessibility of the property. There are two types of accessors i.e. get accessors and set accessors. There are different types of properties based on the “get” and set accessors:

 Read and Write Properties: When the property contains both get and set methods.
 
 Read-Only Properties: When the property contains only the get method.
 
 Write Only Properties: When the property contains only a set method.
 
 Auto-Implemented Properties: When there is no additional logic in the property accessors, it introduces in C# 3.0. 

**Q #7) Explain Namespaces in C#.**

**Answer:** They are used to organize large code projects. “System” is the most widely used namespace in C#. We can create our own namespace and can also use one namespace in another, which is called Nested Namespaces.

They are denoted by the keyword “namespace”.

**Q #8) Explain Polymorphism?**

**Answer:** Programmatically, Polymorphism means the same method but different implementations. It is of 2 types, Compile-time and Runtime.

Compile-time polymorphism is achieved by operator overloading.
Runtime polymorphism is achieved by overriding. Inheritance and Virtual functions are used during Runtime polymorphism.

**Q #9) What is the difference between “continue” and “break” statements in C#?**

**Answer:** Using a break statement, you can 'jump out of a loop,' whereas using a continue statement, you can 'jump over one iteration' and resume your loop execution.

**Q #10) What is the difference between constant and read-only in C#?**

**Answer:** Const is nothing but "constant," a variable whose value is constant but at compile time. Therefore, it's mandatory to assign a value to it. By default, a const is static, and we cannot change the value of a const variable throughout the entire program.

Readonly is the keyword whose value we can change during runtime or assign it at run time but only through the non-static constructor.

//////////////////////////////////////////////////
 C#
Sdk
Clr
Bcl
.net compiler platform
.net framwork
.net core
.net
.net standard 
Assembly
Name space
Nuget 
.net call
Constants
Nulable types
Data type
Floot , boolean , char, object, string,If, else, switsch case ,loops , name space, comments Class,fields,properties,methods,cunstructors,local func
Extention method Annonymos type
Records Structs Enum Ref , in ,out Tuples Partial types Inheritant Virtual method Abstract
Sealds
Constructors
Modifiers
Inheritanc with record
Interface
Class with interface
Default interface meth
Generic 
What is meant by object-oriented programming?
Sample answer:Object-oriented programming (OOP) is an approach to programming where software is primarily designed by using objects (essentially data) that interact with each other. 
When different pieces of data are put together, they come to form the software as a whole. OOP is an alternative to functional or procedural programming and it’s also the approach used by C#.
What is an object in C#?
Sample answer:
An object is a real-world entity; in C# it’s a single class instance. For example, if you had a class of ‘dogs’, ‘labradors’, ‘bulldogs’, and ‘golden retrievers’ would all be objects. 
6. What is a class in C#?
Sample answer:
In C#, a class is a user-defined blueprint from which objects are created. It brings various types of data together to form a single unit. 
16. What are Properties in C#?
Properties are the special type of class members that provides a flexible mechanism to read, write, or compute the value of a private field. Properties can be used as if they are public data members, but they are actually special methods called accessors. This enables data to be accessed easily and helps to promote the flexibility and safety of methods. Encapsulation and hiding of information can also be achieved using properties. It uses pre-defined methods which are “get” and “set” methods which help to access and modify the properties.
Accessors: The block of “set” and “get” is known as “Accessors”. It is very essential to restrict the accessibility of the property. There are two types of accessors i.e. get accessors and set accessors. There are different types of properties based on the “get” and set accessors:
Read and Write Properties: When property contains both get and set methods.
Read-Only Properties: When property contains only the get method.
Write Only Properties: When property contains only set method.
Auto Implemented Properties: When there is no additional logic in the property accessors, and it introduces in C# 3.0. 


7. What is a method in C#?
Sample answer:
In C#, a method is a code block that contains a series of statements used to perform particular operations. Methods must be declared within a class or a structure. They help save time by reusing code. 
 
How would you explain the four fundamental concepts of object-oriented programming? 
Sample answer:
The four fundamental concepts of object-oriented programming can be explained as follows:
Encapsulation is the bundling of data, including the methods that operate on that data, into a single, private unit
Polymorphism is the ability of a type to take on many forms using a single interface
Abstraction is the concealment of unnecessary program details so that the user only sees the essential attributes
Inheritance is the process where one class derives (or inherits) its attributes and methods from another
 
What are the different types of classes in C#?
Abstract classes: These provide a common definition for a base class that other classes can be derived from
Static classes: These contain static items that can only interact with other static items
Partial classes: These are portions of a class that a compiler can combine to form a complete class
Sealed classes: These cannot be inherited by any class but can be instantiated
 17. What are partial classes in C#?
A partial class is a special feature of C#. It provides a special ability to implement the functionality of a single class into multiple files and all these files are combined into a single class file when the application is compiled. A partial class is created by using a partial keyword. This keyword is also useful to split the functionality of methods, interfaces, or structure into multiple files.


What is the difference between ref and out keywords in C#?
Sample answer:
The <ref> and <out> keywords are similar in that they are both used to pass arguments in a reference or function. However, there is a subtle difference:
With <ref> keywords, the value is already set, meaning the method can read and modify it
With <out> keywords, the value isn’t set and can’t be read by the method until it is set, meaning the method must set it before it can be returned
 14. What is the difference between ref and out keywords?
The ref is a keyword in C# which is used for passing the arguments by a reference. Or we can say that if any changes made in this argument in the method will reflect in that variable when the control return to the calling method. The ref parameter does not pass the property.
The out is a keyword in C# which is used for passing the arguments to methods as a reference type. It is generally used when a method returns multiple values. The out parameter does not pass the property. 


 
What are the advantages of generics in C#?
Sample answer:
In C#, generics allow the developer to define classes and methods which can be used with any data type. This brings several benefits:
Saves time by reusing code
Provides type safety without unnecessary overhead
Removes the need for boxing and unboxing
Generic collection types generally perform better with value types because there is no need to box the values
 
When is method overriding used in C#?
Sample answer:
In C#, method overriding is used to invoke functions that belong to different classes. This process creates a method in the derived class with the same signature as a method in the base class without modifying the code of the base class. This helps achieve runtime polymorphism
What is the difference between Const and ReadOnly keywords in C#?
Sample answer:
There are several differences between Const and ReadOnly keywords in C#. These include:
ReadOnly is a constant used at runtime, whereas Const is a constant used at compile-time
ReadOnly values can be changed, whereas Const values cannot be changed
ReadOnly cannot be declared inside the method, whereas Const can
 
What is meant by dependency injection in C#?
Sample answer:
In C#, dependency injection (DI) is a design pattern used to develop loosely coupled code. This process moves the creation and binding of dependent objects outside of the class that depends on them. The main purpose of this is to make future changes to code more manageable. 
How is exception handling performed in C#?
Sample answer:
In C#, exception handling helps detect errors in code at runtime. The process is implemented using four different keywords:
1.	<Try> identifies blocks of code where exceptions are activated
2.	<Catch> catches the exceptions that have been identified by <Try>
3.	<Finally> executes a given set of statements depending on whether an exception is thrown out or not
4.	<Throw> removes the exception
32. Describe Accessibility Modifiers in C#?
Access Modifiers are keywords that define the accessibility of a member, class, or datatype in a program. These are mainly used to restrict unwanted data manipulation by external programs or classes. There are 4 access modifiers (public, protected, internal, private) which defines the 6 accessibility levels as follows:
public
private
private protected
protected
internal
protected internal


What are Access Modifiers in C#?
Access Modifiers are basically used to control the accessibility of types and members with in the types. In C# there are 5 different types of Access Modifiers.
1. Public: Public is the most common access specifier in C#. It can be accessed from anywhere, that means there is no restriction on accessibility. It is accessible to all classes & projects.
2. Private: The range of the accessibility is limited only within the classes or struct in which they are declared.
3. Protected: All members in the current class & in derived classes can access the variables.
4. Internal: The type or member can be accessed by any code in the same assembly, but not from another assembly.
5. Protected Internal: The protected internal access specifier allows a class to hide its member functions & member variables from other class objects and functions, except a child class within the same application. This is also used while implementing inheritance.
Explain is an interface class?
Interface class is an abstract class that has only public abstract methods & the methods only have the declaration and not the definition. These abstract methods must be implemented in the inherited classes.
Explain Abstract class?
We create an abstract class when we define a template that needs to be followed by all the derived classes. Abstract class can have an implementation which should be implemented in the child class.

What are generics in C#.NET?
Generics are used to make reusable code classes to decrease the code redundancy, increase type safety and performance. Using generics, we can create a collection of classes. To create a generic collection, System.Collections.Generic namespace should be used.
What is Hashtable in C#?
A Hashtable is a collection of key-value pairs. It contains values based on the key.
What is the purpose of async/await keywords?
These keywords allow writing asynchronous non-blocking code in a synchronous fashion.
This feature is facilitated by the Task/Task<T> classes or ValueTask/ValueTask<T> structs. These types represent an abstraction around an operation that may execute asynchronously.


9. What are extension methods in C#?
In C#, the extension method concept allows you to add new methods in the existing class or in the structure without modifying the source code of the original type, and you do not require any kind of special permission from the original type and there is no need to re-compile the original type. It is introduced in C# 3.0. 
10. What is inheritance? Does C# support multiple inheritance?
Inheritance is an important pillar of OOP(Object Oriented Programming). It is the mechanism in C# by which one class is allowed to inherit the features(fields and methods) of another class.
Super Class: The class whose features are inherited is known as superclass(or a base class or a parent class).
Sub Class: The class that inherits the other class is known as a subclass(or a derived class, extended class, or child class). The subclass can add its own fields and methods in addition to the superclass fields and methods.
Reusability: Inheritance supports the concept of “reusability”, i.e. when we want to create a new class and there is already a class that includes some of the code that we want, we can derive our new class from the existing class. By doing this, we are reusing the fields and methods of the existing class.
C# does not support multiple class inheritance. 


12. What is the difference between a struct and a class in C#? 
A class is a user-defined blueprint or prototype from which objects are created. Basically, a class combines the fields and methods(member function which defines actions) into a single unit.
A structure is a collection of variables of different data types under a single unit. It is almost similar to a class because both are user-defined data types and both hold a bunch of different data types. 
13. What is enum in C#? 
Enumeration (or enum) is a value data type in C#. It is mainly used to assign the names or string values to integral constants, which make a program easy to read and maintain. For example, the 4 suits in a deck of playing cards may be 4 enumerators named Club, Diamond, Heart, and Spade, belonging to an enumerated type named Suit. Other examples include natural enumerated types (like the planets, days of the week, colors, directions, etc.). The main objective of enum is to define our own data types(Enumerated Data Types). Enumeration is declared using the enum keyword directly inside a namespace, class, or structure. 
19. What are the different ways in which a method can be Overloaded in C#?
Method Overloading is the common way of implementing polymorphism. It is the ability to redefine a function in more than one form. A user can implement function overloading by defining two or more functions in a class sharing the same name. C# can distinguish the methods with different method signatures. i.e. the methods can have the same name but with different parameters list (i.e. the number of the parameters, order of the parameters, and data types of the parameters) within the same class.
Overloaded methods are differentiated based on the number and type of the parameters passed as arguments to the methods.
You can not define more than one method with the same name, Order, and type of the arguments. It would be a compiler error.
The compiler does not consider the return type while differentiating the overloaded method. But you cannot declare two methods with the same signature and different return types. It will throw a compile-time error. If both methods have the same parameter types, but different return types, then it is not possible.
21. What is the difference between constant and read-only in C#?
In C#, a const keyword is used to declare constant fields and constant local. The value of the constant field is the same throughout the program or in other words, once the constant field is assigned the value of this field is not be changed. In C#, constant fields and locals are not variables, a constant is a number, string, null reference, boolean values. readonly keyword is used to declare a readonly variable. This readonly keyword shows that you can assign the variable only when you declare a variable or in a constructor of the same class in which it is declared. 
33. What is a Virtual Method in C#?
In C# virtual method is a strategy that can be reclassified in derived classes. We can implement the virtual method in the base class and derived class. It is utilized when a method’s fundamental work is similar but in some cases derived class needed additional functionalities. A virtual method is declared in the parent class that can be overridden in the child class. We make a virtual method in the base class by using the virtual keyword and that method is overridden in the derived class using the Override keyword.  It is not necessary for every derived class to inherit a virtual method, but a virtual method must be created in the base class. Hence the virtual method is also known as Polymorphism.




 
 




