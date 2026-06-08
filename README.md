# Procurement Management System

## Project Overview

The Procurement Management System is a web-based inventory management application developed to help organizations manage products, suppliers, stock levels, and procurement activities through a centralized platform.

The system digitizes inventory operations by maintaining product records, tracking stock availability, managing supplier information, and recording purchase orders. It reduces manual record keeping and provides better visibility into inventory movement and procurement activities.

The platform is designed for small and medium-scale businesses that require a simple and efficient solution for inventory control and procurement management.

---

## Objective

To develop a centralized Procurement Management System that simplifies inventory tracking and procurement operations.

The system aims to:

* Maintain product inventory records.
* Manage supplier information.
* Monitor stock availability.
* Record procurement transactions.
* Generate inventory reports.
* Reduce manual data entry.
* Improve inventory visibility.
* Support better procurement decisions.

---

## Problem Statement

Many organizations still manage inventory and procurement activities using spreadsheets, notebooks, and manual registers.

This approach often leads to:

* Duplicate product records.
* Inaccurate stock information.
* Delayed procurement decisions.
* Difficulty in tracking supplier transactions.
* Inventory shortages and overstocking.
* Manual reporting efforts.
* Increased chances of human error.

The absence of a centralized inventory management platform affects operational efficiency and inventory accuracy.

This project addresses these challenges by providing a digital procurement and inventory management solution.

---

## User & Module Identification

The Procurement Management System is designed for inventory administrators and store managers who are responsible for managing stock and procurement activities.

Users interact with the system through a web interface to maintain inventory records, supplier details, purchase orders, and reports.

### Modules List

* Authentication Module
* Product Management Module
* Supplier Management Module
* Inventory Management Module
* Purchase Order Management Module
* Dashboard & Reporting Module

---

## System Use Case Overview

![System Overview](docs/images/system-overview.png)

---

## Module Breakdown

![Module Breakdown](docs/images/module-breakdown.png)

---

## Entity Relationship Diagram (ER Diagram)

![ER Diagram](er-diagram.png)

---

## Technology Stack

### Frontend

* HTML
* CSS
* Bootstrap
* JavaScript

### Backend

* Spring Boot (Java)

### Database

* PostgreSQL

### Development Tools

* VS Code
* GitHub
* Postman

---

## Database Entities

### User

* User ID
* Name
* Email
* Password
* Role

### Product

* Product ID
* Product Name
* Category
* Unit Price
* Quantity

### Supplier

* Supplier ID
* Supplier Name
* Contact Details

### Inventory

* Inventory ID
* Product ID
* Stock Quantity

### Purchase Order

* Purchase Order ID
* Supplier ID
* Order Date
* Status

### Purchase Order Item

* Item ID
* Purchase Order ID
* Product ID
* Quantity

---

## Future Enhancements

* Barcode Integration
* QR Code Tracking
* Email Notifications
* Mobile Application
* Inventory Forecasting
* Advanced Analytics Dashboard
