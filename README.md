# CareTrack - Hospital Management System

## Overview
CareTrack is a Python-based application designed to streamline hospital operations. It utilizes a robust SQLite database to store records persistently. The system provides a clean Command Line Interface (CLI) for administrators and staff to manage hospital resources effectively.

## Features
•⁠  ⁠*CRUD Operations:* Create, Read, Update, and Delete records for Patients and Doctors.
•⁠  ⁠*Appointment Booking:* Link patients to doctors with specific time slots.
•⁠  ⁠*Data Integrity:* Uses SQL constraints to ensure valid data entry.
•⁠  ⁠*Modular Design:* logic is separated into distinct modules for scalability.
•⁠  ⁠*Validation:* Input checks to prevent empty or invalid data.

## Technologies Used
•⁠  ⁠*Language:* Python 3.x
•⁠  ⁠*Database:* SQLite3 (Embedded relational database)
•⁠  ⁠*Tools:* Git for version control.

## Installation & Run Steps
1.  *Clone the Repository:*
    ⁠ bash
    git clone [https://github.com/yourusername/caretrack.git](https://github.com/yourusername/caretrack.git)
    cd caretrack
     ⁠
2.  *Initialize Database:*
    The system automatically creates ⁠ hospital.db ⁠ on the first run.
3.  *Run the Application:*
    ⁠ bash
    python main.py
     ⁠

## Testing
•⁠  ⁠Run the application and select "Add Doctor" to create a staff member.
•⁠  ⁠Select "Add Patient" to register a user.
•⁠  ⁠Select "Book Appointment" to link them.
•⁠  ⁠Check ⁠ hospital.db ⁠ using any SQLite viewer to verify data storage.
