<div align="center">

# 🚆 IRCTC Railway Reservation System

### ✨ A Modern Java Console-Based Railway Ticket Booking Application

![Java](https://img.shields.io/badge/Java-17+-orange?style=for-the-badge&logo=java)
![OOP](https://img.shields.io/badge/OOP-Design-blue?style=for-the-badge)
![Console](https://img.shields.io/badge/UI-Interactive%20Console-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

</div>

---

## 📖 Overview

The **IRCTC Railway Reservation System** is a Java-based console application that simulates the core functionalities of a railway ticket booking platform. It provides an interactive terminal interface for searching trains, booking tickets, checking PNR status, and managing reservations while following Object-Oriented Programming principles.

This project was developed to strengthen concepts such as **Java Programming, OOP, Collections Framework, Service-Based Architecture, and Real-World Application Design**.

---

## ✨ Features

### 🔍 Train Search
- Search trains by **Source** and **Destination**
- View all available stations
- Search trains using Train Number
- Display complete train details
- Sort trains by:
  - 💰 Fare
  - ⏰ Departure Time

### 🎟️ Ticket Booking
- Book seats instantly
- Dynamic seat availability management
- Fare calculation based on seat count
- Passenger information management
- Booking confirmation summary

### 📌 PNR Management
- Auto-generated unique PNR number
- Track booking status
- View complete ticket information

### ❌ Ticket Cancellation
- Cancel booked tickets
- Automatic seat restoration
- Refund information display

### 🎨 Interactive Console UI
- ANSI Colored Terminal Interface
- Professional Dashboard Layout
- Styled Railway E-Ticket Generation
- User-Friendly Navigation Menus

---

## 🏗️ Project Structure

```text
IRCTC-Railway-Reservation-System
│
├── IRCTCMain.java          # Application Entry Point
├── SearchService.java      # Train Search Operations
├── BookingService.java     # Booking & Cancellation Logic
├── Booking.java            # Booking Model & Ticket Generation
├── Train.java              # Train Entity
├── TrainDatabase.java      # In-Memory Train Database
│
└── README.md
```

---

## ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ☕ Java | Core Development |
| 🧩 OOP | Design Principles |
| 📚 Collections Framework | Data Management |
| 🖥️ Console Interface | User Interaction |
| 🔄 UUID | PNR Generation |

---

## 🚀 How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/IRCTC-Railway-Reservation-System.git
```

### 2️⃣ Navigate to Project

```bash
cd IRCTC-Railway-Reservation-System
```

### 3️⃣ Compile

```bash
javac src/*.java -d out
```

### 4️⃣ Run

```bash
java -cp out project_1.IRCTCMain
```

---

## 🖥️ Sample Workflow

```text
Main Menu
│
├── Search Trains
│      ├── Search by Route
│      ├── View Stations
│      └── Train Details
│
├── Book Ticket
│      ├── Select Train
│      ├── Enter Passenger Details
│      └── Generate PNR
│
├── Check PNR Status
│
└── Cancel Ticket
```

---

## 📸 Highlights

✅ Train Search System  
✅ Dynamic Seat Allocation  
✅ Unique PNR Generation  
✅ Ticket Cancellation & Refund Logic  
✅ Modular Service Architecture  
✅ Clean Object-Oriented Design  
✅ Beautiful Console Interface  

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Object-Oriented Programming (OOP)
- Java Collections Framework
- Service-Based Application Design
- Real-World Reservation System Logic
- Data Validation & User Interaction
- Clean Code Practices

---

## 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

```bash
Fork ➜ Create Branch ➜ Commit Changes ➜ Open Pull Request
```

---

<div align="center">

### 🚆 Built with Java & Passion for Learning

⭐ If you like this project, consider giving it a star!

</div>