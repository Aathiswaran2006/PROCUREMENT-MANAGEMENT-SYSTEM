# Crowdsourced Civic Issue Reporting and Resolution System

## Project Overview

The Crowdsourced Civic Issue Reporting and Resolution System is a web-based platform that enables citizens to report civic problems such as potholes, garbage accumulation, drainage blockages, water leakages, broken streetlights, and other public infrastructure issues directly to the concerned authorities.

The platform provides a centralized mechanism for issue reporting, complaint management, authority assignment, status tracking, and resolution monitoring. It improves communication between citizens and local government departments while increasing transparency and accountability in civic administration.

The system is designed to support smart governance by encouraging public participation and enabling efficient issue resolution through digital technologies.

---

## Objective

To develop a centralized Civic Issue Reporting and Resolution System that simplifies issue reporting, complaint management, and resolution tracking.

The system aims to:

- Digitize civic issue reporting.
- Enable image-based complaint submission.
- Allow location-based issue tracking.
- Maintain centralized complaint records.
- Improve authority response time.
- Provide transparent complaint tracking.
- Reduce manual complaint management.
- Generate reports and analytics.
- Support smart city initiatives.

---

## Problem Statement

Many civic issues are still reported through phone calls, physical visits to government offices, and manual complaint registers.

This approach often leads to:

- Delayed complaint registration.
- Poor communication between citizens and authorities.
- Lack of transparency in complaint resolution.
- Difficulty tracking complaint status.
- Duplicate issue reporting.
- Slow response times.
- Manual paperwork and administrative overhead.
- Limited public participation.

The absence of a centralized civic issue management platform affects operational efficiency and public satisfaction.

This project addresses these challenges by providing a digital platform for reporting, monitoring, and resolving civic issues.

---

## User & Module Identification

The Crowdsourced Civic Issue Reporting and Resolution System is designed for Citizens, Government Authorities, and System Administrators.

Citizens can report civic problems and monitor their status, while authorities manage and resolve complaints through an administrative dashboard.

### Modules List

- Authentication Module
- Citizen Management Module
- Complaint Management Module
- Authority Management Module
- Issue Category Management Module
- Status Tracking Module
- Notification Module
- Dashboard & Reporting Module

---

# System Use Case Overview

![Use Case Diagram](Use_Case_Diagram.png)

The Use Case Diagram illustrates the interaction between Citizens, Authorities, and Administrators within the system.

Citizens can register, log in, report civic issues, upload supporting images, and track complaint status. Authorities can view complaints, assign issues, update progress, and resolve reported problems. Administrators manage users, categories, and system reports.

---

# Database Requirement Analysis

The system requires a centralized PostgreSQL database to store user information, complaint records, issue categories, authority details, notifications, and complaint status updates.

The database supports secure storage, complaint tracking, reporting, and efficient communication between stakeholders.

## Table List

| Table Name | Description |
|------------|-------------|
| Users | Stores citizen, authority, and admin accounts |
| Complaints | Stores issue reports submitted by citizens |
| Categories | Stores issue classification details |
| Authorities | Stores department information |
| Status_Updates | Stores complaint progress history |
| Notifications | Stores alerts and notifications |

---

# Entity Relationship Diagram (ER Diagram)

![ER Diagram](ER_Diagram.png)

The ER Diagram represents the relationships between users, complaints, authorities, categories, notifications, and status updates within the system database.

---

# Database Schema

The database schema is designed to maintain efficient relationships between system entities and support scalable complaint management operations.

### Main Relationships

- One User can submit multiple Complaints.
- One Category can contain multiple Complaints.
- One Complaint can have multiple Status Updates.
- One User can receive multiple Notifications.
- Authorities manage and resolve assigned Complaints.

---

# UI Wireframe Design

The system includes multiple user interfaces designed for different stakeholders.

### Planned Screens

- Home Page
- User Registration Page
- User Login Page
- Complaint Submission Page
- Complaint Tracking Page
- Authority Dashboard
- Admin Dashboard
- Reports Page

### Wireframe

_Add UI Wireframe Images Here_

---

# Login & Dashboard UI Design

The login and dashboard modules provide role-based access control and monitoring capabilities.

### Features

#### Citizen Dashboard

- Submit Complaints
- View Complaint Status
- Receive Notifications

#### Authority Dashboard

- View Assigned Complaints
- Update Complaint Status
- Resolve Issues

#### Admin Dashboard

- Manage Users
- Manage Categories
- Generate Reports

### Dashboard Screens

_Add Dashboard Screenshots Here_

---

# Navigation & Form Design

The system provides a user-friendly navigation structure for easy access to features.

### Navigation Flow

Home Page

↓

Login / Register

↓

Dashboard

↓

Complaint Management

↓

Status Tracking

↓

Reports

### Forms Included

- Registration Form
- Login Form
- Complaint Submission Form
- Status Update Form
- Category Management Form

---

# System Overview

![System Overview](System_Overview.png)

The System Overview Diagram presents the high-level architecture of the platform.

It shows the interaction between Citizens, Authorities, Application Server, Complaint Management Module, Notification Module, Dashboard Module, and Database.

---

# Module Breakdown

![Module Breakdown](Module_Breakdown.png)

The Module Breakdown Diagram illustrates the internal modules and their interactions.

### Authentication Module

- User Registration
- Login
- Role Management

### Complaint Management Module

- Issue Reporting
- Complaint Tracking
- Complaint History

### Authority Management Module

- Issue Assignment
- Status Updates
- Resolution Management

### Notification Module

- Email Alerts
- Complaint Status Notifications

### Dashboard Module

- Analytics
- Reports
- Statistics

### Administration Module

- User Management
- Category Management
- System Monitoring

---

# Technology Stack

## Frontend

- HTML
- CSS
- Bootstrap
- JavaScript

## Backend

- Spring Boot (Java)

## Database

- PostgreSQL

## Development Tools

- VS Code
- GitHub
- Postman
- pgAdmin

---

# Database Entities

## User

- User ID
- Name
- Email
- Password
- Role

## Complaint

- Complaint ID
- User ID
- Category ID
- Description
- Image URL
- Location
- Status
- Created Date

## Category

- Category ID
- Category Name

## Authority

- Authority ID
- Department Name
- Contact Information

## Status Update

- Update ID
- Complaint ID
- Status
- Remarks
- Updated Date

## Notification

- Notification ID
- User ID
- Message
- Created Date

---


