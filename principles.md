## Principles of Object Oriented Programming

Th four major principles of OOP are:

**Encapsulation**

**Data Abstraction**

**Polymorphism**

**Inheritance**


### Encapsulation

Encapsulation is the hiding of data implementation by restricting access to accessors and mutators.
Basically the internal representation/ properties is hidden from view outside of the object's definition. Only the Object's own method can access and manipulate its fields.

Accessor
An accessor is a method used to ask an object about itself. They are ussually in form of properties, eg, the get() method

Mutator
It is a public method that is used to modify/manipulate the state of an object, while hiding the implememntation of exactly how the data gets modified. e.g the Set() method lets the caller modify the member data behind the scenes.



### Abstraction

Abstraction is the development of classes, objects, types in terms of their interfaces and functionality, instead of their implementation details. 

It denotes a model, a view, or some other focused representation for an actual item. They hide the details of their implementation
Data abstraction is closely tied together with encapsulation. 


### Polymorphism

Polymorphism means one name, many forms. It manifests itself by having multiple methods all with the same name, but slightly different functionality.

2 basics of polymorphism
Overriding
Also known as run-time polymorphism . For method overloading, the compiler determines which method will be executed, and this decision is made when the code gets compiled.

Overloading,
Known to as compile-time polymorphism. Method will be used for method overring is determined at runtime based on the dynamic type of an object.
 



### Inheritance

This is reusing code of existing objects, or establishing a subtype from an existing object,or both depending upon programming language support. 
Classical Ineritance-classescan inherit attributes and bejaviour from pre-existing  classes called base classes, superclass, parent class or ancestor classes. 

The resulting/inheriting classes are known as derived classes, subclasses or child classes. this gives a hierarchy relationship.
properties inheritd include data variables, methods and functions
