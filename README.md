# Student Management System

A full-stack web application developed to manage student records efficiently. It allows users to add, view, update, and delete student information through a user-friendly interface.

## Features

- Add new student records.
- View student details.
- Update existing student information.
- Delete student records.
- Manage student information efficiently.

## Technologies Used

**Frontend**
- React.js
- JavaScript
- HTML5
- CSS3
- Bootstrap 5

**Backend**
- Java
- Spring Boot
- REST APIs

**Database**
- MySQL

**Tools**
- Git
- GitHub
- Maven
- VS Code

## Project Structure

```text
Student-Management-System/
│
├── backend/
│   └── studentmanagement/
│
├── frontend/
│
├── .gitignore
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/madhavi-09/Student-Management-System.git
```

### 2. Navigate to the project

```bash
cd Student-Management-System
```

### 3. Start the Backend

```bash
cd backend/studentmanagement
```

Run:

```bash
.\mvnw.cmd spring-boot:run
```

### 4. Start the Frontend

Open another terminal:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm run dev
```

## Database Configuration

This project uses MySQL.

Create a database:

```sql
CREATE DATABASE student_db;
```

Configure the database credentials in the Spring Boot `application.properties` file.

## Author

**Madhavi Uppu**

GitHub: [madhavi-09](https://github.com/madhavi-09)

## Acknowledgement

This project is based on an existing open-source project. The original source is available at [Student Management System](https://github.com/MalayaNayak2002/student-management-system).
