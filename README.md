# Fitness Center Management System

A relational database management system built with **MySQL** to manage the core operations of a fitness center, including members, employees, trainers, classes, equipment, memberships, and facility-related information.

## Overview

The **Fitness Center Management System** is a database-focused project designed to demonstrate the design and implementation of a structured relational database for a fitness center.

The system provides a centralized way to manage and maintain information related to:

* Fitness center members and their memberships
* Employees and trainers
* Fitness classes and schedules
* Gym equipment and facilities
* Other operational data required to support fitness center management

The project focuses primarily on **database design, SQL development, data integrity, automation, and performance optimization** using MySQL.

## Objectives

The primary objectives of this project are to:

* Design and implement a normalized relational database for a fitness center.
* Maintain accurate and consistent member information.
* Manage membership details and related records.
* Maintain employee and trainer information.
* Manage fitness classes and schedules.
* Track gym equipment and other facilities.
* Enforce data integrity using database constraints and triggers.
* Automate recurring database operations using MySQL Events.
* Simplify data access through MySQL Views and Stored Procedures.
* Improve query performance through appropriate indexing strategies.

## Scope

The system is designed to support the following areas of fitness center management:

### Membership Management

* Store and manage member information.
* Maintain membership details and status.
* Track membership-related records.

### Employee & Trainer Management

* Maintain employee information.
* Manage trainer details and assignments.
* Associate trainers with fitness classes and activities.

### Class Management

* Maintain fitness class information.
* Manage class schedules.
* Track trainer and class relationships.

### Equipment & Facility Management

* Maintain information about gym equipment.
* Track equipment and facility-related data.
* Support ongoing management of fitness center resources.

## Database Features

The project demonstrates several core MySQL database capabilities:

| Feature               | Purpose                                                                                              |
| --------------------- | ---------------------------------------------------------------------------------------------------- |
| **MySQL Views**       | Provide reusable and simplified access to commonly queried data                                      |
| **Stored Procedures** | Encapsulate reusable database operations and business logic                                          |
| **Triggers**          | Automatically enforce business rules and maintain data consistency                                   |
| **Events**            | Automate scheduled database operations                                                               |
| **Indexes**           | Improve query performance for frequently accessed data                                               |
| **Relational Design** | Establish relationships between members, employees, trainers, classes, equipment, and other entities |

## Technology Stack

* **Database:** MySQL
* **Database Management Tool:** phpMyAdmin
* **Language:** SQL
* **Version Control:** Git / GitHub

## Development Environment

The database was developed and tested using **phpMyAdmin**.

The SQL database script included in this repository should be executed through phpMyAdmin or another MySQL-compatible database client.

> **Note:** The project was developed using phpMyAdmin. Make sure a compatible MySQL server is running before executing the SQL script.

## Project Structure

```text
Fitness-Center-Management-System/
│
├── README.md
├── *.sql
└── ...
```

The SQL file contains the database schema, tables, relationships, and database objects required to set up the Fitness Center Management System.

## PROJECT ENVIRONMENT
 
The project environment for the Fitness Center Management database will be phpMyAdmin (https://www.phpmyadmin.net/) using the Cloud9 development workspace in the cloud. 
The phpMyadmin will provide the interface for MySQL database management system through which data storage, retrieval and operations can be performed. 
Cloud9 is the best option as all team members already have an account and have the knowledge in how to perform operations in this application.

## Getting Started

### Prerequisites

Before running the project, ensure you have:

* MySQL Server
* phpMyAdmin or another MySQL-compatible database client
* Git (optional, for cloning the repository)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/akshayKarai/Fitness-Center-Management-System.git
```

2. Open **phpMyAdmin**.

3. Create or select the MySQL database where the project will be deployed.

4. Open the **Import** section in phpMyAdmin.

5. Select the project's `.sql` file.

6. Execute the SQL script.

7. Verify that the required tables, relationships, views, stored procedures, triggers, events, and indexes have been created successfully.

## Application Vision

The vision of this project is to create a centralized fitness center management system that enables fitness centers to efficiently maintain information related to **memberships, employees, trainers, classes, schedules, equipment, and facilities**.

By organizing this information within a relational database, the system aims to improve data consistency, simplify information management, and provide a foundation for future application development.

## Development Approach

The project is planned and implemented across **three development sprints**.

Each sprint focuses on a specific set of database requirements and includes corresponding user stories and implementation tasks.

### Sprint 1

Focuses on the foundational database design, including the identification of entities, relationships, tables, and core membership and employee functionality.

### Sprint 2

Expands the system with additional fitness center functionality, including trainers, classes, equipment, and related relationships.

### Sprint 3

Focuses on advanced MySQL functionality such as:

* Views
* Stored Procedures
* Triggers
* Events
* Indexes
* Database optimization and integrity

Detailed user stories and sprint-specific implementation details can be added to the corresponding project documentation.

## Key Learning Outcomes

This project demonstrates practical experience with:

* Relational database design
* Entity relationships and normalization
* SQL data definition and manipulation
* MySQL Views
* Stored Procedures
* Database Triggers
* MySQL Events
* Indexing and query optimization
* Data integrity and business rules
* Database administration using phpMyAdmin
* GitHub-based project management

## Future Enhancements

Potential future enhancements include:

* Develop a web-based user interface.
* Build REST APIs for database operations.
* Add authentication and role-based access control.
* Implement member check-in and check-out functionality.
* Add payment and billing management.
* Add attendance tracking.
* Implement reporting and analytics dashboards.
* Integrate notifications for memberships, classes, and payments.
* Deploy the database and application to a cloud environment.

## Repository

**GitHub:**
https://github.com/akshayKarai/Fitness-Center-Management-System

## License

This project is intended for educational and portfolio purposes.
