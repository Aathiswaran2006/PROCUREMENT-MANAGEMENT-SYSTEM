# Crowdsourced Civic Issue Reporting and Resolution System

---

# Project Overview

The Crowdsourced Civic Issue Reporting and Resolution System is a web-based platform that enables citizens to report public issues such as road damage, garbage accumulation, water leakage, streetlight failures, and sanitation problems directly to responsible authorities.

The system provides a centralized platform for issue submission, tracking, verification, and resolution. Citizens can upload issue details along with images and location information, while authorities can monitor complaints, update statuses, and notify users regarding progress.

The platform aims to improve communication between citizens and government departments, reduce response times, and increase transparency in civic issue management.

---

# Objective

To develop a centralized Civic Issue Reporting System that simplifies issue reporting and resolution processes.

The system aims to:

- Enable citizens to report civic issues online.
- Allow authorities to track and manage complaints.
- Provide real-time status updates.
- Improve transparency in complaint resolution.
- Reduce manual complaint handling.
- Support image-based issue reporting.
- Enhance citizen engagement.
- Generate reports for monitoring civic services.

---

# Problem Statement

Many civic issues remain unresolved because citizens lack a proper platform to report them directly to authorities.

Current complaint handling methods often result in:

- Delayed issue resolution.
- Lack of transparency.
- Poor communication between citizens and authorities.
- Difficulty tracking complaint status.
- Manual record maintenance.
- Duplicate complaints.
- Inefficient monitoring.

The absence of a centralized complaint management platform affects public service quality and citizen satisfaction.

This project addresses these challenges through a digital civic issue reporting and resolution platform.

---

# User & Module Identification

The system is designed for Citizens, Government Authorities, and Administrators who are responsible for reporting, monitoring, and resolving civic issues.

Users interact through a web interface to submit complaints, track issue status, receive notifications, and manage complaint records.

---

# Modules List

- Authentication Module
- Complaint Management Module
- Category Management Module
- Authority Management Module
- Status Tracking Module
- Notification Management Module
- Dashboard & Reporting Module

---

# System Use Case Overview

The Use Case Diagram illustrates interactions between Citizens and Authorities within the Civic Issue Reporting System.

![System Use Case Diagram](files/civic_use_case_diagram.png)

---

# Database Requirement Analysis

The system requires a centralized relational database to store users, complaints, categories, authorities, notifications, and status updates.

The database ensures proper issue tracking, status monitoring, and communication between citizens and government departments.

---

# Table List

| Table Name | Description |
|------------|-------------|
| User | Stores citizen and authority information |
| Complaint | Stores complaint details |
| Category | Stores issue categories |
| Authority | Stores department details |
| Status_Update | Stores complaint progress history |
| Notification | Stores user notifications |

---

# Entity Relationship Diagram (ER Diagram)

The ER Diagram represents relationships between users, complaints, authorities, notifications, and complaint status updates.

![ER Diagram](files/civic_er_diagram.png)

---

# Database Schema

The database schema defines primary keys, foreign keys, and relationships required for complaint management and tracking.

![Database Schema](files/civic_database_schema.png)

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
- Contact Details

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

# Future Enhancements

- Mobile Application Support
- GPS-Based Complaint Mapping
- AI-Based Issue Classification
- Multi-Language Support
- SMS Notifications
- Complaint Priority Prediction
- Department Performance Analytics
- Public Issue Heatmaps

---

# License

This project is developed for Smart India Hackathon (SIH 2025) academic and learning purposes.

---
