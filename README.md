# Vehicle Rental System

A Vehicle Information System for a car rental agency, demonstrating object-oriented programming principles in Java, such as interfaces, polymorphism, and contract enforcement.

---

## Project Structure

```
VehicleRentalSystem/
├── src/
│   ├── Vehicle.java         // Core interface for all vehicles
│   ├── CarVehicle.java      // Specific interface for Cars
│   ├── MotorVehicle.java    // Specific interface for Motorcycles
│   ├── TruckVehicle.java    // Specific interface for Trucks
│   ├── Car.java             // Class implementing Vehicle and CarVehicle
│   ├── Motorcycle.java      // Class implementing Vehicle and MotorVehicle
│   ├── Truck.java           // Class implementing Vehicle and TruckVehicle
│   └── VehicleManager.java  // Main program with user interaction (contains the main method)
└── README.md                // Project documentation
```

---

## Key Modules and Implementation Details

### Interface Design

- **Vehicle**: The core interface defining common methods (`getMake`, `getModel`, `getYear`).
- **CarVehicle, MotorVehicle, TruckVehicle**: Specialized interfaces defining unique attributes and behaviors for each vehicle type.

### Class Implementation

- **Car, Motorcycle, Truck**: Concrete classes implementing the core `Vehicle` interface and their respective specialized interfaces to handle unique properties (e.g., number of doors, engine type, cargo capacity).

### Main Program (`VehicleManager`)

- An interactive console application that prompts the user to create and populate objects of all three vehicle types.

---

## How to Run

1. **Compile the source files:**
   ```sh
   javac src/*.java
   ```

2. **Run the main program:**
   ```sh
   java -cp src VehicleManager
   ```

---

## Features

- Demonstrates Java interfaces and class implementation.
- Enforces contracts for vehicle types.
- Interactive console-based user input for creating vehicle objects.

---

## Assignment Details

This project is designed to illustrate:
- Use of interfaces for contract enforcement.
- Polymorphism in Java.
- Clean separation of concerns for different vehicle types.

---