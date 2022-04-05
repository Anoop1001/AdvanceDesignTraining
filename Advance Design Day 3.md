## Testability
Benefits - Ease of testing. Easier, Simpler and Faster to test.

Improved manageability and supportability.

Enforces good design principles.

#### SOCK model

Simplicity,

Observbility,

Controllability,

Knowledge of Expected Results

What makes Testing difficult?

Dense dependencies -- Test Doubles to resolve - SEAM - is a place where you modify the behaviorwithout editing the place!
"new" Operator
Heavy constructor

Use Dependency Injection

Constructor initialization should be only for the members
Extract interface, Dependency injection, Dependency lookup, Constructor overloading

Law of demeter violation



OO Metrics
- LOC (Lines of code)
- NOC (No. of Classes)
- NOM (No. Of Methods)
- Depth inheritance Tree (DIT)
- NP (No. Of Paraeters)
- WMC ( Weighted method class)
- CC (Cohesion and Coupling)
- Fan-in / Fan-out
- NOF (No. of Fields)


- RFC (Response for Class)
- LCOM (Lack of cohesion of methods) - All the methods use all its instance fields
- CBO (Coupling between Object classes)

- Cyclomatic complexity

![image](https://user-images.githubusercontent.com/27200911/160979002-7aca909a-4e54-4245-a587-bbbe97b95874.png)

NDepend
Source Monitor
Designite

#### Craftsmanship (Metaphor)
 "making things work is the minimum expectation from someone who is paid for it."
 
 "How it is done is more important than getting it done"
 
 "A little extra work wonders"
 
 - Tech blogs and Katas

References :

- Clean code
- Working with legacy code(Robert C. Martin)
- Clean Coder : A code of conduct for professional programmers
- Refactoring to Patterns
- Refactoring (Martin Fowler)
- Object Oriented Analysis and Design with Applications, Grady booch.
- How google tests Software (Help me test like google)
- How we test software at Microsoft
- 31 days refactoring for C# and Java(Los Techies)

Extended 
## Design Principles

Design quality attributes,

1. Understandibility
2. Changeability
3. Extendebility
4. Reusability
5. Testability
6. Reliability

Design princinples by Grady Booch

PHAME - Abstraction, Encapsulation, Modularization, Hierarchy

## "Design as a Process" vs "Design as a Product"

High level design
Detailed Design

Artifacts
 Need to learn about aggregation
 
Cohesive means sigle responsibility.

Odors of rotting software
- Rigidity
- Fragility
- Immobility
- Viscosity (Software & Environment)
- Needless complexity
- Needless Repetition
- Opacity

- Premature abstraction

## SOLID Priinciples

#### Single Responsibility : 
 Modem example
#### Open Closed Principle(OCP) : 
 Shape example - Program to the what not on how. Strategy pattern by making loosely coupled. Inheritance when everything is required in child classes.
#### Liskov's substitution : 
 If it looks like a duck, quacks like a duck but needs battery then it is probably wrong abstraction. Throw not implemented exception is a vioation. square and rectangle. Logically implement all the methods from parent to child. Validity is not intrinsic - Behavior counts.
 Book and eBook example.
 is-a(Inheritance) vs has-a(Association)
#### Interface Segregation
Fat interfaces should be simplified. Animal example. Animal can't have bark, fly etc. 
[Example](https://www.codeproject.com/Articles/93369/How-I-explained-OOD-to-my-wife)
#### Dependency inversion
High level module should not depend on low level module. Should depend on abstractions.
Abstractions should not depend on details.
Example : Soldering wire to bulb instead of having an interface
Button/ Switch -> Button Server -> Fan/Lamp
Dependency injection(Aggregation with base reference) is dependent on Dependency inversion(Uses abstraction).
 
 
## Design Patterns
Every design pattern is based on SOLID principles.

#### Factory Method : 
Abstraction in some way(Not necessarily parent child) -> Implements Dependency inversion
#### Abstract factory :
Factories of factories : Family of classes. Example : Windows and Linux OS and widgets
Creational pattern only creates. Deletion we need to take care.
#### Observer pattern :
Subject [Update] - Observer [Update] - Concreteobserver [Update]




