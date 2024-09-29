# Design Patterns
Important Design Patterns For Interview Preparation
- [Four Pillars of OOPS](#four-pillars-of-oops)
- [SOLID Principles](#solid-principles)
- [Creational Pattern](#creational-pattern)
- [Behavioural Pattern](#behavioural-pattern)
- [Structural Pattern](#structural-pattern)

## Four Pillars of OOPS
The four pillars of OOPS (object-oriented programming) are
- [Inheritance](#1-inheritance)
- [Polymorphism](#2-polymorphism)
- [Encapsulation](#3-encapsulation)
- [Abstraction](#4-abstraction)

### 1. Inheritance
Inheritance is the process of one class inheriting properties and methods from another class. Inheritance is used when we have is-a relationship between objects.

### 2. Polymorphism
Polymorphism is the ability to perform many things in many ways. The word Polymorphism is from two different Greek words- poly and morphs. “Poly” means many, and “Morphs” means forms. So polymorphism means many forms. The polymorphism can be present in the case of inheritance also. The functions behave differently based on the actual implementation.

### 3. Encapsulation
Encapsulation is the process of wrapping code and data together into a single unit. encapsulation is achieved by declaring the instance variables of a class as private, which means they can only be accessed within the class. To allow outside access to the instance variables, public methods called getters and setters are defined, which are used to retrieve and modify the values of the instance variables, respectively

### 4. Abstraction
Abstraction is a process of hiding implemetation details and exposing only the functionality to the user. This means the user will only know "What it does" rather then "How it does".

## SOLID Principles
SOLID Principles are 5 basic principles which helpes to create good software architecture.

- [Single Responsibility Principle](#1-single-responsibility-principle)
- [Open Closed Principle](#2-open-closed-principle)
- [Liskov Substitution Principle](#3-liskov-substitution-principle)
- [Interface Segregation Principle](#4-interface-segregation-principle)
- [Dependency Inversion Principle](#5-dependency-inversion-principle)

### 1. Single Responsibility Principle
A class should have only one responsibility and not many.

### 2. Open Closed Principle
Keep the class open for extension (Inheritance). Close the class for modification.

### 3. Liskov Substitution Principle
Parent class types should easily be able to replace child objects.
```
Eg: Class Shape, Class Square : Shape, Class Rectangle : Shape
Shape s = new Rectangle();
Shape s = new Square();
```
Here we can substitute the object of Square or Rectangle to its parent class Shape.

### 4. Interface Segregation Principle
Clients should not be foreced to implement interfaces they do not use. Instead, interfaces should be broken down into smaller, more specific interfaces to prevent clents from being dependent on methods that are irrelevant to thier needs. Don't add methods to existing Interface that the client don't need. Instead create new interface by extending existing interfaces.

### 5. Dependency Inversion Principle
High level modules should not depend on low level modules. Both should depend on abstractions. Abstractions should not depend on details. Basically, Implement loosely coupled class architecture over concrete class.

## Creational Pattern
Creational Design Patterns deals with object creation mechanism.
- [Singleton Design Pattern](#1-singleton-design-pattern)
- [Factory Design Pattern](#2-factory-design-pattern)
- [Abstract Design Pattern](#3-abstract-design-pattern)
- [Builder Design Pattern](#4-builder-design-pattern)
- [Prototype Design Pattern](#5-prototype-design-pattern)

### 1. Singleton Design Pattern

### 2. Factory Design Pattern

### 3. Abstract Design Pattern

### 4. Builder Design Pattern

### 5. Prototype Design Pattern

## Behavioural Pattern
Behavioural Design Patterns deals with the communication of interaction between classes and objects.
- [Chain of Responsibility Design Pattern](#1-chain-of-responsibility-design-pattern)
- [Command Design Pattern](#2-command-design-pattern)
- [Interpreter Design Pattern](#3-interpreter-design-pattern)
- [Iterator Design Pattern](#4-iterator-design-pattern)
- [Mediator Design Pattern](#5-mediator-design-pattern)
- [Memento Design Pattern](#6-memento-design-pattern)
- [Observer Design Pattern](#7-observer-design-pattern)
- [State Design Pattern](#8-state-design-pattern)
- [Stratergy Design Pattern](#9-stratergy-design-pattern)
- [Template Design Pattern](#10-template-design-pattern)
- [Visitor Design Pattern](#11-visitor-design-pattern)

### 1. Chain of Responsibility Design Pattern

### 2. Command Design Pattern

### 3. Interpreter Design Pattern

### 4. Iterator Design Pattern

### 5. Mediator Design Pattern

### 6. Memento Design Pattern

### 7. Observer Design Pattern

### 8. State Design Pattern

### 9. Stratergy Design Pattern

### 10. Template Design Pattern

### 11. Visitor Design Pattern

## Structural Pattern
Structural design patterns are a group of design patterns that deal with how to arrange classes and objects to achieve specific design goals.
- [Adapter Design Pattern](#1-adapter-design-pattern)
- [Bridge Design Pattern](#2-bridge-design-pattern)
- [Composite Design Pattern](#3-composite-design-pattern)
- [Decorator Design Pattern](#4-decorator-design-pattern)
- [Facade Design Pattern](#5-facade-design-pattern)
- [Flyweight Design Pattern](#6-flyweight-design-pattern)
- [Proxy Design Pattern](#7-proxy-design-pattern)

### 1. Adapter Design Pattern

### 2. Bridge Design Pattern

### 3. Composite Design Pattern

### 4. Decorator Design Pattern

### 5. Facade Design Pattern

### 6. Flyweight Design Pattern

### 7. Proxy Design Pattern
