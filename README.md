# MERN-Notes-App

## Table of Contents  
- [Project Overview](#project-overview)  
- [Reasons for Making This Project](#reasons-for-making-this-project)  
- [Tools and Technologies Used](#tools-and-technologies-used)  
- [Tasks Performed](#tasks-performed)  
- [Web App Screenshots and UI](#web-app-screenshots-and-ui)  
- [Results and Findings](#results-and-findings)

---

## Project Overview:
This project is a **Full-Stack Note-Taking Application** built using the **MERN stack (MongoDB, Express, React, Node.js)**. It allows users to **create, read, update, and delete** personal notes through a modern, responsive interface. The app integrates a secure backend API, a MongoDB database for storage, and a fast frontend built with Vite + React, styled using Tailwind CSS and Daisy UI. The app is fully deployable and production-ready with rate-limiting and API optimization features.

---

## Reasons for Making This Project:
- **Fullstack Development Practice**: To gain experience building an end-to-end application with modern JavaScript technologies.
- **API Design and CRUD Operations**: To implement and structure clean RESTful APIs with full CRUD functionality.
- **Frontend-Backend Integration**: To learn how to consume backend APIs in a dynamic React application.
- **MongoDB Integration**: To work with a NoSQL database and manage schema with Mongoose.
- **Deployment Readiness**: To push a real-world project from local development to live deployment using services like Render.
- **Middleware & Rate Limiting**: To understand request lifecycle management and secure the backend using Redis-based rate limiting.

---

## Tools and Technologies Used:
- **MongoDB + Mongoose** → NoSQL database and ODM for managing note data  
- **Node.js + Express** → Backend API and server logic  
- **React (Vite)** → Frontend user interface  
- **Tailwind CSS + Daisy UI** → Utility-first styling and UI components  
- **React Router DOM** → Routing between pages  
- **Axios** → HTTP requests between frontend and backend  
- **Upstash Redis** → For rate limiting API requests  
- **Dotenv** → Environment variable management  
- **Render** → Hosting and deployment  
- **Nodemon** → Backend auto-reload during development  

---

## Tasks Performed:

### 1) Backend API:
- Set up Express server with ES module support.
- Created modular route and controller files for `/api/notes`.
- Connected to MongoDB Atlas using Mongoose.
- Built full CRUD operations:  
  - `GET /api/notes` → Fetch all notes  
  - `POST /api/notes` → Create new note  
  - `PUT /api/notes/:id` → Update a note  
  - `DELETE /api/notes/:id` → Delete a note  

### 2) Middleware & Rate Limiting:
- Implemented JSON parsing and logging middleware.
- Integrated Upstash Redis-based rate limiter to prevent abuse.

### 3) Frontend (React):
- Initialized using Vite for fast development.
- Created pages: Home, Create Note, Note Detail.
- Implemented React Router for navigation.
- Added user feedback using React Hot Toast.
- Styled the app using Tailwind CSS and Daisy UI.

### 4) Frontend Features:
- Navbar with route links.
- Form to create and edit notes with validation.
- Notes displayed in cards with title, content, and timestamps.
- Delete confirmation prompt.
- Loading and empty state UIs.
- Used Axios instance for optimized API requests.

### 5) Deployment:
- Combined frontend and backend in one repo.
- Created root-level `package.json` to manage scripts.
- Served React build from Express in production.
- Deployed on **Render** with environment variables configured.

---

## Web App Screenshots and UI:


![Home Page](https://github.com/user-attachments/assets/05b25a04-32a1-49e7-857c-22e2f8ca0613)
![Note Detail](https://github.com/user-attachments/assets/f40f9227-c783-4cc2-9785-d181045436b1)
![Create Note](https://github.com/user-attachments/assets/35c378ce-c4f3-444b-b076-be08760996c4)

---

## Results and Findings:

-  Fully functional MERN stack app for note management.  
-  Clean UI/UX with modern design and responsiveness.  
-  Rate limiting adds production-level security.  
-  Codebase structured for scalability and maintainability.  
-  Successfully deployed using Render with working API endpoints.  
-  Great project for understanding fullstack app lifecycle from development to deployment.
