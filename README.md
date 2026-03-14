Inventory Management System (IMS)

The Inventory Management System (IMS) is a full-stack web application designed to help businesses efficiently manage their inventory, products, billing, and customer transactions. The system provides an easy-to-use interface for tracking stock levels, searching products, generating receipts, and managing inventory operations.

This project follows a client-server architecture, where the frontend handles the user interface and user interactions, while the backend manages business logic, database operations, and API services.

The application helps improve inventory control by allowing users to maintain product records, monitor stock availability, and generate transaction receipts automatically.
Project Overview

The system provides features such as:

Product inventory management

Product search functionality

Stock tracking and updates

Notification system

Receipt generation

User-friendly dashboard

Backend API integration for data handling

The project is divided into two main components:

Client (Frontend) – Handles the user interface and user interaction.

Server (Backend) – Handles the database, APIs, and application logic.

## 📁 Repository File Structure

Due to GitHub's file upload size limitation (25MB), the project is uploaded as two compressed files:

- **client.zip** → Contains the frontend source code  
- **server.zip** → Contains the backend source code  

After extracting both files, the project structure will look like this:

```
IMS-Project
│
├── client
│   │
│   ├── public
│   │   └── Static files and assets
│   │
│   ├── src
│   │   │
│   │   ├── components
│   │   │   └── Reusable UI components
│   │   │
│   │   ├── pages
│   │   │   └── Different application pages
│   │   │
│   │   ├── services
│   │   │   └── API communication functions
│   │   │
│   │   ├── styles
│   │   │   └── CSS and styling files
│   │   │
│   │   ├── App.js
│   │   │   └── Main application component
│   │   │
│   │   └── main.js / index.js
│   │       └── Application entry point
│   │
│   ├── package.json
│   │   └── Project dependencies and scripts
│   │
│   └── vite.config.js
│       └── Vite configuration file
│
├── server
│   │
│   ├── routes
│   │   └── API route definitions
│   │
│   ├── controllers
│   │   └── Business logic for handling requests
│   │
│   ├── models
│   │   └── Database schemas or data models
│   │
│   ├── config
│   │   └── Database and environment configuration
│   │
│   ├── middleware
│   │   └── Request handling middleware
│   │
│   ├── server.js / app.js
│   │   └── Main backend server file
│   │
│   └── package.json
│       └── Backend dependencies
│
└── README.md
    └── Project documentation
```
