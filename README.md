<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=250&section=header&text=Java%20OOP%20Assignments&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Amandeep%20Kumar%20|%20Java%20Developer%20in%20Progress&descAlignY=55&descAlign=50"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-blue?style=for-the-badge&logo=java">
  <img src="https://img.shields.io/badge/Java-Version%2021-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/OOP-Concepts-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

---

## 🐍 Contribution Graph

<p align="center">
  <img src="https://raw.githubusercontent.com/amanDeep080/Java-Advanced-OOPs-Assignment/output/github-contribution-grid-snake-dark.svg" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=amanDeep080&show_icons=true&hide_title=true&theme=tokyonight" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=amanDeep080&theme=tokyonight" />
</p>

---

# 🚀 Project Overview

This project demonstrates core **Object-Oriented Programming (OOP)** principles in Java through three structured assignments.

### 🔥 Concepts Covered
- ✔ Abstract Classes  
- ✔ Inheritance  
- ✔ Method Overriding  
- ✔ Interfaces  
- ✔ Polymorphism  
- ✔ Encapsulation  

All assignments are implemented within a single Java project using clean package organization.

---

# 📂 Project Structure

```text
src/
 ├─ assignment4_shapes/
 │   ├─ Shape.java
 │   ├─ Circle.java
 │   ├─ Rectangle.java
 │   └─ Triangle.java
 │
 ├─ assignment5_vehicles/
 │   ├─ Vehicle.java
 │   ├─ Car.java
 │   └─ Bike.java
 │
 ├─ assignment6_employees/
 │   ├─ Payable.java
 │   ├─ SalariedEmployee.java
 │   └─ ContractEmployee.java
 │
 └─ AssignmentMain.java
🔷 Assignment 4 — Geometric Shape Hierarchy
🧩 Abstract Classes
🎯 Objective

Create a common blueprint (Shape) ensuring each shape calculates:

📐 Area

📏 Perimeter

🛠 Implementation

Shape → Abstract Class

Circle, Rectangle, Triangle → Concrete subclasses

public abstract class Shape {
    public abstract double area();
    public abstract double perimeter();
}

🔷 Assignment 5 — Vehicle Start Behavior
🚗 Inheritance & Method Overriding
🎯 Objective

Reuse base behavior and override specific functionality.

Vehicle → Base class

Car, Bike → Subclasses

Method overridden:

void start();

🔷 Assignment 6 — Employee Compensation
💼 Interfaces
🎯 Objective

Define a contract for payment calculation.

Payable → Interface

SalariedEmployee

ContractEmployee

double calculatePay();

▶️ How to Run
💻 Using IDE

Open in Eclipse / IntelliJ

Run AssignmentMain.java

🖥 Using Command Line
javac AssignmentMain.java assignment4_shapes/*.java assignment5_vehicles/*.java assignment6_employees/*.java

java AssignmentMain

=== Assignment 4: Shapes ===
Circle Area: 78.53
Circle Perimeter: 31.41
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


🧠 OOP Principles Demonstrated
Principle	Implementation
Abstraction	Shape, Payable
Inheritance	Car & Bike
Polymorphism	Overridden methods
Encapsulation	Private fields
Interface	Payment contract
👨‍💻 Author

Amandeep Kumar
