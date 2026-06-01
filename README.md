🏫 Smart Campus Resource System

A centralized web-based campus management platform designed to streamline resource booking, maintenance handling, and communication between users, administrators, and technicians within a university environment.

🚀 Overview

The Smart Campus Resource System enables efficient management of university facilities such as lecture halls, auditoriums, and other resources. It also provides a structured workflow for booking approvals, maintenance ticketing, and role-based user management.

The system is designed with role-based access control (RBAC) to ensure secure and structured operations across different user types: Admin, User, and Technician.

✨ Key Features
📍 Resource Management (Admin)
Add, update, and remove campus locations
Manage resource types (lecture halls, auditoriums, labs, etc.)
Maintain centralized availability of university facilities
📅 Booking Management
Users can view available campus resources
Create booking requests for selected time slots
Admin reviews all active bookings
Admin can approve or reject booking requests
Users receive real-time status updates
🔔 Notifications System
Automated notifications for:
Booking approval/rejection
Ticket status updates
Maintenance completion
Users can view, read, and dismiss notifications
🛠 Maintenance & Ticketing System
Users can submit issue tickets (e.g., equipment failure, room issues)
Admin reviews and assigns tickets
Technicians can:
Log in/register
View assigned tickets
Resolve reported issues
Update ticket status upon completion
Users get notified when issues are resolved
👥 User Management (Admin)
View all registered users
Assign or modify user roles:
User
Technician
Admin
Full control over system access and permissions
🔐 Authentication & Authorization
Secure login and registration system
Role-based access control (RBAC)
Protected routes based on user roles
🧑‍💻 User Roles
👤 User
Book campus resources
Submit maintenance tickets
Receive notifications
🛠 Technician
View assigned tickets
Update maintenance status
Resolve reported issues
🧑‍💼 Admin
Manage resources and locations
Approve/reject bookings
Assign roles to users
Manage tickets and technicians
Monitor system activity
🏗 System Architecture

The system follows a modular architecture:

Frontend: User interface for interaction (React / Angular / etc.)
Backend: RESTful API handling business logic
Database: Stores users, bookings, resources, and tickets
Authentication Layer: Secure role-based access control
🔄 Workflow Summary
Admin adds campus resources
User browses and submits booking request
Admin approves/rejects booking
Notification sent to user
User submits maintenance tickets if needed
Admin assigns technician
Technician resolves issue
User gets completion notification
🧰 Tech Stack (Example - update if needed)
Frontend: React.js / Angular
Backend: Node.js / Spring Boot
Database: MongoDB / MySQL
Authentication: JWT / OAuth2
Styling: Tailwind CSS / Bootstrap
Communication: REST APIs
