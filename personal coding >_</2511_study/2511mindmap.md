---
markmap:
  maxWidth: 300
---

 # root((Architectural Foundations))
 ### Core Design Principles
 ##### SOLID Principles
 ####### Single Responsibility :: SRP
 ####### Open/Closed :: OCP
 ####### Liskov Substitution :: LSP
 ####### Interface Segregation :: ISP
 ####### Dependency Inversion :: DIP
 ##### Law of Demeter
 ####### Least Knowledge
 ### Hallmarks of Good Design
 ##### High Cohesion
 ##### Loose Coupling
 ### Design Patterns
 ##### Creational
 ####### Factory Method
 ####### Abstract Factory
 ####### Builder
 ####### Singleton
 ##### Structural
 ####### Composite
 ####### Decorator
 ##### Behavioral
 ####### Strategy
 ####### Observer
 ### Refactoring & Quality
 ##### Refactoring methods 
 ###### Extract method: extract into seperate methods
 ###### Move method: move methods to class that use it the most
 ###### Replace Temp with Query: move temporary expressions into methods
 ####### Replace conditionals with polymorphism: Subclass inheritance, Strategy pattern
 ######### excessive switch cases violate OCP
 ####### Favour composition over inheritance
 ##### Refactoring Cycle
 ###### Identify Smell
 ###### Write Tests
 ###### Small Changes
 ##### Common Code Smells
 ###### Refused Bequest: subclass inherits inappropriate behaviour
 ###### Long Parameter List: create a data class and parse an instance of that class instead
 ###### Duplicated Code:
 1. Same code in multiple methods -> Extract method
 2. Same code in two subclasses of the same level -> Extract method into superclass
    - Pull up field: move up fields
    - Pull up method: move up methods
        - Inside constructor: use super constructor + parameterise fields 
        - Similar but not exact code: Template Method
         
 ###### Long Method/Class: Extract method/Extract class
 ###### Feature Envy
 ### Modern Paradigms
 ##### Functional Paradigm
 ####### Lambda Expressions
 ####### Functional Interfaces
 ####### Streams and Pipelines
 ##### Asynchronous Design
 ####### Independent Execution
 ####### Callbacks
 ####### Event-Driven :: Kafka