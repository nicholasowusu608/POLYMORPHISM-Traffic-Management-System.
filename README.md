# POLYMORPHISM-Traffic-Management-System

## Project Overview
This repository contains a Python implementation of a **Smart Traffic Management System** designed to demonstrate the concept of **Polymorphism** in Object-Oriented Programming (OOP).

In a smart city, various traffic control devices respond to a single standard command (`activate()`), but each performs a unique operational task based on its class behavior.

## Key OOP Concepts Demonstrated
* **Polymorphism:** A single interface (`activate()`) executes different behavior depending on the underlying subclass object.
* **Inheritance:** `TrafficLight`, `SpeedCamera`, `PedestrianSignal`, and `EmergencySiren` inherit from the base `TrafficDevice` class.
* **Extensibility:** The `EmergencySiren` class can be added to the collection without making any modifications to the existing device activation loop.

## How to Run
1. Ensure Python 3.x is installed on your machine.
2. Clone this repository:
   ```bash
   git clone [https://github.com/nicholasowusu608/POLYMORPHISM-Traffic-Management-System.git](https://github.com/nicholasowusu608/POLYMORPHISM-Traffic-Management-System.git)
