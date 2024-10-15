# Jobify App

[Jobify App](https://jobify-app-r8s1.onrender.com) is a full-stack MERN application that allows users to manage job applications, track statuses, and more. This app provides a streamlined interface to handle the entire job application process, from creation to tracking, with secure user authentication and CRUD functionality.

## Live Demo
Check out the live app: [Jobify App](https://jobify-app-r8s1.onrender.com)

## Features
- **Job Management:** Create, edit, delete, and track jobs.
- **User Authentication:** Secure login and registration using JWT tokens.
- **Dark Mode:** Toggle dark mode, stored via localStorage.
- **Error Handling:** Real-time notifications using React Toastify.
- **Responsive Design:** Mobile and desktop friendly.

## Screenshots

### Dashboard
![Dashboard Screenshot](link_to_screenshot)

### Add Job
![Add Job Screenshot](link_to_screenshot)

### Login
![Login Screenshot](link_to_screenshot)

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
- **Concurrently, Nodemon** for local development

### Installation

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
The server runs at `http://localhost:5100`  
The client runs at `http://localhost:5173`

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

## Contributing
Feel free to contribute! Fork the repo and submit a pull request.
