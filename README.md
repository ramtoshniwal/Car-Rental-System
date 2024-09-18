# Rent-a-Ride : Car-Rental-System

This project implements a simple car rental system using Java. It allows users to:

* Add cars with details like brand, model, and base price per day.
* Add customers with unique IDs and names.
* Rent available cars to customers, specifying the rental duration.
* Return rented cars, displaying rental information for the customer.

**Features:**

* Object-oriented design with `Car`, `Customer`, `Rental`, and `CarRentalSystem` classes.
* User-friendly text-based menu for interaction.
* Availability check for car rentals.
* Rental price calculation based on base price and rental days.
* Functionality to return cars and access associated customer information.

**How to Run:**

1. Save the files `Car.java`, `Customer.java`, `Rental.java`, `CarRentalSystem.java`, and `Main.java` in the same directory.
2. Compile the code using a Java compiler (e.g., `javac Car.java Customer.java Rental.java CarRentalSystem.java Main.java`).
3. Run the compiled application using `java Main`.

**This project demonstrates basic functionalities of a car rental system. You can extend it by adding features like:**

* User authentication
* Persisting data using files or databases
* Different car categories (e.g., economy, luxury)
* Search functionality for finding available cars
