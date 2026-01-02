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
