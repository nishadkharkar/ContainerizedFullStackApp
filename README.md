# ContainerizedFullStackApp
Survey Management System
A full-stack CRUD application designed for efficient survey creation and management. This project features a dynamic front-end built with Vue.js, a robust PostgreSQL back-end for data persistence, and is fully containerized using Docker for seamless deployment and portability.

🚀 Features
Dynamic Survey Creation: User-friendly interface for building and managing surveys.

Full CRUD Functionality: Create, Read, Update, and Delete operations for survey records.

Advanced Validation: Implements complex client-side validation (Vue.js) and server-side validation to ensure data integrity.

Persistent Storage: Reliable data management using a PostgreSQL relational database.

Containerized Architecture: Front-end, back-end, and database services are isolated and managed via Docker and Docker Compose.

🛠️ Tech Stack
Front-end: Vue.js

Back-end: Node.js/Express (or your specific runtime)

Database: PostgreSQL

DevOps: Docker, Docker Compose

📦 Project Structure
Plaintext
├── frontend/          # Vue.js application
├── backend/           # API and server-side logic
├── database/          # Database configuration and migrations
├── docker-compose.yml # Multi-container orchestration
└── README.md
🛠️ Getting Started
Prerequisites
Docker

Docker Compose

Installation & Running
Clone the repository:

Bash
git clone https://github.com/your-username/survey-management-system.git
cd survey-management-system
Spin up the containers:
Use Docker Compose to build and start the front-end, back-end, and database services simultaneously:

Bash
docker-compose up --build
Access the Application:

Front-end: http://localhost:8080 (or your configured port)

API/Back-end: http://localhost:3000

🐳 Containerization Strategy
This application utilizes a multi-container architecture:

Frontend Service: Serves the Vue.js app via an optimized environment.

Backend Service: Handles API requests and form validation.

Database Service: A PostgreSQL container with persistent volume mapping to ensure data survives container restarts.

🎓 Academic Context
This project was developed at George Mason University as part of a focus on containerization and full-stack architecture, emphasizing infrastructure consistency and portable multi-container environments.
