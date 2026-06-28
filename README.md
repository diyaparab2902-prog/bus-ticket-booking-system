# bus-ticket-booking-system
A Python-based bus ticket booking system with booking, cancellation, and fare calculation features.
# Bus Ticket Booking System

## Overview

The Bus Ticket Booking System is a Python-based console application that allows users to check seat availability, book tickets, and cancel tickets for different bus routes. The project demonstrates the use of Python concepts such as loops, conditional statements, lists, and user input handling.

## Features

* View available seats for different routes.
* Book tickets for multiple passengers.
* Calculate ticket fare based on passenger age:

  * Age ≤ 10 years: ₹100
  * Age ≥ 60 years: ₹150
  * Others: ₹200
* Cancel booked tickets.
* Refund calculation with a 5% deduction on the ticket fare.
* Case-insensitive city name input.
* Prevention of overbooking when seats are unavailable.

## Supported Routes

| Source | Destination | Bus Name         |
| ------ | ----------- | ---------------- |
| Mumbai | Pune        | Shivneri         |
| Mumbai | Nashik      | Sahydari Travels |
| Pune   | Mumbai      | Deccan Rider     |
| Pune   | Nashik      | Western Express  |
| Nashik | Mumbai      | Nashik Express   |
| Nashik | Pune        | Pune Rider       |

## Technologies Used

* Python 3
* Lists
* Loops
* Conditional Statements
* User Input Handling

## How to Run

1. Clone or download the repository.
2. Open the project in Python or Google Colab.
3. Run the Python file.
4. Follow the on-screen menu options:

   * View Available Seats
   * Book Tickets
   * Cancel Tickets
   * Exit

## Sample Workflow

1. Check available seats for a route.
2. Enter the number of seats to book.
3. Provide passenger details (name and age).
4. View the total fare.
5. Cancel tickets if required and receive a refund after deduction.

## Learning Outcomes

This project helped in understanding:

* Menu-driven programming
* List operations (`append()` and `remove()`)
* Input validation
* Fare calculation logic
* State management using variables
* Basic problem-solving with Python

## Future Improvements

* Generate ticket IDs.
* Assign seat numbers automatically.
* Store booking history.
* Add more routes and buses.
* Save data using files or a database.
* Build a graphical user interface (GUI).

## Author

Diya Parab

Beginner Python Project created for learning programming concepts and problem-solving.

