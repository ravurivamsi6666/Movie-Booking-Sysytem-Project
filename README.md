# Movie Booking System (C++ OOP Project)

Academic Group Project – IIITDM Kancheepuram

---

## Overview

This project is a **Movie Booking System implemented in C++ using Object-Oriented Programming (OOP) principles**.
It simulates a real-world movie ticket booking platform where users can browse movies, view show timings, select seats, and manage ticket bookings.

The system is designed with a modular architecture using multiple classes to represent real-world entities such as **Users, Movies, Shows, Seats, Bookings, and Payments**.
It demonstrates how OOP concepts can be applied to build a structured and maintainable software system.

---

## Features

* User registration and login
* Browse available movies
* View show timings
* Seat selection and booking
* Booking management
* Payment handling
* Admin functionalities for managing movies and shows
* Activity logging system
* File-based data storage using CSV files

---

## Object-Oriented Concepts Used

The project demonstrates key Object-Oriented Programming principles:

### Encapsulation

* Each entity such as `User`, `Movie`, `Seat`, and `Booking` is implemented as a class that encapsulates its data and behavior.

### Inheritance

* Shared behavior between related classes is implemented through inheritance.

### Abstraction

* Complex system logic is divided into simplified modules and interfaces.

### Modularity

* Each class is implemented in separate `.cpp` and `.h` files, improving maintainability and scalability.

---

## Project Structure

```
Movie-Booking-System
│
├── main.cpp
├── Admin.cpp / Admin.h
├── User.cpp / User.h
├── Movie.cpp / Movie.h
├── Show.cpp / Show.h
├── Seat.cpp / Seat.h
├── Booking.cpp / Booking.h
├── Payment.h
├── FileManager.cpp / FileManager.h
├── Logger.cpp / Logger.h
├── Exceptions.h
├── IDGenerator.h
├── Utils.h
├── Report.cpp / Report.h
│
├── movies_db.csv
├── bookings_db.csv
├── activity_log.csv
│
└── README.md
```

---

## Technologies Used

* **Programming Language:** C++
* **Concepts:** Object-Oriented Programming
* **Data Storage:** CSV files
* **Version Control:** Git & GitHub

---

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/Movie-Booking-System-Project.git
```

### 2. Navigate to the project directory

```
cd Movie-Booking-System-Project
```

### 3. Compile the program

Using g++:

```
g++ *.cpp -o movie_booking
```

### 4. Run the program

```
./movie_booking
```

---

## Data Storage

The system stores persistent data using CSV files:

* `movies_db.csv` → stores movie details
* `bookings_db.csv` → stores booking records
* `activity_log.csv` → records system activity logs

This approach allows persistent storage without requiring a database.

---

## Contributors

This project was developed as a **group Object-Oriented Programming project**.

Team Members:

* Charan Sai Suluru - Charan-dev247
* Depa Varshith Reddy - varshithreddy137
* Tarun Sekhar
* Ravuri Krishna Vamsi - ravurivamsi6666
* Shanmukha Sai

---

## Contributions

This project was developed collaboratively by all team members.

All contributors participated in:

* System design and architecture planning
* Implementation of modules using OOP principles
* Integration of different components
* Testing and debugging
* Documentation and project structuring

Each member contributed equally to the development and refinement of the Movie Booking System.

---

## Future Improvements

* Add a graphical user interface (GUI)
* Integrate a database (MySQL / SQLite)
* Add online payment gateway integration
* Develop a web-based or mobile-based interface

---

## License

This project is developed for **educational purposes as part of an academic assignment** at IIITDM Kancheepuram.
