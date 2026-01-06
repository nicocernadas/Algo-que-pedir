# FINAL PROJECT - Programming Algorithms III

### Introduction
These projects were developed as the final assignment for the Programming Algorithms III course. The work consists of three tightly integrated components: two front-end applications: one developed using TypeScript and React, the other with Svelte. And a back-end service built with Kotlin and Spring Boot, which is an improved and extended version of the system originally developed for Programming Algorithms II.

The two front-end applications represent different interaction perspectives within the system: one is designed for store-level operations and management, while the other is oriented toward the end user. Both clients communicate with the same back-end service, consuming shared RESTful APIs while maintaining clearly separated responsibilities at the presentation layer.

The primary objective of this project was to apply theoretical concepts studied throughout the course in a real-world–oriented software system. This included algorithm design, data structures, abstraction, modularization, and clean architecture, combined with modern web development practices. The project emphasizes controlled interaction between multiple client applications and a centralized back-end through well-defined APIs, reinforcing key concepts such as separation of concerns, scalability, maintainability, and code reuse.

### Instructors
- Dodino Fernando
- Foglia Pablo

### Team members
- Cossettini Reyes Dana
- Andres Maximiliano
- Perez Fernanda
- Cernadas Nicolás
- Correa Catalina

### Project Samples
User Account Creation
[User Account Creation](media/Account_creation.mp4)
Demonstrates the user registration flow, including form validation, data submission to the back-end, and successful account creation.

User Preference Management
[User Preference Management](media/Preferences_update.mp4)
Shows how a user can update personal preferences, with changes being persisted on the server and reflected in the application state.

Order Management with Live Reviews
[Order Management with Live Reviews](media/Order_management_real_time_reviews.mp4)
Illustrates the order management process from the store perspective, including order handling and real-time customer review updates.

Real-Time Order Synchronization Between Clients
[Real-Time Order Synchronization Between Clients](media/Real_time_orders_synchronized.mp4)
Demonstrates how order state changes are synchronized in real time between the user and store front-end applications through the back-end.

Dynamic Price Updates in Real Time
[Dynamic Price Updates in Real Time](media/Real_time_price_changes.mp4)
Shows real-time price modifications performed by the store and their immediate propagation to connected user clients.

### Project Overview
The system is structured around a client-side architecture:

The front-end is a single-page application responsible for user interaction, data visualization, and client-side validation.

The back-end follows a layered architecture that separates controllers, services, and data access logic. This back-end exposes RESTful endpoints consumed by the front-end, handling business rules, validations, and persistence. Compared to the version developed in **Programming Algorithms II**, this iteration introduces structural improvements, cleaner abstractions, and better alignment with object-oriented and algorithmic principles discussed in the course.

Communication between the front-end and back-end is handled via HTTP using JSON as the data exchange format.
