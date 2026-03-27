# SQL Server Web Application – Ticket Management System

## Overview

This project is a database-driven web application built with ASP.NET Core MVC and SQL Server. It was designed to simulate a real-world support ticket workflow where users can create, view, update, and delete ticket records.

The goal of this project is to demonstrate practical experience with:

- SQL Server database design
- CRUD operations
- ASP.NET Core MVC architecture
- Backend-to-database connectivity
- Form handling and validation
- Business-style web application development

## Problem Statement

Many organizations use internal systems to manage support issues, track requests, and monitor ticket status. This project simulates that workflow by providing a web-based ticket management system backed by SQL Server.

## Technologies Used

- ASP.NET Core MVC
- C#
- SQL Server Express / LocalDB
- Entity Framework Core
- HTML
- CSS
- Bootstrap
- Visual Studio

## Features

- Create new support tickets
- View all tickets in a structured table
- Edit existing ticket records
- Delete tickets
- Store ticket data in SQL Server
- Display ticket details through MVC views

## Project Structure

```text
sql-server-web-app/
│
├── README.md
├── LICENSE
├── .gitignore
├── sql/
│   ├── create-database.sql
│   └── seed-data.sql
├── screenshots/
│   ├── 01-homepage.png
│   ├── 02-create-ticket-form.png
│   ├── 03-ticket-list.png
│   ├── 04-database-table.png
│   └── 05-query-results.png
├── docs/
│   └── schema-diagram.png
└── TicketSystemWebApp/
