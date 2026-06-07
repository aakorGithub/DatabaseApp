# Database System Application

A full-stack, cloud-based data storage and retrieval web application designed for efficient data management and user-friendly interaction. This system bridges classic desktop spreadsheet power with modern web applications—utilizing an Excel spreadsheet as the core data pipeline and Google Sheets/Apps Script as the real-time cloud backend database, all powered by SQL-like querying for high-performance information retrieval.

This project demonstrates end-to-end software ownership—from initial requirements gathering and schema design to final deployment readiness for the Google Workspace Marketplace.

## Live Links & Media
For Recruiters & Hiring Managers: Please Message me to get Access to the Live Site Demo
* **Demo Video:**
  ## Demo Video

<video src="PASTE_YOUR_GITHUB_ASSET_URL_HERE.mp4" width="100%" controls autocomplete muted></video>

## Key Features

* **Excel & Spreadsheet Data Pipeline:** Leverages an Excel spreadsheet format as the foundational data layer, creating a seamless pipeline that imports, exports, and syncs data to a live web interface.
* **SQL Query Functionality:** Fetches, filters, and processes complex relational data using structured, SQL-like queries for fast and optimized information retrieval.
* **Role-Based Access Control (RBAC):** Secures user data and application views based on user credentials mapped to backend authentication records.
* **Google Calendar Integration:** Automates workflow actions by scheduling and managing calendar events directly from stored database entries.
* **Dynamic, Responsive UI:** Built with asynchronous JavaScript to provide real-time UI feedback and data entry validation without page reloads.

---

## Database Architecture & Modules

As engineered in the architecture (detailed in Screenshot 2026-06-06 at 4.27.56 PM (2).jpg), the database pipeline is separated into modular, structured tables:

* `Product` – Handles product names, descriptions, and verified image asset hosting URLs.
* `Inventory` – Tracks core asset quantities and stock status across 10+ asset types.
* `Employees` – Manages corporate staff records, unique IDs, departments, and operational roles.
* `LoginData` – Enforces the system's security model by storing hashed/secure access credentials.
* `Company` & `QA` – Dedicated modules for business auditing, log tracking, and quality assurance workflows.

---

## Use Cases

* **Inventory & Asset Management:** Real-time tracking of quantities, media references, and stock status across various data pipelines.
* **Employee Record Tracking:** Securely manages internal organizational directories, ID numbers, and system roles.
* **Automated Event Scheduling:** Direct pipeline to push event parameters from the web app straight into Google Calendar reminders.
* **General CRUD Workflows:** Optimized workflows to Create, Read, Update, and Delete data while strictly reducing manual entry errors through front-end validation.

---

## Technologies Used

* **SQL / Query Language** – For structured data queries, sorting, and efficient relational manipulation.
* **Microsoft Excel / Google Sheets** – Serves as the core data pipeline, format parser, and cloud database engine.
* **Google Apps Script** – Server-side runtime handling API endpoints, spreadsheet interactions, and Google Workspace integrations.
* **JavaScript (ES6+)** – Drives front-end interactivity, dynamic DOM manipulation, and asynchronous API communication.
* **HTML5 & CSS3** – Structures and styles a clean, intuitive, and modern user interface.

---

## Installation & Setup

Because this project utilizes spreadsheet engines and Google Apps Script, it can be deployed directly via the Google Cloud ecosystem.

1. **Clone the Repository:**
```bash
   git clone [https://github.com/aakorGithub/DatabaseApp.git](https://github.com/aakorGithub/DatabaseApp.git)
   cd DatabaseApp

# Demo
https://github.com/aakorGithub/GappDb-Google-Apps-Script-Software-Application/assets/115869746/96f8be96-a0f3-4102-8650-6da934fa0b5c







# Link to Demo 
https://docs.google.com/spreadsheets/d/1Xu43iYvaCmSCzG2qXP0fLB14XAr71QT2VMIUQdgKWx8/edit?usp=sharing
