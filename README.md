# InternPath – Internship Application Portal

InternPath is a full-stack web application that streamlines the internship application process for both students and recruiters. Students can browse internship opportunities, submit applications, and track their application status, while recruiters can review applications and update their status through a dedicated dashboard.

The project demonstrates full-stack web development concepts including RESTful APIs, CRUD operations, client-server communication, and MongoDB integration using Node.js and Express.js.

---

## Features

### Student Portal
- Login using email
- Browse available internship opportunities
- Apply for internships
- Track application status
- View previously submitted applications

### Recruiter Portal
- Recruiter login
- View all internship applications
- Update application status
- Manage application workflow

### Backend
- RESTful API built with Express.js
- MongoDB database integration using Mongoose
- Stores internship applications
- Supports retrieval and status updates

---

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (ES6)

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

---

## Project Structure

```
InternPath/
│
├── node_modules/
├── index.html
├── style.css
├── script.js
├── server.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## Application Workflow

1. Student logs in using their email.
2. Student browses available internship listings.
3. Student submits an application for a selected internship.
4. The application is stored in MongoDB.
5. Recruiter logs in to view all submitted applications.
6. Recruiter updates the application status.
7. Students can view the updated status from their dashboard.

---

## REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/applications` | Fetch all internship applications |
| POST | `/api/applications` | Submit a new internship application |
| PUT | `/api/applications/:id` | Update application status |

---

## Installation

### Clone the repository

```bash
git clone https://github.com/diksha-sakhi03/InternPath.git
```

### Navigate to the project directory

```bash
cd InternPath
```

### Install dependencies

```bash
npm install
```

### Start MongoDB

Make sure MongoDB is running locally.

Default MongoDB connection:

```text
mongodb://127.0.0.1:27017/internship_db
```

### Start the server

```bash
node server.js
```

Open your browser and visit:

```
http://localhost:3000
```

---

## Demo Credentials

### Recruiter

```
Email: recruiter@internpath.com
```

### Student

Use any valid email address to log in as a student.

---

## Screenshots

> Add screenshots of your project here.

- Login Page
- Student Dashboard
- Recruiter Dashboard

---

## Future Enhancements

- Secure authentication using passwords and JWT
- Resume upload functionality
- Search and filter internships
- Company management dashboard
- Email notifications
- MongoDB Atlas integration
- Responsive mobile interface

---

## Learning Outcomes

Through this project, I gained practical experience with:

- Full-Stack Web Development
- REST API Design
- CRUD Operations
- Express.js
- MongoDB & Mongoose
- Client-Server Architecture
- Asynchronous JavaScript (Fetch API)
- Git & GitHub Workflow

---

## Author

**Diksha Sakhi**

B.Tech Computer Science Engineering  
The LNM Institute of Information Technology (LNMIIT), Jaipur

GitHub: https://github.com/diksha-sakhi03