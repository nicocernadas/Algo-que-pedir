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

https://github.com/user-attachments/assets/6e2f2cfa-a329-4722-a0ce-e7acdb4b4d98

_Demonstrates the user registration flow, including form validation, data submission to the back-end, and successful account creation._

User Preference Management

https://github.com/user-attachments/assets/4f3c1c48-9ff1-423c-a617-362e16fe4bd0

_Shows how a user can update personal preferences, with changes being persisted on the server and reflected in the application state._


Order Management with Live Reviews

https://github.com/user-attachments/assets/dee4ac73-5899-4429-954f-862336f5ddd6

_Illustrates the order management process from the store perspective, including order handling and real-time customer review updates._


Real-Time Order Synchronization Between Clients

https://github.com/user-attachments/assets/5f8e5ed0-4b25-4a4e-a412-ed7700bb6b96

_Demonstrates how order state changes are synchronized in real time between the user and store front-end applications through the back-end._


Dynamic Price Updates in Real Time

https://github.com/user-attachments/assets/47d1d809-eba4-4556-a040-226b8897327c

_Shows real-time price modifications performed by the store and their immediate propagation to connected user clients._

### Project Overview
The system is structured around a client-side architecture:

The front-end is a single-page application responsible for user interaction, data visualization, and client-side validation.

The back-end follows a layered architecture that separates controllers, services, and data access logic. This back-end exposes RESTful endpoints consumed by the front-end, handling business rules, validations, and persistence. Compared to the version developed in **Programming Algorithms II**, this iteration introduces structural improvements, cleaner abstractions, and better alignment with object-oriented and algorithmic principles discussed in the course.

Communication between the front-end and back-end is handled via HTTP using JSON as the data exchange format.
