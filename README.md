🚀 Java Advanced OOP Assignments
<p align="center"> <img src="https://img.shields.io/badge/Language-Java-blue?style=for-the-badge&logo=java"> <img src="https://img.shields.io/badge/Java-Version%2021-orange?style=for-the-badge"> <img src="https://img.shields.io/badge/OOP-Concepts-success?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"> </p>
📌 Project Overview

This project demonstrates core Object-Oriented Programming (OOP) concepts in Java through three structured assignments:

🔹 Abstract Classes

🔹 Inheritance & Method Overriding

🔹 Interfaces

🔹 Polymorphism

🔹 Encapsulation

All assignments are implemented within a single Java project using proper package organization.

📂 Project Structure
src/
 ├─ assignment4_shapes/
 │   ├─ Shape.java
 │   ├─ Circle.java
 │   ├─ Rectangle.java
 │   ├─ Triangle.java
 │
 ├─ assignment5_vehicles/
 │   ├─ Vehicle.java
 │   ├─ Car.java
 │   ├─ Bike.java
 │
 ├─ assignment6_employees/
 │   ├─ Payable.java
 │   ├─ SalariedEmployee.java
 │   ├─ ContractEmployee.java
 │
 └─ AssignmentMain.java

🔷 Assignment 4 — Geometric Shape Hierarchy
🧩 (Abstract Classes)
🎯 Objective

Create a common blueprint (Shape) for geometric shapes ensuring each can calculate:

Area

Perimeter

🛠 Implementation

Shape → Abstract class

Circle, Rectangle, Triangle → Concrete subclasses

Each overrides:

double area();
double perimeter();

💡 Concepts Demonstrated

✔ Abstraction
✔ Method Overriding
✔ Runtime Polymorphism

🔷 Assignment 5 — Vehicle Start Behavior
🚗 (Inheritance & Overriding)
🎯 Objective

Demonstrate inheritance and customize behavior using method overriding.

🛠 Implementation

Vehicle → Base class

Car, Bike → Subclasses

Override:

void start();

💡 Concepts Demonstrated

✔ Inheritance
✔ Upcasting
✔ Runtime Polymorphism

🔷 Assignment 6 — Employee Compensation
💼 (Interfaces)
🎯 Objective

Use an interface to define a payment contract.

🛠 Implementation

Payable → Interface

SalariedEmployee

ContractEmployee

Both implement:

double calculatePay();

💡 Concepts Demonstrated

✔ Interface
✔ Abstraction
✔ Implementation
✔ Polymorphism

▶️ How to Run
🔹 Using IDE (Recommended)

Open project in Eclipse / IntelliJ / VS Code

Run AssignmentMain.java

🔹 Using Command Line

Compile:

javac AssignmentMain.java assignment4_shapes/*.java assignment5_vehicles/*.java assignment6_employees/*.java


Run:

java AssignmentMain

🖥 Sample Output
=== Assignment 4: Shapes ===
Circle Area: 78.53981633974483
Circle Perimeter: 31.41592653589793
Rectangle Area: 24.0
Rectangle Perimeter: 20.0
Triangle Area: 6.0
Triangle Perimeter: 12.0

=== Assignment 5: Vehicles ===
Vehicle is starting.
Car engine starts with a key.
Bike engine starts with a kick or button.

=== Assignment 6: Employees ===
Salaried Monthly Pay: 50000.0
Contract Total Pay: 20000.0

🧠 OOP Concepts Summary
Concept	Implementation
Abstraction	Shape, Payable
Inheritance	Car & Bike extend Vehicle
Polymorphism	Overridden methods
Encapsulation	Private fields + getters
Interface	Payment contract
👨‍💻 Author

Amandeep Kumar
