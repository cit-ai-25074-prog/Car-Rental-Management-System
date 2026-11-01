Car Rental Management System (C++)

1. Project Overview

The Car Rental Management System is a console-based application developed using C++ and Object-Oriented Programming (OOP).

The system helps manage cars and customers and allows users to rent and return vehicles بسهولة.

2. Project Features

* Add a new car.
* Register a new customer.
* Display all cars.
* Search for a car by ID.
* Search for cars by brand.
* Rent an available car.
* Calculate rental costs.
* Return a rented car.
* Display all registered customers.

3. Classes Used

Vehicle

The base class that contains common vehicle information such as ID, brand, model, price, and availability.

Car

A derived class that inherits from Vehicle and adds the manufacturing year.

Customer

Stores customer information, including ID, name, and phone number.

RentalSystem

Manages the cars, customers, searching, renting, and returning operations.

4. Object-Oriented Programming Concepts

This project demonstrates the following OOP concepts:

1. Classes and Objects: Creating classes and objects to organize the program.
2. Encapsulation: Protecting data using private and protected access modifiers.
3. Constructors: Initializing objects when they are created.
4. Destructors: Releasing dynamically allocated memory.
5. Inheritance: The Car class inherits from the Vehicle class.
6. Polymorphism: Using virtual functions and function overriding.
7. Function Overloading: Using searchCar() with different parameter types.
8. Access Modifiers: Using private, protected, and public.

5. Libraries Used

* iostream: Input and output operations.
* string: Handling text data.
* vector: Storing collections of cars and customers.

6. How to Compile and Run

A C++ compiler is required.

Using GCC:

g++ -std=c++14 main.cpp -o car_rental

Run the program:

./car_rental

7. How the System Works

The user interacts with the program through a menu.

The user can add cars, register customers, search for vehicles, rent available cars, and return rented vehicles.

The rental cost is calculated by multiplying the daily rental price by the number of rental days.

8. Project Requirements

* C++ Compiler.
* Basic knowledge of C++.
* Object-Oriented Programming concepts.

9. Project Limitation

The application stores information in memory. Data is not permanently saved after the program closes.

10. Conclusion

The Car Rental Management System demonstrates the practical use of C++ and Object-Oriented Programming concepts through a simple and organized vehicle rental application.
