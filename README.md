# Smart Home Management System (C++)

## Project Description
This is a **console-based Smart Home Management System** developed in **C++** using **Object-Oriented Programming (OOP)** concepts.  
The system allows users to manage rooms and smart devices, control them remotely, schedule actions, monitor energy usage, and store data using file handling.

This project is designed for **beginners** and **academic purposes** to demonstrate real-world use of OOP concepts in C++.

---

## Features
- User registration and login with password validation
- Room management (add and view rooms)
- Device management (add and view devices)
- Supported smart devices:
  - Light
  - Thermostat
  - Air Conditioner (AC)
  - Camera
  - Door Lock
- Remote control of devices (ON/OFF and actions)
- Device scheduling using time
- Energy usage monitoring and reports
- Notification system for important events
- File handling for saving and loading system data
- Exception handling for error management

---

## OOP Concepts Used
- Classes and Objects  
- Inheritance  
- Polymorphism  
- Encapsulation  
- Abstraction  
- Dynamic memory allocation  
- Exception handling  
- STL (vector, map)

---

## Technologies Used
- Programming Language: **C++**
- Compiler: **GCC / g++**
- Concepts: OOP, File Handling, STL

---

## How to Compile and Run

### Compile
```bash
g++ main.cpp -o SmartHome
```

### Run
```bash
./SmartHome
```

> Ensure that the source file is named `main.cpp` or update the command accordingly.

---

## Project Structure
- `main.cpp` – Contains all classes and the main program logic  
- `data.txt` – Stores user, room, and device data (automatically created)

---

## How the System Works
1. User registers an account
2. User logs in
3. Rooms are added to the smart home
4. Devices are added to rooms
5. Devices can be controlled remotely
6. Devices can be scheduled to run at specific times
7. Energy usage is tracked and reported
8. All data is saved automatically

---

## Menu Options
- Register
- Login
- Add Room
- Add Device
- View Devices
- Dashboard
- Remote Device Control
- Scheduling
- Energy Report
- Notifications
- Exit

---

## Notes
- Password must be at least **6 characters** and contain **at least one digit**
- This project is **console-based**
- Data persists between runs using file handling

---

## Author
- Name:Palwasha

---

