# OOPS_Hospital_Management_System

# 🏥 Hospital Management System

## Overview

Hospitals encounter significant challenges when it comes to the manual management and monitoring of patient data. Dealing with manual data often leads to mistakes and slow processes. This Hospital Management System is designed to streamline administrative tasks, reduce reliance on paper-based processes, and enhance the quality of patient care.

This system offers two interfaces:

- **Doctor Login**
- **Staff Login**

By developing a User-Friendly Graphical User Interface (GUI) using the Swing framework and integrating with the MySQL database via JDBC, this system aims to improve hospital efficiency and the overall patient experience.

## 📋 Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Functionality](#functionality)
7. [Database Integration](#database-integration)
8. [Contributing](#contributing)
9. [License](#license)

## 🌟 Features

- **User Interfaces:** Separate interfaces for doctors and staff to streamline different administrative tasks.
- **Appointment Scheduling:** Simplified process for scheduling patient appointments.
- **Data Management:** Ability to add, view, and update patient, doctor, staff, and test data.
- **Billing:** Generate bills based on the duration of patient admission.
- **Database Integration:** Secure and reliable interaction with a MySQL database through JDBC.

## 🛠 Technologies Used

- **Java Spring Boot:** Backend framework for building the application.
- **Java Swing:** Frontend framework for developing the graphical user interface.
- **MySQL:** Database for storing hospital management data.
- **JDBC:** API for database connectivity.
- **Maven:** Dependency management and build automation tool.

## 🚀 Usage

### Doctor Login
- Doctors can log in to their dedicated interface.
- Access patient information, update patient records, and manage appointments.

### Staff Login
- Staff members can log in to their dedicated interface.
- Manage patient admissions, appointments, and handle billing tasks.

## 📂 File Structure

The repository contains the following main files and directories:

- `Adddoctor.java`
- `Addpatient.java`
- `Addstaff.java`
- `Addtest.java`
- `Appointment.java`
- `Bill.java`
- `carewell_collage.java`
- `Connectiondb.java`
- `Doctordashboard.java`
- `hmsproject.java`
- `HospitalManagementSystem.java`
- `Staffdashboard.java`
- `Updatedoctor.java`
- `Updatepatient.java`
- `Updatestaff.java`
- `Viewappoint.java`
- `Viewdoctor_1.java`
- `Viewpatient.java`
- `Viewstaff.java`
- `viewtest.java`

## 🔧 Functionality

### Graphical User Interface (GUI)

1. **Login Page:**
   - The user can log in as either a doctor or a staff member.

2. **Doctor Interface:**
   - Access and manage patient records.
   - View and schedule appointments.

3. **Staff Interface:**
   - Manage patient admissions and discharges.
   - Handle billing and generate invoices.
   - Update and manage staff records.

### MySQL Database Integration

1. **Connecting to the Database:**
   - The system employs Java Database Connectivity (JDBC) to connect to the MySQL database.

2. **CRUD Operations:**
   - **Add Data:** Insert new records into the database (e.g., patients, doctors, staff, tests).
   - **View Data:** Retrieve and display records from the database.
   - **Update Data:** Modify existing records in the database.
   - **Delete Data:** Remove records from the database (if implemented).

3. **Billing:**
   - Generate bills based on the duration of patient admission and other criteria.
