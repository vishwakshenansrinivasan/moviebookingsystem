<div align="center">

# 🎬 CinemaSync: Movie Booking System

*A modern, intuitive, and feature-rich Python application for seamless movie reservations and management.*

[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blueviolet?style=for-the-badge&logo=python)](https://python.org)
[![Database](https://img.shields.io/badge/Database-MySQL%20%7C%20SQLite-informational?style=for-the-badge&logo=database)](https://mysql.com)
[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#)

</div>

<br />

---

## 🌟 Overview

The **Movie Booking System** is a lightweight yet comprehensive desktop application built in Python. Designed with both moviegoers and administrators in mind, it provides a smooth, user-friendly interface to browse available movies, select seats, and handle ticketing. For administrators, it offers robust management of shows, ticket pricing, and user reservations.

---

## ✨ Key Features

### 👤 User Module (`user_login.py`)
- **Secure Authentication:** Easy login and sign-up with credentials.
- **Seat Selection:** Interactive seat mapping for an intuitive booking experience.
- **Ticket Generation:** Instantly view and export digital tickets.
- **Booking History:** Keep track of past and upcoming reservations.

### 🛡️ Admin Panel (`adminfile.py`)
- **Movie Management:** Add, update, or remove movies and showtimes seamlessly.
- **Theatre Control:** Adjust seating capacity and theater layouts.
- **Revenue Tracking:** Integrated sales reports and booking overviews.
- **Data Structuring:** Robust database structures implemented via `Database Structures`.

### 🎛️ Unified Dashboard (`mainpage.py`)
- **Clean UI/UX:** A modern layout displaying current and upcoming movies.
- **Fast Search:** Find movies by title, genre, or showtime effortlessly.

---

## 🛠️ Tech Stack & Technologies

- **Language:** Python
- **GUI Framework:** *Tkinter / PyQt*
- **Data Persistence:** Database handling via local DB connections (schemas in `Database Structures`).
- **Design:** Modern layout with structured modules.

---

## 📂 Project Structure

```text
📁 moviebookingsystem
├── adminfile.py          # Admin interface & management logic
├── mainpage.py           # Core application dashboard
├── user_login.py         # User authentication & registration
├── Database              # Raw database files & configuration
├── Database Structures   # SQL schemas and table definitions
└── README.md             # Project documentation (You are here!)
```

---

## 🚀 Getting Started

Follow these steps to run the movie booking system locally:

### 1. Prerequisites
Ensure you have Python 3.8+ installed. You may also need a local database server if you're using MySQL.

### 2. Clone the Repository
```bash
git clone https://github.com/vishwakshenansrinivasan/moviebookingsystem.git
cd moviebookingsystem
```

### 3. Setup the Database
1. Check the `Database Structures` file to view the required database schemas.
2. Initialize the database locally.
3. Verify connection settings in the source code.

### 4. Run the Application
Start the program by launching the main page:
```bash
python mainpage.py
```

---

## 💡 Navigating the Application

1. **Start Screen:** On launching `mainpage.py`, you can choose to login as a User or an Admin.
2. **User Flow:** Navigate to the `user_login.py` logic. After authentication, browse movies, select your showtime, pick your seats, and complete your reservation!
3. **Admin Flow:** Navigate to the `adminfile.py` logic. Enter your admin credentials to access scheduling, pricing, and analytics.

---

## 🎨 Visuals & Screenshots

*(Placeholder for UI screenshots. Be sure to add visual captures of your application here once the GUI is finalized to showcase your aesthetic design!)*

| Main Dashboard | Seat Selection | Admin Panel |
|:---:|:---:|:---:|
| <img src="https://via.placeholder.com/300x200/1e1e2e/cdd6f4.png?text=Main+Dashboard" alt="Main Dashboard" width="300" /> | <img src="https://via.placeholder.com/300x200/1e1e2e/cdd6f4.png?text=Seat+Selection" alt="Seat Selection" width="300" /> | <img src="https://via.placeholder.com/300x200/1e1e2e/cdd6f4.png?text=Admin+Panel" alt="Admin Panel" width="300" /> |

---

## 🤝 Contributing

Contributions make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

<br />

<div align="center">
  <b>Built with ❤️ by Vishwakshenan S</b>
</div>