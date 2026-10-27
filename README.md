# Week 10: Object-Oriented Programming in Dart

**Course:** PC16 – Mobile Development with Lab  
**Institution:** National Teachers College  
**Deliverable:** Enhanced OOP Console Application  

## Overview
This Dart console application demonstrates core Object-Oriented Programming principles as required for the Week 10 individual task. It expands upon a base class to create a small hierarchy, utilizing inheritance, polymorphism, abstract classes, and mixins.

## Features & Rubric Mapping

* **Base Class:** `Vehicle` containing shared properties (`brand`, `model`) and methods.
* **Inheritance (25 pts):** `Car` and `Motorcycle` classes properly use the `extends` keyword to inherit from `Vehicle`.
* **Polymorphism (25 pts):** The `startEngine()` method is overridden in both the `Car` and `Motorcycle` classes to exhibit distinct behaviors.
* **Abstract Class / Interface (25 pts):** The `Maintainable` abstract class defines a contract (`performMaintenance()`) that both derived classes successfully implement.
* **Mixin (25 pts):** The `GPSNavigation` mixin is applied to a completely separate class (`SmartWatch`) using the `with` keyword, demonstrating shared behavior outside the main inheritance chain.

## How to Run

1. Ensure you have the [Dart SDK](https://dart.dev/get-dart) installed on your machine, or use [DartPad](https://dartpad.dev/).
2. Save the code in a file named `main.dart`.
3. Open your terminal or command prompt.
4. Run the following command:
   ```bash
   dart run Code.dart
