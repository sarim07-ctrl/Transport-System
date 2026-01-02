# Transport-System
The Transport Management and Booking System is a C++ and Qt-based application designed to streamline travel logistics through a dual-interface architecture. This project eliminates the need for an administrative middleman, allowing drivers to directly register vehicle details, routes, and seat capacities into the system. Passengers interact with this shared data through a separate interface where they can browse available trips and book tickets in real-time. By utilizing Qt’s signal and slot mechanism, the application ensures that seat availability updates instantly across the platform once a booking is confirmed. The modular project structure organizes the code into distinct windows for role selection, driver inputs, and passenger actions to ensure high maintainability. Core programming concepts such as structures and arrays are implemented to manage the transport data effectively without a complex database. This simulation provides a practical look into GUI development, emphasizing user-friendly design and crash-resilient input validation. Ultimately, the system serves as an efficient tool for understanding object-oriented programming within a realistic, service-oriented scenario. The project balances functional requirements with a fast response time to deliver a professional-grade desktop utility.

TransportSystem/
│
├── main.cpp                 # Entry point of the application
├── mainwindow.h / .cpp      # Role Selection Window (Home)
├── driverwindow.h / .cpp    # Registration interface for drivers
├── passengerwindow.h / .cpp # Booking interface for passengers
├── data.h / .cpp            # Shared data structures and logic
└── README.md                # Project documentation


          #Transport Management System – User Manual
              Overview

This program is a simple console-based transport management system.
Drivers can register buses and view them.
Passengers can view buses, book seats, and cancel bookings.

               #How to Run

Compile the program using a C++ compiler.

Run the program.

The main menu will appear with options for Passenger, Driver, and Exit.

Main Menu
1. Passenger
2. Driver
3. Exit


Enter the number to choose your role.

Enter 3 to exit the program.

Driver Menu
1. Register Bus
2. View My Buses
3. Back


Register Bus: Enter driver info, bus number, type, route, time, and seat capacity.

View My Buses: Shows all registered buses.

Back: Returns to main menu.

Passenger Menu
1. View Buses
2. Book Seats
3. Cancel Booking
4. Back


View Buses: See all buses with number, type, route, time, and available seats.

Book Seats: Select a bus and enter number of seats to book.

Cancel Booking: Select a bus and enter number of seats to cancel.

Back: Returns to main menu.

Notes

Maximum buses: 10

Seats cannot exceed bus capacity

Cannot cancel more seats than booked

Always enter valid numbers
