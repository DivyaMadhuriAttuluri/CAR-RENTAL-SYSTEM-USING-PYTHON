# CAR-RENTAL-SYSTEM-USING-PYTHON
### 1. `car_rental.py` - Module File
This module contains two classes that implement the core functionality:

#### `CarRental` class:
- **Constructor**: Initializes the car rental shop with a specified number of cars (default: 20)
- **Methods**:
  - `display_available_cars()`: Shows current inventory
  - `rent_hourly()`, `rent_daily()`, `rent_weekly()`: Rental methods with different pricing models
  - `return_car()`: Processes returns and generates bills
  - `_validate_rental()`: Private helper method for validating rental requests

#### `Customer` class:
- **Constructor**: Initializes with a customer ID
- **Methods**:
  - `request_car()`: Requests a rental with specified quantity and rental type
  - `return_car()`: Returns previously rented cars and gets the bill

### 2. `CarRentalMain.py` - Main Program File
This file implements the user interface and program flow:

- **Functions**:
  - `display_menu()`: Shows the main menu options
  - `main()`: Controls the program flow and user interactions
- Handles input validation and error management
- Maintains customer records with a simple ID assignment system

## Key Features

1. **Object-Oriented Design**: Uses classes, methods, and encapsulation
2. **DateTime Implementation**: Tracks rental times accurately
3. **Flexible Rental Options**: Hourly ($50/car), Daily ($500/car), Weekly ($2500/car)
4. **Automatic Inventory Management**: Updates car availability
5. **Bill Generation**: Calculates costs based on rental period
6. **Input Validation**: Ensures positive numbers and available inventory
7. **Error Handling**: Gracefully manages invalid inputs
