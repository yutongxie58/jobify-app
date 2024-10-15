# Jobify App

[Jobify App](https://jobify-app-r8s1.onrender.com) is a full-stack MERN application designed to help users efficiently manage and track their job applications. With secure user authentication, job CRUD operations, and a responsive UI, the app provides a seamless experience for users looking to organize their job search.

## 🚀 Live Demo
👉 **[Try Jobify Live](https://jobify-app-r8s1.onrender.com)**

## Features
- **Job Management:** Easily create, edit, delete, and track job applications.
- **User Authentication:** Secure login and registration using JWT.
- **Dark Mode:** Toggle dark mode, with user preferences stored in localStorage.
- **Real-time Notifications:** Error and success notifications via React Toastify.
- **Responsive Design:** Mobile-friendly, built with styled-components.

## Screenshots

### Starter
<img src="https://i.postimg.cc/CKFNr62Z/starter.png" width="800" alt="Jobify Starter Screenshot">

### Add Job
<img src="https://i.postimg.cc/3JXfLpwc/add-job.png" width="800" alt="Jobify Add Job Screenshot">

### Job Listings
<img src="https://i.postimg.cc/L5C5Rh4K/job-listings.png" width="800" alt="Jobify Job Listings Screenshot">

### Job Statistics
<img src="https://i.postimg.cc/5yNyZ8VS/job-stats.png" width="800" alt="Jobify Job Statistics Screenshot">

### Profile Management
<img src="https://i.postimg.cc/G3qHvgF7/profile.png" width="800" alt="Jobify Profile Management Screenshot">

## Tech Stack

### Frontend:
- **React.js**, **Vite**, **React Router DOM**, **Axios**, **React Query**
- **Styled Components** for styling
- **React Toastify** for notifications

### Backend:
- **Node.js**, **Express.js**
- **MongoDB** with **Mongoose**
- **JWT** for secure authentication
- **Cloudinary** for image uploads
- **Express Validator** for validation

### Dev Tools:
- **Concurrently**, **Nodemon** for local development

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yutongxie58/jobify-app.git
   cd jobify-app
   ```
2. **Install dependencies and run the app:**
   ```bash
   npm run setup-project
   npm run dev
   ```
- The server runs at `http://localhost:5100`  
- The client runs at `http://localhost:5173`

## API Endpoints

### Authentication
| Method | Endpoint               | Description           |
|--------|------------------------|-----------------------|
| POST   | `/api/v1/auth/register` | Register a new user   |
| POST   | `/api/v1/auth/login`    | Log in a user         |
| GET    | `/api/v1/auth/logout`   | Log out a user        |

### Job Management
| Method  | Endpoint               | Description            |
|---------|------------------------|------------------------|
| GET     | `/api/v1/jobs`          | Fetch all jobs         |
| POST    | `/api/v1/jobs`          | Create a new job       |
| GET     | `/api/v1/jobs/:id`      | Fetch a single job     |
| PATCH   | `/api/v1/jobs/:id`      | Update a job           |
| DELETE  | `/api/v1/jobs/:id`      | Delete a job           |

## 🤝 Contributing
Contributions are welcome! Fork the repo, create a branch, and submit a pull request.
