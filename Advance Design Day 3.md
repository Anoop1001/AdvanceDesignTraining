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
