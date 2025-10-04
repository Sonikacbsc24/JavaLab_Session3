# JavaLab_Session3
Java program that demostrates Multi-level Inheritance using constructor chaining, method overriding and the super keyword.

Java program demonstrating multi-level inheritance using the Vehicle → Car → ElectricCar hierarchy.

This program showcases the use of inheritance, constructor chaining, method overriding, and the super keyword to build an automobile classification system.

A base class Vehicle is created with an attribute brand.

The Car class extends Vehicle, adding a year attribute and using super to call the parent constructor.

The ElectricCar class further extends Car, adding a batteryCapacity attribute and overriding the showDetails() method to include all details.

In the main method, an ElectricCar object (for example, Tesla 2024 model) is created, and its details are displayed using overridden methods from all parent classes.

This demonstrates how subclass constructors and methods can reuse and enhance parent functionality through super and overriding.

## Program Output:

Brand: Tesla

Year: 2024

Battery Capacity: 100 kWh
