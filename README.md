
# DineMaster Restaurant Management System

Welcome to the DineMaster Restaurant Management System! This project is an individual effort to design and implement a custom authentication and authorization system that supports multiple authentication methods (e.g., OAuth, JWT, LDAP) and role-based access control for restaurant management.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Key Components](#key-components)
  - [Authentication and Authorization](#authentication-and-authorization)
  - [Backend](#backend)
  - [Frontend](#frontend)
- [Project Roles](#project-roles)
  - [Admin](#admin)
  - [Customer](#customer)
- [User Interfaces](#user-interfaces)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Conclusion](#conclusion)

## Introduction

DineMaster is a comprehensive restaurant management application where users can make table reservations and order food items. Admins can add menu items and categories to the website.

## Features

- **User Authentication and Authorization**: Supports multiple authentication methods including OAuth, JWT, and LDAP.
- **Role-Based Access Control**: Different functionalities for admin and customer roles.
- **Admin Features**:
  - Add and manage menu items.
  - Add and manage categories.
- **Customer Features**:
  - Make table reservations.
  - Order food items.

## Tech Stack

- **Java**
- **Spring Boot**
- **Hibernate**
- **Thymeleaf**
- **H2 Database**

## Project Structure

The project is structured to follow the best practices in software design, including the use of design patterns and proper separation of concerns.

## Key Components

### Authentication and Authorization

- **OAuth**: For social logins.
- **JWT (JSON Web Tokens)**: For stateless authentication.
- **LDAP (Lightweight Directory Access Protocol)**: For directory-based authentication.
- **Role-Based Access Control**: Ensures that only authorized users can access specific features.

### Backend

- **Spring Boot**: Provides the framework for building the application.
- **Hibernate**: Manages the database interactions.
- **H2 Database**: Serves as the in-memory database for development and testing purposes.

### Frontend

- **Thymeleaf**: Used for server-side rendering of HTML pages.

## Project Roles

### Admin

Admins have the ability to manage the restaurant's offerings. This includes adding new menu items and categories.

### Customer

Customers can browse the menu, make table reservations, and place food orders.

## User Interfaces

- **Home Page**: The landing page for the application, showcasing available menu items and categories.
- **Admin Page**: Accessible only by authorized admins to manage menu items and categories.
- **Login and Register Pages**: For user authentication and account creation.
- **Reservation and Order Page**: Allows customers to make reservations and order food items.

## Getting Started

### Prerequisites

- Java 11 or later
- Maven

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/dinemaster.git
   ```
2. Navigate to the project directory:
   ```bash
   cd dinemaster
   ```
3. Build the project:
   ```bash
   mvn clean install
   ```

### Running the Application

1. Run the application:
   ```bash
   mvn spring-boot:run
   ```
2. The application will be available at `http://localhost:8080`.

## Conclusion

Thank you for reviewing the DineMaster project. This restaurant management system is designed to provide a seamless experience for both customers and administrators, leveraging the power of Java and related frameworks to deliver robust functionality. For any further information or contributions, please refer to the project's repository.

---

Feel free to contact us for any questions or support.

Happy Dining with DineMaster!
