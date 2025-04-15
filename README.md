# **SSGS Calculator**

## **✨ Project Overview**
The **SSGS Calculator** is a simple yet powerful Node.js-based application designed to perform basic arithmetic operations: **addition**, **subtraction**, **multiplication**, and **division**. 

This project includes:
- A **core module** (`calculator.js`) implementing the arithmetic operations.
- A **command-line interface (CLI)** (`app.js`) for seamless user interaction.
- **Unit tests** written using Jest to ensure the correctness of the core logic.
- A **Continuous Integration (CI) pipeline** using GitHub Actions to automate testing and code coverage reporting.

This project was developed as part of a lab assignment to practice software development principles such as **modular design**, **unit testing**, **version control**, and **CI/CD integration**.

---

## **🎯 Scope of the Project**
The scope of this project includes:

### **Core Functionality**
- Implementing basic arithmetic operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Handling edge cases like **division by zero** and **negative numbers**.

### **Testing**
- Writing **unit tests** for all functions using Jest.
- Achieving **100% code coverage** for the core module.

### **Version Control**
- Managing the project under **Git version control** and hosting it on GitHub.

### **CI/CD Pipeline**
- Setting up a **GitHub Actions pipeline** to:
  - Automatically run tests on every push or pull request.
  - Generate and upload a **code coverage report** as an artifact.

### **Documentation**
- Providing clear instructions for **installation**, **usage**, and **testing** in this `README.md` file.

---

## **✅ What We Did**
### **1. Core Module Development**
We implemented a `calculator.js` module with the following functions:
- `addizione(a, b)`: Adds two numbers.
- `sottrazione(a, b)`: Subtracts two numbers.
- `moltiplicazione(a, b)`: Multiplies two numbers.
- `divisione(a, b)`: Divides two numbers, with error handling for division by zero.

Example:
```javascript
const calculator = require('./calculator');
console.log(calculator.addizione(2, 3)); // Output: 5
console.log(calculator.divisione(10, 0)); // Throws an error: "Impossibile dividere per zero."
