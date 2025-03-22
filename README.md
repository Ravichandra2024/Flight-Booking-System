# Flight Booking System

This Java-based Flight Booking System is a simple console application that allows users to register, log in, search for flights, and book them. The system also provides an administrator option to add flights to the system.

## Features

- **User Registration & Login:**  
  Users can register with their username, email, and password. Once registered, they can log in to access the system.

- **Flight Search & Sorting:**  
  Users can search for flights by specifying the origin, destination, departure date, and return date. The search results are automatically sorted by price in ascending order using the QuickSort algorithm.

- **Flight Booking:**  
  After searching, users can select a flight using its Flight ID and book it by providing passenger details like full name, date of birth, and passport number.

- **Add Flights:**  
  Administrators (or users in admin mode) can add new flights by providing details such as origin, destination, departure and return dates, airline, and price.

## Project Structure

- **Flight.java:**  
  Contains the `Flight` class that models flight details and includes a custom `toString()` method for easy display.

- **User.java:**  
  Contains the `User` class to store user credentials.

- **Booking.java:**  
  Contains the `Booking` class that stores booking details.

- **FlightBookingSystem.java:**  
  The main class which ties together the system functionalities including user registration, login, flight search, booking, and flight addition.

## How to Run

1. **Compile the Program:**
   Open your terminal or command prompt, navigate to the project directory, and compile the code:
   ```bash
   javac FlightBookingSystem.java
   ```

2. **Run the Program:**
   Once compiled, run the application with:
   ```bash
   java FlightBookingSystem
   ```

3. **Follow the Console Prompts:**
   The program will display a menu in the console. Follow the instructions to register, log in, search for flights, book a flight, or add new flights.

## System Requirements

- Java Development Kit (JDK) 8 or higher
- Command line interface (Terminal, Command Prompt, etc.)

## Future Enhancements

- **Database Integration:**  
  Moving from array-based storage to a database for scalability and persistent storage.

- **GUI Interface:**  
  Building a graphical user interface for a more user-friendly experience.

- **Improved Security:**  
  Enhancing password security and adding input validations.
