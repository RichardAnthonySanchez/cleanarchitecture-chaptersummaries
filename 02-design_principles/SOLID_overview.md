# What are the SOLID Principles?

- **Single Responsibility Principle (SRP)**
- **Open-Closed Principle (OCP)**
- **Liskov Substitution Principle (LSP)**
- **Interface Segregation Principle (ISP)**
- **Dependency Inversion Principle (DIP)**

## Single Responsibility Principle (SRP)

**Definition:**
A class should have only one reason to change, meaning it should have only one job or responsibility.

**Explanation:**
SRP aims to prevent unintended consequences when making changes to a component within the system. This is achieved by ensuring that each module within the system addresses one concern or responsibility. For example, in a business context, actors such as employees, managers, business owners, and customers each represent distinct responsibilities. By separating application logic in this way, we minimize the risk of unintentionally affecting other parts of the system.

## Open-Closed Principle (OCP)

**Definition:**
Software entities (classes, modules, functions, etc.) should be open for extension but closed for modification.

**Explanation:**
OCP strives to make architecture resilient to changes by allowing the extension of functionality without altering existing code. Adding new features is common, so we design systems in a way that accommodates new functionalities by adding new code, not modifying existing work. This approach avoids creating a domino effect of issues across the system due to modifications.

## Liskov Substitution Principle (LSP)

**Definition:**
Objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program.

**Explanation:**
LSP ensures that subclasses can stand in for their parent classes without causing errors or unexpected behavior. This means that any subclass should be able to substitute its superclass and function in the same way without alteration. For instance, if a subclass has similar properties to its parent, it should be handled in the same manner to ensure consistency and reliability.

## Interface Segregation Principle (ISP)

**Definition:**
No client should be forced to depend on methods it does not use.

**Explanation:**
ISP addresses the issue of classes implementing interfaces they do not need. This can lead to unexpected behavior when lower-level components receive unnecessary data from higher-level modules. By creating specific interfaces tailored to the needs of each client, we ensure that lower-level components receive only the data they require, promoting a more robust and maintainable system.

## Dependency Inversion Principle (DIP)

**Definition:**
High-level modules should not depend on low-level modules. Both should depend on abstractions. Abstractions should not depend on details. Details should depend on abstractions.

**Explanation:**
DIP suggests that high-level modules, which contain complex logic, should not depend on low-level details, which handle simple operations. Instead, both should rely on abstractions, reducing the dependency on concrete implementations. High-level components produce abstract data without dictating how it should be processed, allowing low-level components to handle the specifics, thereby promoting a more flexible and decoupled architecture.

## Why Do We Use These Principles?

These five principles guide us in designing software that is easier to read, maintain, and extend. By adhering to SOLID principles, we create systems that are robust, scalable, and resilient to change, facilitating long-term success and adaptability.