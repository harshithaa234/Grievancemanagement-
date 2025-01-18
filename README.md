# Grievance Management System

## Introduction
The **Grievance Management System** is designed to streamline the process of handling user grievances in a structured and efficient manner. Built using **Java**, **PostgreSQL**, and **Swing**, this application provides a user-friendly interface for both users and administrators. The system supports secure user registration, grievance submission, and an admin dashboard for effective grievance management.

---

## Features

### User Functionality:
1. **Signup and Login**: Users can securely register and log in to access the system.
2. **Grievance Submission**: 
   - Submit grievances by providing details like name, email, contact, and description.
   - Ensure validation for required fields, email format, and contact details.

### Admin Functionality:
1. **View Grievances**: 
   - Admins can view all submitted grievances.
   - The data includes user details and grievance descriptions.
2. **Update Status**:
   - Update grievance statuses to "Pending," "In Progress," or "Resolved."
3. **Delete Grievances**: Remove grievances that are no longer relevant or have been resolved.

---

## Technologies Used

- **Programming Language**: Java (JDK 22.0.1)
- **Database**: PostgreSQL 15 (via PGAdmin)
- **UI Framework**: Swing
- **IDE**: Apache NetBeans IDE 22
- **Database Connector**: PostgreSQL JDBC Driver (v42.5.4)

---

## Database Design

The system uses a PostgreSQL database with the following tables:

1. **Users Table**:
   - Fields: `Name`, `Email`, `Password`, `Role`
   - Purpose: Stores user details and login credentials.

2. **Grievances Table**:
   - Fields: `Name`, `Email`, `Contact`, `Description`, `Status`
   - Purpose: Tracks user grievances with relevant details and status.

---

## Workflow

### 1. User Workflow:
- **Step 1**: User signs up with their details.
- **Step 2**: User logs in to the system.
- **Step 3**: User submits grievances via a form.
- **Step 4**: User views their submitted grievances and their statuses.

### 2. Admin Workflow:
- **Step 1**: Admin logs in to access the dashboard.
- **Step 2**: Admin views all grievances in a tabular format.
- **Step 3**: Admin updates the status of grievances or deletes them as necessary.

---

### Conclusion

The Grievance Management System is a robust solution for managing grievances efficiently. By providing secure user authentication, streamlined grievance submission, and a powerful admin dashboard, the system fosters accountability and transparency. With future enhancements like role-based access, email notifications, and analytics, this project can scale to meet the needs of various organizations.
