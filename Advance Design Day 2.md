## Principles of modularization

- Decompose abstractionto manageable size
- Localize related data and methods
- Create acyclic dependencies
- Limit dependencies

Broken modularization
Insufficient modularization
Cyclically dependent modularization
Hub like modularization

Hierarchy smells

Apply Meaningful classification
Apply Meaningful classification
Ensure Substitutability(Liskovs Substitute Principle) -- Dog --> HasLegs() <-- Chair
Avoid redundant paths
Ensure proper ordering


Broken Hierarchy (Reversing parent child)
Rebellious hierarchy --> throwing not implemented exception in child class(LSP violation)
Unnecessary Hierarchy
Missing Hierarchy

Refactoring for Software Design Smells (Book by Siemens Author)
Behavior-preserving program restructuring
When to refactor, when a method keep on touched frequently

Rename
Method refactoring
Split temporary variable refactoring.
Decompose conditional refactoring
Introduce explaining variable(Discount example).
Consolidate duplicate conditional fragments.
Parameterized method refactoring(Angle example in parameter)
Move method refactoring
Extract class method refactoring
Pull up method field refactoring
Push down method field refactoring

https://refactoring.com/catalog/

2 mins to better code
Remove the 3 C's
- Clutter
- Complexity (Remove magic numbers)
- Cleverness

[Prefer composition over inheritance](https://stackoverflow.com/a/49016/7198636)

## Refactor to patterns

Pattern --> Expresses relationshit between Context - Probelm - Solution

Patterns are generic solutions to recurring design problems.

Learn observer pattern.


