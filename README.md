

---

# Fullstack Task Manager (MERN)

---

## Overview

The Task Tracker is a web application designed to streamline team task management. Built using the MERN stack (MySQL, Express.js, React, and Node.js), this platform provides a user-friendly interface for efficient task assignment, tracking, and collaboration. The application caters to administrators and regular users, offering comprehensive features to enhance productivity and organization.

---

## Why/Problem?

In a dynamic work environment, effective task management is crucial for team success. Traditional methods of task tracking through spreadsheets or manual systems can be cumbersome and prone to errors. The Cloud-Based Task Manager aims to address these challenges by providing a centralized platform for task management, enabling seamless collaboration and improved workflow efficiency.

---

## Background

With the rise of remote work and dispersed teams, there is a growing need for tools that facilitate effective communication and task coordination. The Cloud-Based Task Manager addresses this need by leveraging modern web technologies to create an intuitive and responsive task management solution. The MERN stack ensures scalability, while the integration of Redux Toolkit, Headless UI, and Tailwind CSS enhances user experience and performance.

---

## Admin Features

1. **User Management:**
   - Create admin accounts.
   - Add and manage team members.

2. **Task Assignment:**
   - Assign tasks to individual or multiple users.
   - Update task details and status.

3. **Task Properties:**
   - Label tasks as todo, in progress, or completed.
   - Assign priority levels (high, medium, normal, low).
   - Add and manage sub-tasks.

4. **Asset Management:**
   - Upload task assets, such as images.

5. **User Account Control:**
   - Disable or activate user accounts.
   - Permanently delete or trash tasks.

---

## User Features

1. **Task Interaction:**
   - Change task status (in progress or completed).
   - View detailed task information.

2. **Communication:**
   - Add comments or chat to task activities.

---

## General Features

1. **Authentication and Authorization:**
   - User login with secure authentication.
   - Role-based access control.

2. **Profile Management:**
   - Update user profiles.

3. **Password Management:**
   - Change passwords securely.

4. **Dashboard:**
   - Provide a summary of user activities.
   - Filter tasks into todo, in progress, or completed.

---

## Technologies Used

- **Frontend:**
  - React (Vite)
  - Redux Toolkit for State Management
  - Headless UI
  - Tailwind CSS

- **Backend:**
  - Node.js with Express.js

- **Database:**
  - MySQL for efficient and scalable data storage.

---

## Setup Instructions

---

### Server Setup

#### Environment Variables

Create the environment variables file `.env` in the server folder. The `.env` file contains the following environment variables:

- MYSQL_HOST = `your MySQL host`
- MYSQL_USER = `your MySQL username`
- MYSQL_PASSWORD = `your MySQL password`
- MYSQL_DATABASE = `your database name`
- JWT_SECRET = `any secret key - must be secured`
- PORT = `8800` or any port number
- NODE_ENV = `development`

---

### Set Up MySQL:

1. Install MySQL server on your system or use a cloud-based service.
2. Create a new database for the application:
   ```sql
   CREATE DATABASE task_manager;
   ```
3. Configure the `.env` file with your MySQL connection credentials.
4. Import the SQL schema provided in the project files to initialize the database structure.

---

### Steps to Run Server

1. Open the project in any editor of choice.
2. Navigate into the server directory `cd server`.
3. Run `npm i` or `npm install` to install the packages.
4. Run database migrations (if applicable).
5. Run `npm start` to start the server.

If configured correctly, you should see a message indicating that the server is running successfully and `Database Connected`.

---

### Client Side Setup

#### Environment Variables

Create the environment variables file `.env` in the client folder. The `.env` file contains the following environment variables:

- VITE_APP_BASE_URL = `http://localhost:8800` (Adjust port if necessary)

---

### Steps to Run Client

1. Navigate into the client directory `cd client`.
2. Run `npm i` or `npm install` to install the packages.
3. Run `npm start` to run the app on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

---

## For Support, Contact:

- Email: [rkc.98@outlook.com](mailto:rkc.98@outlook.com)  
---

This version aligns the project to use MySQL as the database while retaining the rest of the structure and functionality. Let me know if further adjustments are needed!