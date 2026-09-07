# Java — Concepts & Practice

> A growing collection of Java programs covering programming fundamentals, object-oriented programming, collections, exceptions, interfaces, and core language features.

<p align="center">
  <img src="https://skillicons.dev/icons?i=java" alt="Java" />
</p>

---

## The learning path

This repository is organised around **concepts rather than projects**. The programs move from basic Java syntax into the object-oriented features that make up the core of the language.

```text
JAVA
 │
 ├── Fundamentals
 │     ├── Hello World
 │     ├── Arithmetic
 │     └── User Input
 │
 ├── Object-Oriented Programming
 │     ├── Classes & Objects
 │     ├── Constructors
 │     ├── Encapsulation
 │     ├── Inheritance
 │     ├── Abstract Classes
 │     └── Interfaces
 │
 ├── Language Features
 │     ├── Wrapper Classes
 │     ├── Collections
 │     ├── Exceptions
 │     └── Threads
 │
 └── Practice
       └── Small concept-focused programs
```

---

## From syntax to objects

### First Java Project

The repository starts with small programs covering the basic Java workflow: a `HelloWorld` program, arithmetic operations, user input, scanning values, and introductory classes such as `Student` and `Car`. The arithmetic example demonstrates direct use of Java variables and operators. citeturn232file0

**Focus:** syntax · variables · operators · input · classes · objects

---

## Object-oriented Java

The OOP sections form the core of the repository.

### Encapsulation

The `Encapsulation` folder contains `Employee` and `Student` examples, providing practice with keeping object data and behaviour together.

### Inheritance

The `Inheritance` folder explores class relationships through a base `A` class and derived `B` / single-inheritance examples.

```text
        A
        │
        ▼
        B
```

### Abstract Classes

The `Abstract Class` section uses an abstract `Shape` with an abstract `area()` method, with concrete `Circle` and `Rectangle` implementations providing the specific behaviour. citeturn233file0

```text
             Shape
          abstract area()
              │
        ┌─────┴─────┐
        ▼           ▼
      Circle     Rectangle
```

### Interfaces

The `Interfaces` section demonstrates multiple-interface implementation through a `Samsung` class implementing both `Radio` and `Camera`, including station and image operations. citeturn230file0

This gives the repository a useful progression:

`class → inheritance → abstraction → interfaces`

---

## Handling the unexpected

The `Exception Handling` section demonstrates Java's `try` / `catch` mechanism by handling an arithmetic exception and allowing the program to continue cleanly. citeturn231file0

```text
try
 │
 ├── operation succeeds → continue
 │
 └── exception occurs
          │
          ▼
       catch(...)
          │
          ▼
       handle it
```

---

## Other concepts

The repository also contains focused examples for:

| Area | Practice |
|---|---|
| **Constructors** | Creating and initialising objects |
| **Wrapper Classes** | Working with Java's primitive-wrapper types |
| **User Input** | Reading values from the user |
| **Collections** | Core collection-based programming exercises |
| **Threads** | Introductory multithreading concepts |
| **Lambda Expressions** | Functional-style Java syntax |
| **Math** | Java's mathematical utilities |
| **Nested Classes** | Classes defined within other classes |

---

## Repository map

```text
java/
├── First Java Project/
├── constructor/
├── Encapsulation/
├── Inheritance/
├── Abstract Class/
├── Interfaces/
├── Exception Handling/
├── Wrapper Classes/
├── User Input/
└── ...
```

The original folder names and source files are preserved so the repository continues to work as a practical learning archive.

---

## Core concepts

`Java` · `OOP` · `Classes & Objects` · `Encapsulation` · `Inheritance` · `Abstraction` · `Interfaces` · `Exception Handling` · `Collections` · `Threads` · `Lambda Expressions`

---

<p align="center">
  <sub>Java Programming · Concepts, Practicals & OOP</sub>
</p>
