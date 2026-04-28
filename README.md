# Exam Preparation System (Frontend)

## Overview
A React-based Single Page Application (SPA) supporting Admin, Teacher, and Student roles to manage exams, classes, and learning progress efficiently

## Live Demo
https://thitracnghiem-sandy.vercel.app

## Screenshots

### Login Page
![Login](src/assets/images/login.png)
![Forgot Password](src/assets/images/quenmatkhau.png)
![Verification & Password Reset](src/assets/images/xacthucvadoimatkhau.png)

### Admin Dashboard & Management
![Admin Dashboard](src/assets/images/dashboard.png)
![User Management](src/assets/images/nguoidung.png)
![Class Management](src/assets/images/lop.png)
![Teacher Assignment](src/assets/images/phancong.png)

### Teacher Dashboard & Management
![Teacher Dashboard](src/assets/images/dashboard_teacher.png)
![Exam Management](src/assets/images/quanlydethi.png)
![Question Management](src/assets/images/quanlycauhoi.png)
![Category Management](src/assets/images/quanlydanhmuc.png)
![Student Management](src/assets/images/quanlyhocvien.png)
![Class Exam Management](src/assets/images/quanlylop.png)

### Student Interface
![Student Dashboard](src/assets/images/dashboard_student.png)
![Practice Exam](src/assets/images/thithu.png)
![Official Exam](src/assets/images/thithat.png)
![Taking Exam](src/assets/images/lambaithi.png)
![Practice History](src/assets/images/lichsuthithu.png)
![Official History](src/assets/images/lichsuthithat.png)

### Reusable Modals & Edge Cases
![Update Profile](src/assets/images/capnhatthongtin.png)
![Change Password](src/assets/images/capnhatmatkhau.png)
![404 Not Found](src/assets/images/404.png)

## Tech Stack
ReactJS (Hooks, Context API)  
React Router (Protected Routes)  
Axios (REST API Integration)  
Ant Design / Bootstrap  
JWT Authentication  
Vercel (Deployment & CI/CD)

## Key Features

- Authentication & Authorization (JWT)  
- Multi-role system (Admin, Teacher, Student)  
- Protected Routes for role-based access control  
- Reusable component architecture (Header, Sidebar, Layout)  
- Dynamic data rendering from REST APIs  
- Dashboard & statistics display  
- Optimized API calls to reduce unnecessary requests  
- Responsive UI (Desktop & Tablet)

## My Contributions

- Developed frontend for 15+ screens across 3 roles (Admin, Teacher, Student)  
- Built reusable layout system (Header, Sidebar) to reduce duplicated code  
- Implemented authentication flow (Login, Forgot Password, JWT handling)  
- Integrated REST APIs using Axios and handled async data rendering  
- Managed routing using React Router with 10+ routes  
- Optimized API calls using state management to improve performance  
- Deployed application using Vercel with CI/CD pipeline

## Challenges & Solutions

- Managing authentication state  
  → Solved using Context API for global state management  

- Handling protected routes  
  → Implemented custom route guards based on user roles  

- Reducing duplicated UI code  
  → Built reusable components and layout system  

- Ensuring smooth user experience  
  → Standardized notifications using React Toastify

## Installation

```bash
# Clone repository
git clone https://github.com/tiendat2k3dev/exam-prep-frontend

# Enter project folder
cd exam-prep-frontend

# Install dependencies
npm install
### Environment Variables

Create a `.env` file in the project root:

``` .env
VITE_API_BASE_URL=http://localhost:8080/api

npm run dev
```

## Project Structure
```text
exam-prep-frontend/
├── .env                     # Environment variables
├── package.json
├── README.md
├── public/
└── src/
    ├── assets/             # Images, icons, static files
    ├── components/         # Reusable UI components
    ├── pages/              # Main application pages
    ├── services/           # API calls
    ├── hooks/              # Custom hooks
    ├── context/            # Global state / AuthContext
    ├── route/              # Route-level guards and navigation flow
    ├── layouts/            # Header / Sidebar layouts
    ├── App.jsx
    └── main.jsx
```
## Notes

- This project is part of a team of 7 members  
- My main responsibility: Frontend development & integration

## Related Repositories

- Backend: https://github.com/tiendat2k3dev/exam-prep-backend  
- Frontend (this repo): https://github.com/tiendat2k3dev/exam-prep-frontend
