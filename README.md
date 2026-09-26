# Week 5 Assignment — Advanced Java

## Student Information

**Name:** Rushikesh Asawale
**Course:** B.Tech Information Technology
**Subject:** Advanced Java
**Assignment:** Week 5 — Advanced Java

---

## Objective

The objective of this assignment is to understand and implement important Advanced Java concepts through practical programming tasks.

The assignment covers:

* Packages
* Interfaces
* Abstract Classes
* File Handling
* Multithreading

---

## Technologies Used

* **Programming Language:** Java
* **JDK:** 17+
* **IDE:** IntelliJ IDEA / Eclipse / VS Code

---

# Tasks

## Task 1 — Packages

### Concept

Java Packages are used to organize related classes and interfaces.

### Implementation

A custom package named `studentmanagement` is created. The `Student` class stores:

* Student ID
* Student Name
* Course

The class is imported and used from another Java file.

### Files

```text
Task1-Packages/
├── studentmanagement/
│   └── Student.java
└── PackageDemo.java
```

### Concepts Used

* `package`
* `import`
* Classes and Objects
* Constructors
* Encapsulation

---

## Task 2 — Interface: Payment System

### Concept

An interface defines a contract that implementing classes must follow.

### Implementation

A `Payment` interface is created with:

```java
pay()
showPaymentDetails()
```

Two classes implement the interface:

* `UPIPayment`
* `CardPayment`

Both classes provide their own implementation of the payment methods.

### File

```text
Task2_Interface.java
```

### Concepts Used

* Interface
* `implements`
* Method Overriding
* Polymorphism

---

## Task 3 — Abstract Class: Shape Calculator

### Concept

Abstract classes are used to provide a common structure for related classes.

### Implementation

An abstract class named `Shape` is created with:

```java
calculateArea()
displayMessage()
```

Two child classes extend `Shape`:

* `Circle`
* `Rectangle`

Each class implements the `calculateArea()` method differently.

### File

```text
Task3_AbstractClass.java
```

### Concepts Used

* Abstract Class
* Abstract Method
* Concrete Method
* `extends`
* Method Overriding
* Abstraction

---

## Task 4 — File Handling: Student Records

### Concept

Java File Handling allows programs to create, write, and read files.

### Implementation

The program creates a file named:

```text
students.txt
```

Student information is written into the file and then read and displayed in the console.

The stored information includes:

* Student ID
* Student Name
* Course
* Marks

### Files

```text
Task4_FileHandling.java
students.txt
```

### Concepts Used

* `FileWriter`
* `FileReader`
* `BufferedReader`
* Exception Handling
* `IOException`

---

## Task 5 — Multithreading Basics

### Concept

Multithreading allows multiple tasks to execute concurrently.

### Implementation

Two threads are created:

**Thread 1:** Prints numbers from 1 to 10.

**Thread 2:** Prints:

```text
Learning Java Multithreading
```

multiple times.

### File

```text
Task5_Multithreading.java
```

### Concepts Used

* `Thread`
* `extends Thread`
* `run()`
* `start()`
* `Thread.sleep()`
* Concurrent Execution

---

# Project Structure

```text
Week5-Advanced-Java/
│
├── Task1-Packages/
│   ├── studentmanagement/
│   │   └── Student.java
│   └── PackageDemo.java
│
├── Task2_Interface.java
├── Task3_AbstractClass.java
├── Task4_FileHandling.java
├── students.txt
├── Task5_Multithreading.java
│
└── README.md
```

---

# Concepts Learned

Through this assignment, I gained practical understanding of:

* Java Packages
* Interfaces
* Abstraction
* Inheritance
* Polymorphism
* Method Overriding
* File Input/Output
* Exception Handling
* Multithreading
* Thread Creation and Execution

---

# Challenges Faced

During the implementation of this assignment, I faced challenges in understanding package organization, implementing interfaces, working with abstract classes, handling file input/output operations, and understanding the execution order of multiple threads.

Working on these tasks helped me understand how Java provides different features for organizing code, implementing abstraction, handling files, and executing multiple tasks concurrently.

---

# Conclusion

This assignment provided practical experience with important Advanced Java concepts. By implementing packages, interfaces, abstract classes, file handling, and multithreading, I developed a better understanding of Java programming and object-oriented programming principles.

The practical implementation of these concepts helped connect theoretical knowledge with real programming applications.

---

## Submission

This repository contains the complete source code and required files for the Week 5 Advanced Java assignment.

**Submitted by:** Rushikesh Asawale
