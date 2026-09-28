# Object-Oriented Design

## Learn
- Classes, constructors, encapsulation, interfaces, and composition.
- Inheritance and polymorphism; prefer composition when behavior varies independently.
- Immutability and defensive handling of mutable inputs.
- SOLID principles as tools for diagnosing coupling, not rules to apply mechanically.

## Practice
Model a booking or inventory domain with explicit invariants. Keep persistence and HTTP concerns out of domain rules.

## Ready when
Objects protect their invariants and responsibilities can be tested without starting a server.