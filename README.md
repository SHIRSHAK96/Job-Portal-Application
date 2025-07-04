# job-portal-mern-stack
This is a Full stack job App made with MERN Stack, MUI, Datagrid, cookie, etc.  It is a Youtube series to teach step by step how to make a full stack App

##### To use this app: clone this repo, in the root of bonus folder create a .env file with these variables PORT=9000 DATABASE=YOUR_MONGO_URL JWT_SECRET=fidbfbFCDSm1558 NODE_ENV=development if in development mode and NODE_ENV=production if you're deploying your App; after that, run "npm install" in the bonus root folder. Go inside frontend folder in bonus folder, run "npm install "

![image](https://github.com/user-attachments/assets/cfed70ac-9edb-47fc-b6ec-3b7005021799)


![image](https://github.com/user-attachments/assets/e9f2f726-ca11-4325-bbe1-769576021142)


🔍 About the Project

This job portal allows recruiters to post new job listings and candidates to browse, search, filter, and apply for jobs. It features:

Role-based authentication (Recruiter & Candidate)

Responsive React front‑end with theme toggling (dark/light)

Secure REST API built with Node.js & Express

MongoDB for data storage

JWT & HTTP-only cookies for authentication

Admin dashboard with analytics

✨ Features

User Authentication: Sign up, log in, role-based access control

Job Management: Create, update, delete, and list jobs (recruiter)

Search & Filter: Filter by title, category, location

Responsive Design: Mobile-first, adapts to any screen size

Dashboard Analytics: Charts & metrics for job posts and applications

Notifications: Toasts for success/error feedback

🛠️ Technology Stack

Layer

Technology

Front‑end

React, React Router, MUI

Back‑end

Node.js, Express

Database

MongoDB, Mongoose

Auth

JSON Web Tokens (JWT)

State

React Context / Redux (opt)

Styling

Tailwind CSS / Material UI

Validation

Formik, Yup

Folder Structure
root/
├── backend/           # Express API server
│   ├── controllers/   # Route controllers
│   ├── models/        # Mongoose schemas
│   ├── routes/        # Express routes
│   ├── middleware/    # Auth, error handling
│   └── server.js      # Entry point
└── frontend/          # React application
    ├── public/        # Static assets
    ├── src/
    │   ├── assets/    # Images, icons, styles
    │   ├── components/# Reusable UI components
    │   ├── pages/     # Route-level components
    │   ├── context/   # React Context providers
    │   ├── services/  # API helper functions
    │   └── App.js     # Main app wrapper

🚀 Getting Started

Prerequisites

Node.js >= 14.x

npm or yarn

MongoDB instance (local or cloud)

Installation

Clone the repo

git clone https://github.com/<your-username>/mern-job-portal.git
cd mern-job-portal

Install dependencies

# Backend
cd backend && npm install

# Frontend (in new terminal tab)
cd frontend && npm install

Configure environment variables

Create a .env file in backend/:

PORT=9000
MONGO_URI=<your_mongo_connection_string>
JWT_SECRET=<your_jwt_secret>
NODE_ENV=development

Start the servers

# Backend (runs on http://localhost:9000)
cd backend && npm run dev

# Frontend (runs on http://localhost:3000)
cd frontend && npm start

🎯 Usage

Register as a Recruiter to create job postings and view applications.

Register as a Candidate to browse jobs and submit applications.

Use the Search bar and Filters to find relevant job listings.

Toggle between Dark and Light modes in the header.

📡 API Endpoints

Method

Endpoint

Description

POST

/api/auth/register

Create a new user

POST

/api/auth/login

Authenticate user

GET

/api/jobs

List all jobs

POST

/api/jobs

Create a new job (recruiter)

GET

/api/jobs/:id

Get job details

PUT

/api/jobs/:id

Update job (recruiter)

DELETE

/api/jobs/:id

Delete job (recruiter)

POST

/api/jobs/:id/apply

Submit application (candidate)

🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements.

📄 License

Distributed under the MIT License. See LICENSE for more information.

📬 Contact

My Name –Shirshak Mandal
My email-shirshakmandal12july@gmail.com
Project Link: https://github.com/SHIRSHAK96/Job-Portal-Application

