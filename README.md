# Design Patterns Implementation

This repository contains an implementation of various design patterns in TypeScript. Each design pattern is implemented as a separate console application, demonstrating its usage and benefits.

## Design Patterns Implemented

The following design patterns are included in this repository:

- Abstract Factory: Provides an interface for creating families of related or dependent objects without specifying their concrete classes.
- Adapter: Converts the interface of a class into another interface that clients expect, allowing classes with incompatible interfaces to work together.
- Bridge: Decouples an abstraction from its implementation, allowing both to vary independently.
- Builder: Separates the construction of a complex object from its representation, enabling the same construction process to create different representations.
- Chain of Responsibility: Allows an object to pass a request along a chain of potential handlers until the request is handled or reaches the end of the chain.
- Command: Encapsulates a request as an object, enabling parameterization of clients with different requests, queues, or log requests, and supporting undoable operations.
- Composite: Composes objects into tree structures to represent part-whole hierarchies, treating individual objects and compositions uniformly.
- Decorator: Dynamically adds responsibilities to an object by wrapping it with one or more decorator objects, providing a flexible alternative to subclassing for extending functionality.
- Facade: Provides a simplified interface to a complex subsystem, making it easier to use and reducing dependencies between subsystems and clients.
- Factory Method: Defines an interface for creating objects, but allows subclasses to decide which class to instantiate.
- Flyweight: Shares common state between multiple objects, reducing memory consumption for large numbers of similar objects.
- Iterator: Provides a way to access elements of an aggregate object sequentially without exposing its underlying representation.
- Mediator: Defines an object that encapsulates how a set of objects interact, promoting loose coupling by keeping objects from referring to each other explicitly.
- Memento: Captures and restores an object's internal state, allowing objects to return to a previous state without revealing the details of its implementation.
- Observer: Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
- Prototype: Creates new objects by cloning existing ones, allowing the creation of new objects without coupling to their specific classes.
- Proxy: Provides a surrogate or placeholder for another object to control access to it or add additional functionality.
- Singleton: Ensures that a class has only one instance and provides a global point of access to it.
- State: Allows an object to alter its behavior when its internal state changes, resulting in different object behavior for different states.
- Strategy: Defines a family of algorithms, encapsulates each one, and makes them interchangeable, allowing the algorithm to vary independently from clients.
- Template Method: Defines the skeleton of an algorithm in a method, deferring some steps to subclasses, enabling subclasses to redefine certain steps without changing the algorithm's structure.
- Visitor: Separates an algorithm from the object structure it operates on, allowing new operations to be added to existing object structures without modifying those structures.

## Requirements

To run the examples, make sure you have the following installed on your computer:

- [Node.js](https://nodejs.org/en/) and npm (Node Package Manager)
- TypeScript compiler: Install it globally by running `npm install -g typescript`.
- TypeScript Node extension: Install it globally by running `npm install -g ts-node`.

## Usage

1. Clone this repository to your local machine or download it as a ZIP file and extract it.
2. Navigate to the specific design pattern's directory you want to run (e.g., `cd Bridge`).
3. Install the required dependencies by running `npm install`.
4. Run the example by executing `npm start`.

Each design pattern implementation includes

 a README file with additional details and explanations specific to that pattern.

Feel free to explore the implementations and learn more about each design pattern in action!
