# MERN Stack Blog Project

## Overview
This is a Full Stack Blog Application built using the MERN stack (MongoDB, Express, React, Node.js). The application allows users to create, edit, and delete blog posts, with an AI-powered feature to generate summaries for blog posts. A demo video is included for better understanding.

---

## Features
- **User Authentication**: Secure login and signup functionality.
- **CRUD Operations**: Create, Read, Update, and Delete blog posts.
- **AI-Powered Summaries**: Generate concise summaries for blog content using AI.
- **Responsive Design**: Fully responsive and optimized for all devices.
- **Video Demo**: A walkthrough of the app's functionality is included.

---

## Tech Stack
### Frontend
- **React.js**: For building a dynamic and responsive user interface.

### Backend
- **Node.js**: For server-side logic.
- **Express.js**: For creating APIs.

### Database
- **MongoDB**: For storing user and blog data.

### Additional Tools
- **AI Integration**: For generating blog summaries.

---

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone <https://github.com/Meetpaneliya/blogg.git>
   ```
2. Navigate to the project directory:
   ```bash
   cd mern-blog-stack
   ```
3. Install dependencies for both frontend and backend:
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```
4. Configure environment variables:
   - Create a `.env` file in the server directory and add:
     ```env
     MONGO_URI=your_mongodb_connection_string
     PORT=5000
     ```
5. Start the application:
   - Backend:
     ```bash
     cd server
     npm start
     ```
   - Frontend:
     ```bash
     cd client
     npm start
     ```
6. Access the application at `http://localhost:3000`.

---

## Demo
![Demo Video](
https://github.com/user-attachments/assets/d3a99e7b-009e-41a2-98a0-e7a3176cd6ee
)

---

## Folder Structure
```
blog-mern-stack/
├── client/          # React frontend
├── api/          # Express backend
├── .env             # Environment variables
├── README.md        # Project documentation
```


