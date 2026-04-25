# Project Structure

This document outlines the directory structure of the `fake-job-detection-system` project, detailing the purpose of each folder and its contents.

## Directory Layout

```plaintext
fake-job-detection-system/
│
├── frontend/
│   ├── src/
│   │   ├── components/         # React components for the UI
│   │   ├── pages/              # Page components
│   │   └── styles/             # Stylesheets for components
│   │
│   ├── public/                # Static files like HTML, images, etc.
│   └── package.json            # Frontend dependencies and scripts
│
├── backend/
│   ├── app/
│   │   ├── controllers/       # Business logic and controller functions
│   │   ├── middleware/         # Express middleware functions
│   │   ├── models/             # Database models
│   │   └── routes/             # API routes
│   │
│   ├── config/                # Configuration files (e.g., database config)
│   └── server.js               # Entry point for the backend server
│
├── ml_model/
│   ├── training/               # Scripts for training machine learning models
│   ├── models/                 # Saved models and serialization
│   ├── utils/                  # Utilities for data processing
│   └── requirements.txt        # Dependencies for ML tasks
│
├── chrome_extension/
│   ├── src/
│   │   ├── background.js       # Background script for the extension
│   │   ├── content.js           # Content script injected into web pages
│   │   └── popup.html           # HTML for the extension's popup
│   └── manifest.json            # Metadata for the Chrome extension
│
├── database/
│   ├── migrations/             # Database migration scripts
│   ├── seeds/                  # Seed data files for populating database
│   └── database.sql            # SQL dump of the initial database structure
│
├── admin_dashboard/
│   ├── src/
│   │   ├── components/         # Components for the admin dashboard UI
│   │   └── pages/              # Admin dashboard pages
│   └── package.json            # Backend dependencies and scripts
│
└── docs/
    ├── API_DOCUMENTATION.md   # API documentation
    ├── USER_GUIDE.md            # User guide for the application
    └── INSTALLATION.md          # Setup and installation instructions
```

## Folder Descriptions

- **frontend/**: Contains all files related to the client-side application built with React. It manages the user interface and user experience of the application.

- **backend/**: Contains the server-side application built with Node.js and Express, handling API requests and business logic.

- **ml_model/**: Contains scripts and resources for machine learning processes, including training scripts and model files.

- **chrome_extension/**: Contains all files necessary to build a Chrome extension that integrates with the application.

- **database/**: Holds database migration scripts and seed data for setting up the initial state of the database.

- **admin_dashboard/**: Contains files for an administrative interface to manage the application and its users.

- **docs/**: Documentation regarding the project, including API specifications, user guides, and installation instructions.