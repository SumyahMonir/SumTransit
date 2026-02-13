# SumTransit

SumTransit is a web-based transportation and logistics management platform developed as part of a university Software Development course. The system integrates ride booking, goods delivery, and plane ticket reservation into a single platform with structured role-based access control.

This project demonstrates full-stack web development using Django, with a strong focus on backend architecture, database design, authentication workflows, and dynamic data handling.

---

## Project Objective

The goal of SumTransit is to design and implement a centralized service platform where:

* Customers can book rides and delivery services.
* Riders can register and manage their services.
* Administrators can monitor and control platform operations.

The system simulates real-world transportation workflows, incorporating approval mechanisms, dashboard separation, and controlled access management.

---

## Technologies Used

**Frontend**

* HTML
* CSS
* JavaScript

**Backend**

* Python
* Django Framework

**Database**

* Django ORM (SQLite by default, configurable)

---

## System Architecture

The platform is built around three primary roles:

### User

* Account registration and authentication
* Ride booking
* Home-to-home delivery request
* Rider selection based on location and service fee
* Plane ticket booking

### Employee (Rider)

* Registration with vehicle details (Bike, Car, Bicycle)
* Access granted after admin approval
* Service fee management
* Availability management

### Admin

* Approval and verification of employee accounts
* User and rider management
* Platform-level oversight and control

---

## Technical Highlights

* Designed and implemented a role-based authentication and authorization system using Django’s built-in authentication framework.
* Developed complete CRUD functionality for users, employees, and service records.
* Integrated image upload and media handling for profile and vehicle data with proper backend validation.
* Implemented an approval workflow system where employee privileges are conditionally activated by admin authorization.
* Structured database models with relational mapping to maintain data integrity between users, vehicles, bookings, and services.
* Built dynamic dashboards with controlled access based on user roles.
* Implemented server-side data fetching and rendering using Django views and templates.
* Managed form validation, request handling, and secure data processing in the backend.

This project highlights practical experience with backend logic design, relational database handling, and structured web application development.


---

## Contributors

Developed by students of IIUC, 56th CSE Batch.

### Sumyah Monir Mithy

* Backend logic implementation
* Database design and integration
* CRUD operations
* Media handling (profile and vehicle images)
* Partial CSS implementation

### Sumaya Rahman

* Frontend design and UI implementation
* Testing
* Django project setup and configuration
* CSS, HTML

---

## Relevance for Software Engineering Internships

SumTransit reflects hands-on experience in:

* Backend development using Django
* Database schema design and ORM usage
* Role-based system architecture
* Authentication and access control implementation
* Full-stack integration between frontend and backend components

The project demonstrates practical understanding of structured application development, modular design, and scalable backend workflows, making it relevant for software engineering and backend development internship roles.


If you want, I can now make a slightly sharper version that subtly positions you stronger as the primary backend engineer (which helps a lot in internship screening).
