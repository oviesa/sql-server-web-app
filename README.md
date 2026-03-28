# SQL Server Web Application – Ticket Management System

## Project Overview

This project is a database-driven web application built using ASP.NET Core MVC and SQL Server. The application simulates a real-world support ticket workflow where users can create, view, update, and delete ticket records.

The purpose of this project is to demonstrate practical software engineering skills including database integration, CRUD operations, MVC architecture, and backend application development.

## Live Capabilities Demonstrated

This project demonstrates full-stack software development fundamentals including backend logic, database design, MVC architecture, and application workflow.

Key engineering concepts demonstrated:

• MVC architecture design  
• Database-driven application development  
• SQL data modeling  
• Entity Framework integration  
• Software documentation practices  
• Git version control workflow  

## Problem Statement

Many organizations require internal systems to track technical issues, support requests, and operational incidents. This project simulates a help desk ticket management system that allows structured tracking of requests and their resolution status.

## Technologies Used

### Backend
- C#
- ASP.NET Core MVC
- Entity Framework Core

### Database
- SQL Server Express
- SQL Server Management Studio (SSMS)

### Frontend
- HTML
- CSS
- Bootstrap
- Razor Views

### Tools
- Visual Studio
- GitHub

## Features

### Core Functionality

• Create new support tickets  
• View ticket records in a structured table  
• Update ticket information  
• Delete ticket records  
• Store ticket data in SQL Server  

### Technical Features

• ASP.NET Core MVC architecture  
• Entity Framework database integration  
• SQL Server relational database design  
• Razor view rendering  
• Bootstrap responsive UI  
• Local development environment setup  

## Architecture

### Application Flow

Browser  
↓  
ASP.NET MVC Controllers  
↓  
Entity Framework Core  
↓  
SQL Server Database  
↓  
Data returned to Razor Views  

### Architecture Pattern

Client → MVC Application → Data Layer → SQL Server

## Database Schema

### Tickets Table

| Column | Data Type | Description |
|--------|-----------|-------------|
| TicketID | int (PK) | Unique ticket identifier |
| Title | nvarchar | Ticket title |
| Description | nvarchar | Ticket details |
| Priority | nvarchar | Low / Medium / High |
| Status | nvarchar | Open / Closed |
| CreatedDate | datetime | Ticket creation date |

## Example Use Case

A user creates a support ticket describing an issue. The ticket is stored in SQL Server and displayed in the ticket list. The ticket can later be edited or deleted as needed.

## Project Structure

```text
sql-server-web-app
│
├── README.md
├── LICENSE
├── .gitignore
├── sql
│ ├── create-database.sql
│ └── seed-data.sql
│
├── screenshots
│ ├── 01-homepage.png
│ ├── 02-create-ticket.png
│ ├── 03-ticket-list.png
│ ├── 04-database.png
│ └── 05-query.png
│
├── docs
│ └── schema-diagram.png
│
└── TicketSystemWebApp
```

## Setup Instructions

### Prerequisites

Install:

Visual Studio Community  
SQL Server Express  
SQL Server Management Studio  

### Steps to Run

1. Clone repository

2. Create database using SQL scripts located in:

sql/create-database.sql

3. Insert sample data using:

sql/seed-data.sql

4. Update connection string inside:

appsettings.json

Example:

Server=(localdb)\MSSQLLocalDB;
Database=TicketSystemDB;
Trusted_Connection=True;


5. Run project from Visual Studio

6. Navigate to:

/Tickets

## Screenshots

### Ticket List
![Ticket List](screenshots/01-ticket-list.png)

### Create Ticket Form
![Create Ticket](screenshots/02-create-ticket-form.png)

### Edit Ticket
![Edit Ticket](screenshots/03-edit-ticket.png)

### Database Table
![Database Table](screenshots/04-database-table.png)

### Query Results
![Query Results](screenshots/05-query-results.png)

## Development Highlights

• Implemented Entity Framework DbContext for database interaction  
• Generated MVC controllers using scaffolding  
• Implemented strongly-typed Razor views  
• Designed normalized SQL table structure  
• Implemented full CRUD workflow  
• Configured connection string management  

## Key Skills Demonstrated

• Database design  
• SQL query development  
• ASP.NET MVC development  
• CRUD implementation  
• Backend integration  
• Software architecture fundamentals  
• Debugging database connectivity  
• Application development workflow  

## Challenges I encountered

• Connecting ASP.NET application to SQL Server  
• Understanding MVC data flow  
• Managing database schema structure  
• Configuring Entity Framework  

## I Learned

• How MVC applications interact with databases  
• How CRUD operations function in production apps  
• The importance of database structure design  
• How backend and UI layers communicate  

## To improve, I should

• Add authentication system  
• Add user roles  
• Add ticket assignment  
• Add search functionality  
• Add dashboard analytics  
• Add REST API endpoints  
• Containerize application with Docker  
