# Definition
SOLID is an acronym for five key principles that guide programmers in writing cleaner, more maintainable, and scalable code. The meaning of each letter is:

- S — Single Responsiblity Principle 
- O — Open-Closed Principle 
- L — Liskov Substitution Principle 
- I — Interface Segregation Principle
- D — Dependency Inversion Principle 

# What it means and how to apply it daily at work

### 1. Single Responsibility Principle (SRP)
Meaning: A class should only focus on a single responsibility or functionality.

How to Apply:
- Break down large classes into smaller, focused ones.
- Ensure each class handles one specific task, such as managing data, interacting with a database, or implementing business logic.
- Regularly review code to identify classes doing too much and refactor them.

### 2. Open/Closed Principle (OCP)
Meaning: Code should be open for extension but closed for modification.
How to Apply:
- Use interfaces or abstract classes to define contracts that can be extended without altering the original code.
- Avoid hardcoding logic. Instead, rely on design patterns like the Strategy or Decorator pattern to add functionality.

### 3. Liskov Substitution Principle (LSP)
Meaning: Subclasses should be substitutable for their base classes without altering the behavior of the program.
How to Apply:
- Ensure subclasses don’t violate the behavior expected by the base class.
- Avoid overriding methods in a way that changes their original intent.
- Make sure that objects of a subclass can be used in place of the base class without causing any issues or unexpected behavior.

### 4. Interface Segregation Principle (ISP)
Meaning: A class should not be forced to implement interfaces it does not use.
How to Apply:
- Split large interfaces into smaller, more specific ones.
- Ensure that implementing classes are not burdened with methods they don’t need.
- Frequently review and refactor interfaces to maintain focus and clarity.

### 5. Dependency Inversion Principle (DIP)
Meaning: High-level modules should not depend on low-level modules; both should depend on abstractions.
How to Apply:
- Use dependency injection to provide the required dependencies to a class rather than instantiating them directly.
- Rely on abstractions (interfaces or abstract classes) instead of concrete implementations.
- Refactor tightly coupled code to introduce layers of abstraction for better flexibility.






