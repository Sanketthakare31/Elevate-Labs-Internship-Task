# Elevate-Labs-Internship-Task
Java Developer Intern Daily Task provide by Elevate Labs

# Java Command-Line Calculator 🧮

**Simple Calculator (Addition, Subtraction, Multiplication, Division)  
Built in Java 17 × CLI**

---

## Overview

A console-based Java application to perform basic arithmetic operations:  
- Addition, subtraction, multiplication, and division  
- Live input via `Scanner`, with robust error handling for non-numeric inputs and division-by-zero  
- Looping menu interface until the user chooses to exit

This project demonstrates control flow, modular methods, exception handling (`InputMismatchException`), and clean console interaction.
## Table of Contents

1. [Features](#features)  
2. [Prerequisites](#prerequisites)  
3. [Setup & Compilation](#setup--compilation)  
4. [Usage Examples](#usage-examples)  
5. [Error Handling](#error-handling)  
6. [Code Structure](#code-structure)  
7. [To-Do / Improvements](#to-do--improvements)  
8. [Contributing](#contributing)  
9. [License](#license)  

---

## Features

- ☑️ Add, subtract, multiply, or divide two numbers  
- 🔁 Loop menu until user exits  
- 🛑 Prevent division by zero  
- 📥 Validate user input; reprompt on invalid entries  

---

## Prerequisites

- Java Development Kit (JDK) 17 or later  
- Command-line access (`java`, `javac`)  

---

## Setup & Compilation

```bash
$ javac Calculator.java
$ java Calculator

Choose an operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exit

Enter your choice (1/2/3/4/5): 1
Enter the first number: 12.5
Enter the second number: 3.4
Result: 15.9
