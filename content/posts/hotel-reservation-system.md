---
title: "Hotel Reservation System"
date: '2025-08-15T02:35:00-05:00'
draft: false
summary: "A desktop hotel booking and front-desk management application built with JavaFX, SQLite, and Maven. Structured using MVC and DAO patterns to separate self-service guest kiosk operations from administrative room assignment, billing, and check-out workflows."
tags: ["Java", "JavaFX", "SQLite", "Maven", "Desktop App"]
---

## Overview

Hotel Reservation System is a desktop application I built at Seneca Polytechnic to streamline hotel booking and front-desk management. The app separates the user experience into two distinct workflows: a self-service kiosk where guests can check room availability, book stays, modify reservations, and submit feedback, and an admin dashboard where staff can authenticate, assign rooms, process check-ins and check-outs, and generate itemized bills.

## Technologies Used

- **Java & JavaFX (FXML)** – Core application logic and multi-screen desktop user interface
- **SQLite (`sqlite-jdbc`)** – Embedded relational database for persistent storage
- **Apache Maven** – Dependency management and build automation

## Project Highlights

- Designed a dual-interface desktop application separating guest kiosk self-service from administrative staff controls.
- Structured the codebase around the MVC (Model-View-Controller) and DAO (Data Access Object) patterns for clean separation of concerns.
- Built a normalized SQLite relational schema with foreign key constraints and JDBC `PreparedStatement` queries to prevent SQL injection.
- Implemented room availability checks and admin-driven room assignment across 4 room types (`SINGLE`, `DOUBLE`, `DELUXE`, `PENTHOUSE`).
- Built reservation lookup by guest phone number, with each booking exposing a unique Reservation ID that drives all follow-up operations (modify, cancel, check-out).
- Implemented discount-supported billing where the final charge is calculated as total amount minus discount, with centralized activity/exception logging.

## What I Learned

This project gave me practical experience designing a multi-screen desktop application from scratch and connecting JavaFX controllers to a relational database. Structuring the project with DAO classes taught me how to keep SQL queries isolated from UI logic, making debugging and adding features like billing and feedback forms much cleaner.

## Links

- [GitHub Repository](https://github.com/Jungkyuu/HotelReservationSystem)