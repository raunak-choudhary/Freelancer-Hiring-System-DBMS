# Freelancer Hiring System

**Freelancer Hiring System** is a full-stack DBMS project developed as part of the Database Management Systems course during the 5th semester of the undergraduate program in Computer Science & Engineering at SMVITM (VTU). The system provides a web-based platform that enables freelancers to discover jobs and allows companies to post opportunities, streamlining freelance hiring workflows.

## 📌 Project Overview

This system bridges the gap between freelance job seekers and companies by offering:
- Separate login modules for freelancers and companies
- Profile creation, job listings, and dashboard-based navigation
- Role-based access with secure login authentication
- Job application and posting modules integrated with a relational database

## ⚙️ Technologies Used

- **Frontend**: HTML, CSS
- **Backend**: Node.js (Express.js)
- **Database**: MySQL
- **Templating**: EJS
- **Web Server**: Localhost (Node server on port 8081)

## 🧩 Database Tables

- `buyerinfo` – Freelancer details  
- `joblisting` – Posted jobs with metadata  
- `login` – Credential records with role flags  
- `ssign` – Company information  
- `binfo` – Freelancer hobbies/interests  

The schema supports normalization (up to 3NF) for efficient query performance and data integrity.

## 💡 Key Features

- Dual-role system: Freelancers & Companies
- Job listing, addition, and deletion modules
- User session management via cookies and sessions
- Interactive UI with conditional rendering and redirects

## 🛠️ Implementation Highlights

- Built using modular routing and middleware in Express.js
- Implemented relational joins and foreign key constraints
- Secure session management for login states and role-specific dashboards

## 👨‍💻 Author

- **Raunak Choudhary**  
  Email: [raunakchoudhary17@gmail.com](mailto:raunakchoudhary17@gmail.com)  
  LinkedIn: [linkedin.com/in/raunak-choudhary](https://www.linkedin.com/in/raunak-choudhary)
