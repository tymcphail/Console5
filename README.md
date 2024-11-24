# Computer Hardware Console Application
Program Focus
- Object-oriented design for managing computer hardware, specifically CPUs and laptops

Classes and Features

- CPU Class
  - Represents a CPU with properties like manufacturer, model, clock speed, socket type, and power draw
  - Includes validation to prevent invalid inputs
  - Overloaded constructors for flexible initialization
-Computer Abstract Class
  - Represents a general computer with a manufacturer and a CPU
  - Defines an abstract method CalcTDP() for calculating total power draw
- Laptop Class
  - Derived from Computer, represents laptops with an additional model property and a fixed TDP (thermal design power).
  - Overrides CalcTDP() to return the fixed TDP value.

Object-Oriented Techniques Used

- Encapsulation: Ensures proper data validation through property accessors
- Inheritance: The Laptop class extends the base Computer class
- Polymorphism: Overrides abstract methods for specific behavior in subclasses
- Purpose: Demonstrates object-oriented programming principles by modeling computer hardware, enabling reusability and efficient representation of CPUs and laptops












