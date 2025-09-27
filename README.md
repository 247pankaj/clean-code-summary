# 📘 Clean Code: A Handbook of Agile Software Craftsmanship

![Book](https://img.shields.io/badge/Book-Clean%20Code-blue)  
![Summary](https://img.shields.io/badge/Type-Summary-brightgreen)  
![Status](https://img.shields.io/badge/Status-Active-lightgrey)  

This repository provides a structured summary of **Robert C. Martin’s (Uncle Bob)** classic book  
*Clean Code: A Handbook of Agile Software Craftsmanship*.  

It is one of the most influential books in professional software development, focusing on writing code that is **clean, maintainable, and sustainable**.

---

## 📑 Table of Contents

- [Part I: Principles, Patterns, and Practices](#part-i-principles-patterns-and-practices)  
- [Part II: Case Studies](#part-ii-case-studies)  
- [Part III: Smells and Heuristics](#part-iii-smells-and-heuristics)  
- [📖 Reference](#-reference)  

---

## Part I: Principles, Patterns, and Practices

### 1. Clean Code
- Writing clean code is a professional responsibility.  
- Messy code leads to high long-term costs.  
- Apply the **Boy Scout Rule**: always leave the code cleaner than you found it.  

### 2. Meaningful Names
- Names must be **intention-revealing, unambiguous, and pronounceable**.  
- Use nouns for classes, verbs for methods.  
- Avoid Hungarian notation, mental mapping, or cryptic names.  

### 3. Functions
- Functions should be small, do **one thing**, and stay at a single level of abstraction.  
- Follow the **Stepdown Rule**.  
- Minimize arguments (ideally 0–2).  
- Avoid flag arguments and hidden side effects.  

### 4. Comments
- Comments are often a failure to express intent in code.  
- Use sparingly (legal notes, clarifications, warnings).  
- Avoid redundant, misleading, or commented-out code.  

### 5. Formatting
- Code should read like a newspaper: high-level concepts first, details later.  
- Use spacing and indentation to clearly separate ideas.  

### 6. Objects and Data Structures
- Objects expose **behavior**; data structures expose **data**.  
- Follow the **Law of Demeter**: don’t expose internal details unnecessarily.  

### 7. Error Handling
- Prefer **exceptions** over error codes.  
- Keep error-handling separate from core logic.  
- Provide meaningful context in exceptions.  
- Avoid returning or passing `null`.  

### 8. Boundaries
- Isolate third-party code with **wrappers/adapters**.  
- Decoupling makes systems safer and easier to update.  

### 9. Unit Tests
- Tests must be clean and first-class citizens.  
- Follow TDD’s three laws.  
- Tests should be **F.I.R.S.T.**: Fast, Independent, Repeatable, Self-Validating, Timely.  
- Each test should assert **one thing only**.  

### 10. Classes
- Apply the **Single Responsibility Principle (SRP)**.  
- Classes should be small, cohesive, and have **one reason to change**.  

### 11. Systems
- Separate **construction from use** (startup/configuration vs. runtime).  
- Use Dependency Injection and Factories for decoupling.  

### 12. Emergence
Follow the **Four Rules of Simple Design**:  
1. Runs all tests.  
2. Contains no duplication.  
3. Expresses intent clearly.  
4. Minimizes classes and methods.  

### 13. Concurrency
- Keep concurrency concerns isolated.  
- Apply SRP to concurrent code.  
- Keep synchronized sections small.  
- Prioritize clarity and testability in multithreaded systems.  

---

## Part II: Case Studies

### Chapter 14 – Successive Refinement
- Iterative refactoring of a messy class (`Args.java`).  
- Demonstrates applying the **Boy Scout Rule** in practice.  

### Chapter 15 – JUnit Internals
- Refactors parts of the JUnit framework (`ComparisonCompactor`).  
- Shows incremental cleanup while preserving tests.  

### Chapter 16 – Refactoring SerialDate
- Applies clean code principles to a larger legacy system (`SerialDate`).  
- Improves naming, structure, readability, and testability.  

---

## Part III: Smells and Heuristics

### Chapter 17 – Smells and Heuristics
- A **reference catalog** of common code smells and heuristics.  
- Covers class design, function signatures, test quality, and maintainability.  
- Serves as a **long-term checklist** for daily coding practices.  

---

## 📖 Reference

- **Book**: *Clean Code: A Handbook of Agile Software Craftsmanship* by Robert C. Martin (Uncle Bob).  
- **GitHub Reference**: [Clean Code Book Repository](https://github.com/Gatjuat-Wicteat-Riek/clean-code-book)  

---

## 🤝 Contribution

Contributions are welcome! 🚀  
If you’d like to expand or improve the summaries:  

1. Fork the repo  
2. Create a feature branch  
3. Submit a Pull Request  

---

## ⭐ Support

If you find this repository useful, please **star it** ⭐ to help others discover it!  

---
