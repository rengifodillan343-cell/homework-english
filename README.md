# homework-english

# Parking Lot System (Python)

## Description
This project is a simple **Parking Lot Management System** written in Python.  
It allows users to manage a small parking lot with 10 spaces through a console menu.

Users can check available spaces, park a car using its license plate, remove a car, and exit the program.

## Features
- View the current status of all parking spaces
- Park a car by entering its license plate
- Remove a car from the parking lot
- Simple menu system
- Simulated loading effect using `time.sleep()`

## How It Works
1. The program creates a list with **10 parking spaces**.
2. Each space starts as **available (`None`)**.
3. When a car enters, the user enters the **license plate** and it is stored in the first available space.
4. When removing a car, the system searches for the **license plate** and frees that space.
5. The program runs in a loop until the user chooses **Exit**.

## Menu Options
1. Show parking spaces status  
2. Park a car  
3. Remove a car  
4. Exit  

## Technologies Used
- Python
- Lists
- Loops
- Conditionals
- `time` module

## Example

--- PARKING LOT MENU ---

Show parking spaces status

Park a car

Remove a car

Exit


## Author
Created as a practice project for learning Python and basic programming logic.
