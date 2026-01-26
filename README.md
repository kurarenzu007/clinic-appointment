# 🏥 Clinic Appointment System

![Project Status](https://img.shields.io/badge/Status-Academic%20Project-blue)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange)

A streamlined patient scheduling platform designed to digitize manual clinic processes. This system reduces appointment conflicts, manages patient records efficiently, and provides a seamless workflow for both clinic staff and patients.

## 📋 Table of Contents
- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Database Setup](#database-setup)
- [Usage](#usage)
- [Contact](#contact)

## 📖 About the Project

This project was developed as a requirement for **BSIT 3rd Year**. The primary goal was to solve the inefficiencies of manual/paper-based appointment setting in local clinics.

By automating the scheduling process, this system aims to:
* **Reduce waiting times** for patients.
* **Eliminate double-booking** conflicts (approx. 80% reduction).
* **Securely manage** patient health records.

## ✨ Key Features

* **📅 Online Appointment Booking:** Patients can view available slots and book appointments remotely.
* **👨‍⚕️ Admin Dashboard:** comprehensive view for staff to approve, reschedule, or cancel appointments.
* **📂 Patient Record Management:** Digital storage of patient history and basic information.
* **🔔 Real-time Status Updates:** (If applicable) Status tracking for pending, approved, and completed appointments.
* **🔐 Secure Authentication:** Role-based login for Admins and Patients.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Backend:** Node.js, Express.js
* **Database:** MySQL
* **Tools:** Visual Studio Code, XAMPP (for local MySQL), Git

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
* **Node.js** (v14 or higher) installed.
* **MySQL** installed (or XAMPP/WAMP).

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/kurarenzu007/clinic-appointment.git](https://github.com/kurarenzu007/clinic-appointment.git)
    cd clinic-appointment
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Configure Environment Variables**
    Create a `.env` file in the root directory and add your database credentials:
    ```env
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=
    DB_NAME=clinic_db
    PORT=3000
    ```

## 🗄️ Database Setup

1.  Open your MySQL tool (phpMyAdmin or Workbench).
2.  Create a new database named `clinic_db`.
3.  Import the provided SQL file:
    * Locate `database/clinic_db.sql` (or `schema.sql`) in this repository.
    * Import it into your new database to create the necessary tables.

## 🖥️ Usage

1.  **Start the server**
    ```bash
    npm start
    # or if using nodemon
    npm run dev
    ```

2.  **Access the application**
    Open your browser and navigate to:
    `http://localhost:3000`

## 👤 Author

**Clarence F. Felicilda**
* **Portfolio:** [Link](https://kurarenzu007.github.io/AnimalAdoption/)
* **GitHub:** [@kurarenzu007](https://github.com/kurarenzu007)
* **LinkedIn:** [Clarence Felicilda](https://linkedin.com/in/clarence-felicilda-13667728a)

---
*This project is for educational purposes.*
