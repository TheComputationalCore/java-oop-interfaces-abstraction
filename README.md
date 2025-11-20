# Java OOP Interfaces & Abstraction 

This repository contains Java programs demonstrating essential Object-Oriented Programming (OOP) concepts such as **encapsulation, abstraction, interfaces, and class relationships**. The project is organized into **two major tasks**:

1. **Library Management System**  
2. **Taxable Interface Implementation**  

---

## 📁 Project Structure

```
.
├── Book.java
├── Library.java
├── Taxable.java
├── Employee.java
├── Product.java
├── Main.java
├── 1.a.png
├── 1.b.png
├── 1.c.png
├── 1.d.png
└── 2.png
```

### File Overview
- **Book.java** – Defines the `Book` class with attributes `bookID`, `title`, `author`, and `isAvailable`.  
- **Library.java** – Manages an array of `Book` objects; methods to add, remove, search, and display.  
- **Taxable.java** – Interface defining constants `salesTax`, `incomeTax`, and abstract method `calcTax()`.  
- **Employee.java** – Implements `Taxable` to compute income tax.  
- **Product.java** – Implements `Taxable` to compute sales tax.  
- **Main.java** – Driver for tax calculations.  

---

## 📚 Task 1 — Library Management System

### Book Class
Represents:
- `bookID`
- `title`
- `author`
- `isAvailable`

### Library Class
Features:
✔ Add books  
✔ Remove books  
✔ Search by `bookID`  
✔ Display all books  

### 📸 Screenshots
![1a](1.a.png)  
![1b](1.b.png)  
![1c](1.c.png)  
![1d](1.d.png)  

---

## 🧮 Task 2 — Taxable Interface Implementation

### Taxable Interface
Defines:
- `salesTax = 0.07`
- `incomeTax = 0.105`
- `calcTax()` abstract

### Employee Class
Computes **income tax** on salary.  

### Product Class
Computes **sales tax** on product price.  

### 📸 Screenshot
![Task2](2.png)

---

## ▶️ Running the Programs

### Clone
```bash
git clone https://github.com/TheComputationalCore/java-oop-interfaces-abstraction.git
```

### Compile
```bash
javac *.java
```

### Run Task 1
```bash
java Library
```

### Run Task 2
```bash
java Main
```

---

## Requirements
- Java JDK 8+
- Terminal or IDE

---

## 📝 License
Add a license if needed.
