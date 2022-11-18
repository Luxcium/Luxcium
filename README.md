<div>
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Luxcium&layout=compact" alt="Top Langs">

<img align="right" width="50%" src="https://github-readme-stats.vercel.app/api?username=Luxcium&theme=transparent&show_icons=true&count_private=true&include_all_commits=true">  
</div>
<br>


# SOLID principles

Although they apply to any object-oriented design, the SOLID principles can 
also form a core philosophy for methodologies such as [agile development](https://en.wikipedia.org/wiki/Agile_software_development) or 
adaptive software development.

## Concepts

- [Single-responsibility principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)
A class should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.
 - [Open–closed principle](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle)
"Software entities ... should be open for extension, but closed for modification."
 - [Liskov substitution principle](https://en.wikipedia.org/wiki/Liskov_substitution_principle)
"Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.See also design by contract.
 - [Interface segregation principle](https://en.wikipedia.org/wiki/Interface_segregation_principle)
"Many client-specific interfaces are better than one general-purpose interface."
 - [Dependency inversion principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle)
One should "depend upon abstractions, [not] concretions.

### History

The theory of SOLID principles was introduced by 
[Robert C. Martin](https://en.wikipedia.org/wiki/Robert_C._Martin) (Uncle Bob)
in his 2000 paper Design Principles and Design Patterns. The SOLID acronym was introduced later by Michael Feathers.


###### From Wikipedia, the free encyclopedia ([source](https://en.wikipedia.org/wiki/SOLID)) ― [Used under license](https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License) ― Additional terms may apply.
 
 ----
 
 
 
# Design Patterns

**Design Patterns:** *Elements of Reusable Object-Oriented Software (1994)* is a software engineering book describing software design patterns. The book was written by Erich Gamma, Richard Helm, Ralph Johnson, and John Vlissides, with a foreword by Grady Booch.

It has been influential to the field of software engineering and is regarded as an important source for object-oriented design theory and practice. The authors are often referred to as the Gang of Four «GoF».
<!-- 

 - Creational Patterns

Object Creational: Abstract Factory
Object Creational: Builder
Class Creational: Factory Method
Object Creational: Prototype
Object Creational: Singleton

- Structural Patterns

Class, Object Structural: Adapter
Object Structural: Bridge
Object Structural: Composite
Object Structural: Decorator
Object Structural: Facade
Object Structural: Flyweight
Object Structural: Proxy

 - Behavioral Patterns

Object Behavioral: Chain of Responsibility
Object Behavioral: Command
Class Behavioral: Interpreter
Object Behavioral: Iterator
Object Behavioral: Mediator
Object Behavioral: Memento
Object Behavioral: Observer
Object Behavioral: State
Object Behavioral: Strategy
Class Behavioral: Template Method
Object Behavioral: Visitor

-->
## Creational

**Creational patterns are ones that create objects, rather than having to
instantiate objects directly. This gives the program more flexibility in
deciding which objects need to be created for a given case.**

 - 01. [Abstract factory ](https://en.wikipedia.org/wiki/Abstract_factory_pattern) **O** groups object factories that have a common theme.
 - 02. [Builder](https://en.wikipedia.org/wiki/Builder_pattern) **O** constructs complex objects by separating construction and
       representation.
 - 03. [Factory method](https://en.wikipedia.org/wiki/Factory_method_pattern) **C** creates objects without specifying the exact class
       to create.
 - 04. [Prototype](https://en.wikipedia.org/wiki/Prototype_pattern) **O** creates objects by cloning an existing object.
 - 05. [Singleton](https://en.wikipedia.org/wiki/Singleton_pattern) **O** restricts object creation for a class to only one instance.

## Structural

**These concern class and object composition. They use inheritance to compose
interfaces and define ways to compose objects to obtain new functionality.**

 - 06. [Adapter](https://en.wikipedia.org/wiki/Adapter_pattern) **C,O** allows classes with incompatible interfaces to work together by
      wrapping its own interface around that of an already existing class.
 - 07. [Bridge](https://en.wikipedia.org/wiki/Bridge_pattern) **O** decouples an abstraction from its implementation so that the two
       can vary independently.
 - 08. [Composite](https://en.wikipedia.org/wiki/Composite_pattern) **O** composes zero-or-more similar objects so that they can be
       manipulated as one object.
 - 09. [Decorator](https://en.wikipedia.org/wiki/Decorator_pattern) **O** dynamically adds/overrides behaviour in an existing method of
       an object.
 - 10. [Facade](https://en.wikipedia.org/wiki/Facade_pattern) **O** provides a simplified interface to a large body of code.
 - 11. [Flyweight](https://en.wikipedia.org/wiki/Flyweight_pattern) **O** reduces the cost of creating and manipulating a large number
       of similar objects.
 - 12. [Proxy](https://en.wikipedia.org/wiki/Proxy_pattern) **O** provides a placeholder for another object to control access,
       reduce cost, and reduce complexity.

## Behavioral

**Most of these design patterns are specifically concerned with communication
between objects.**

 - 13. [Chain of responsibility](https://en.wikipedia.org/wiki/Chain-of-responsibility_pattern) **O** delegates commands to a chain of processing
       objects.
 - 14. [Command](https://en.wikipedia.org/wiki/Command_pattern) **O** creates objects which encapsulate actions and parameters.
 - 15. [Interpreter](https://en.wikipedia.org/wiki/Interpreter_pattern) **C** implements a specialized language.
 - 16. [Iterator](https://en.wikipedia.org/wiki/Iterator_pattern) **O** accesses the elements of an object sequentially without
       exposing its underlying representation.
 - 17. [Mediator](https://en.wikipedia.org/wiki/Mediator_pattern) **O** allows loose coupling between classes by being the only class
       that has detailed knowledge of their methods.
 - 18. [Memento](https://en.wikipedia.org/wiki/Memento_pattern) **O** provides the ability to restore an object to its previous state
       (undo).
 - 19. [Observer](https://en.wikipedia.org/wiki/Observer_pattern) **O** is a publish/subscribe pattern which allows a number of
       observer objects to see an event.
 - 20. [State](https://en.wikipedia.org/wiki/State_pattern) **O** allows an object to alter its behavior when its internal
       state changes.
 - 21. [Strategy](https://en.wikipedia.org/wiki/Strategy_pattern) **O** allows one of a family of algorithms to be selected
       on-the-fly at runtime.
 - 22. [Template method](https://en.wikipedia.org/wiki/Template_method_pattern) **C** defines the skeleton of an algorithm as an abstract
       class, allowing its subclasses to provide concrete behavior.
 - 23. [Visitor](https://en.wikipedia.org/wiki/Visitor_pattern) **O** separates an algorithm from an object structure by moving
       the hierarchy of methods into one object.


###### From Wikipedia, the free encyclopedia ([source](https://en.wikipedia.org/wiki/Design_Patterns)) ― [Used under license](https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License) ― Additional terms may apply.
 
 ----

## ARCHIVED

###  \#100DaysOfCode

[![time tracker](https://wakatime.com/badge/github/Luxcium/100DaysOfCode.svg)](https://wakatime.com/badge/github/Luxcium/100DaysOfCode) [![Twitter Follow](https://img.shields.io/twitter/follow/Luxcium?label=Follow%20me&style=social)](https://twitter.com/Luxcium?ref_src=github001)


- Learn every day for 100 day.
- Code at least one hour per day.
- Teach someting online.
- Blog about code every day.
- Youtube something usefull for other to learn while doing their #100dayof code challenge.
- Reach to other doing the chalenge.
- Report my daily experience in a log on my github repository.
- Support other doing the chalenge

----
Scientia es lux principium✨™
