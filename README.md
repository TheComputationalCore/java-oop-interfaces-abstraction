# Java OOP Task 3

This repository contains Java programs demonstrating Object-Oriented Programming (OOP) concepts, including encapsulation, abstraction, interfaces, and class relationships. The project includes two main tasks: a Library Management System and a Taxable interface implementation for calculating taxes on employees and products.

## Project Structure

- **Book.java**: Defines the `Book` class with attributes `bookID`, `title`, `author`, and `isAvailable` (Task 1).
- **Library.java**: Implements the `Library` class to manage an array of `Book` objects with methods to add, remove, search, and display books (Task 1).
- **Taxable.java**: Defines the `Taxable` interface with constants `salesTax` and `incomeTax`, and an abstract method `calcTax()` (Task 2).
- **Employee.java**: Implements the `Employee` class with the `Taxable` interface to calculate income tax on yearly salary (Task 2).
- **Product.java**: Implements the `Product` class with the `Taxable` interface to calculate sales tax on unit price (Task 2).
- **Main.java**: Contains the main method (likely `DriverMain`) to accept user input for employee and product information and display respective taxes (Task 2).
- **1.a.png, 1.b.png, 1.c.png, 1.d.png, 2.png**: Screenshots of the code implementations for each task.

## Tasks Overview

### Task 1: Library Management System
This task models a library system using OOP principles:
- **Book Class**: Represents a book with attributes `bookID`, `title`, `author`, and `isAvailable`.
- **Library Class**: Manages a collection of books using an array. Provides methods to:
  - Add a book to the library.
  - Remove a book from the library.
  - Search for a book by `bookID`.
  - Display all books in the library.
- The system allows user interaction to perform these operations.

### Task 2: Taxable Interface Implementation
This task demonstrates the use of interfaces and abstraction for tax calculations:
- **Taxable Interface**: Defines constants `salesTax = 7%` and `incomeTax = 10.5%`, and an abstract method `calcTax()`.
- **Employee Class**: Implements `Taxable` to calculate income tax on the yearly salary. Attributes include `empId`, `name`, and `salary`.
- **Product Class**: Implements `Taxable` to calculate sales tax on the unit price of a product. Attributes include `pid`, `price`, and `quantity`.
- **DriverMain (Main Class)**: Accepts user input for one employee and one product, then calculates and displays the income tax for the employee and sales tax for the product.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/thesoulseizure/task-3.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd task-3
   ```
3. **Compile the Java Files**:
   ```bash
   javac *.java
   ```
4. **Run the Program**:
   - For Task 1 (Library Management System): The interaction logic is likely in `Library.java` or a separate main method within it. Check the code and run:
     ```bash
     java Library
     ```
   - For Task 2 (Taxable Interface): Run the main class:
     ```bash
     java Main
     ```

## Requirements

- Java Development Kit (JDK) 8 or higher.
- A terminal or IDE to compile and run Java programs.

## Screenshots

The repository includes screenshots (1.a.png to 1.d.png for Task 1, and 2.png for Task 2) that show the code implementations for each task. Refer to these images to view the solutions visually.
