# Courier Management System

## Overview
The Courier Management System is a web-based logistics management platform designed to support shipment creation, package tracking, and delivery management. The system allows users to create shipment requests and track package delivery status in real time, while administrators can manage packages and update delivery information.

This project was developed as part of the **IFN636 Software Life Cycle Management** assessment at **Queensland University of Technology (QUT)**.

The system follows the **CRUD (Create, Read, Update, Delete)** model to manage shipment information and delivery status.

---

# Table of Contents

- Project Overview
- System Features
- System Architecture
- Project Tools
- Setup Instructions
- Demo Access
- Repository Structure
- Author

---

# System Features

## User Features
- Create shipment requests
- Track package status
- View shipment history

## Administrator Features
- View package records
- Update delivery status
- Delete package records

---

# System Architecture

The system architecture consists of three main layers:

User / Administrator  
↓  
User Interface (Frontend)  
↓  
Application Backend  
↓  
Courier Database

The frontend provides the user interface for shipment creation and tracking, while the backend manages business logic and interacts with the database to store shipment data.

---

# Project Tools

The following tools were used during the development process:

| Tool | Purpose |
|-----|------|
| Draw.io | SysML diagrams and system design |
| JIRA | Agile project management |
| Figma | UI/UX design prototype |
| GitHub | Project repository and documentation |

---

# Setup Instructions

Follow the steps below to run the project locally.

### 1 Clone the repository
git clone https://github.com/EugeneXJL/Courier-Management-System

### 2 Navigate to the project folder
cd Courier-Management-System

### 3 Install dependencies
npm install

### 4 Run the project
npm start

### 5 Open the application
http://localhost:8000

---

# Demo Access

The system can be tested using the following demo accounts:

### User Account
Username: user  
Password: user123

### Administrator Account
Username: admin  
Password: admin123

---

# Repository Structure


Courier-Management-System
│
├── diagrams
│ ├── requirement-diagram
│ ├── use-case-diagram
│ └── system-architecture
│
├── ui-design
│ └── figma-screens
│
├── documentation
│ └── project-report
│
└── README.md


---

# Author

Jianliang Xu  
IFN636 Software Life Cycle Management  
Queensland University of Technology

