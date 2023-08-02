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
