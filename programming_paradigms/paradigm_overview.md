# Programming Paradigms

Programming paradigms are different approaches you can use to write code. They are like different tools. Each tool can solve their own unique problems. All attempt to improve maintenance, debugging, and readability.

## Structured Programming

Structured programming emphasizes clear and modular code. It is organized into logically structured blocks, in the form of, loops, conditionals, and functions.

## Object-Oriented Programming

Object-oriented programming allows for the creation of independent modules. These module objects can prevent important parts of the system from becoming dependent on volitile parts. 

## Functional Programming

Functional Programming emphasizes writing code that is easy to reason about. Ideally, it creates an environment where code is less prone to side effects.

For further clarification:
- Side effects: These are unexpected modifications of data, often resulting from mutable data.
- Immutable variables: These are data that doesn't change, typically used as private, encapsulated data.
- Pure Functions have the following characteristics:
  1. No side effects
  2. Referential Transparency: Program behavior doesn't change when using a result instead of calling a function.
  3. Determinism: The same inputs produce the same output.
  4. They don't modify state.