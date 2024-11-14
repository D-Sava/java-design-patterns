# Java Design Patterns

This repository contains implementations of popular design patterns in Java. It serves as a resource for understanding and applying design patterns to create more efficient, reusable, and maintainable code. Each pattern includes an explanation of its purpose, structure, and a practical example to demonstrate its usage in real-world scenarios.

## Table of Contents
- [Overview](#overview)
- [Design Patterns](#design-patterns)
  - [Creational Patterns](#creational-patterns)
  - [Structural Patterns](#structural-patterns)
  - [Behavioral Patterns](#behavioral-patterns)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
Design patterns are best practices that help solve common software design challenges. This repository covers:
- **Creational Patterns**: Managing object creation.
- **Structural Patterns**: Organizing object structures and relationships.
- **Behavioral Patterns**: Defining how objects communicate and interact.

Each pattern includes:
- A brief explanation of the pattern's intent.
- UML diagram for structure visualization.
- Real-world examples in Java to clarify usage.

## Design Patterns

### Creational Patterns
- **Singleton**: Ensures only one instance of a class exists.
- **Factory Method**: Provides an interface for creating objects in a superclass.
- **Abstract Factory**: Creates families of related objects without specifying their concrete classes.
- **Builder**: Simplifies object construction with multiple attributes.
- **Prototype**: Creates new objects by copying existing ones.

### Structural Patterns
- **Adapter**: Converts an interface into another expected by the client.
- **Composite**: Composes objects into tree structures.
- **Decorator**: Adds new functionality to objects dynamically.
- **Facade**: Provides a simplified interface to complex subsystems.
- **Flyweight**: Reduces memory usage by sharing common object states.
- **Proxy**: Controls access to objects.

### Behavioral Patterns
- **Chain of Responsibility**: Passes requests along a chain of handlers.
- **Command**: Encapsulates requests as objects.
- **Iterator**: Provides a way to traverse elements in a collection.
- **Mediator**: Reduces dependencies between communicating objects.
- **Observer**: Establishes a subscription mechanism.
- **State**: Changes behavior when the internal state changes.
- **Strategy**: Defines a family of algorithms and makes them interchangeable.
- **Template Method**: Defines a skeleton of an algorithm.
- **Visitor**: Separates an algorithm from the objects it operates on.

## Directory Structure
```
java-design-patterns/
│
├── creational/
│   ├── Singleton.java
│   ├── FactoryMethod.java
│   └── Builder.java
│
├── structural/
│   ├── Adapter.java
│   ├── Composite.java
│   └── Decorator.java
│
├── behavioral/
│   ├── Observer.java
│   ├── Strategy.java
│   └── Command.java
│
└── README.md
```

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/java-design-patterns.git
   cd java-design-patterns
   ```

2. **Explore Each Pattern**:
   - Navigate to the folder for the desired pattern type (e.g., `creational/`, `structural/`, `behavioral/`).
   - Open the Java file to see the code and comments explaining each part of the pattern.

3. **Run the Examples**:
   - Compile and run each Java file independently to see how each pattern works.

## Contributing
Contributions are welcome! Feel free to submit pull requests if you’d like to add new design patterns, improve explanations, or enhance the examples.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Happy Coding and Learning!
