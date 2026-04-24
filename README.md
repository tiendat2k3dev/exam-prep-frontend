# Exam Preparation System (Frontend)

## Overview
A React-based web application supporting Admin, Teacher, and Student roles to manage exams, classes, and results


[![Live Demo](https://img.shields.io/badge/-Live%20Demo-brightgreen)](https://thitracnghiem-sandy.vercel.app)

## Demo
- **Frontend (Vercel)**: [https://thitracnghiem-sandy.vercel.app](https://thitracnghiem-sandy.vercel.app)
- **Backend (local)**: `http://localhost:8080/api`

## Technical Highlights
- **Multi-role system**: Admin, Teacher, Student with different permissions and views.
- **Role-based UI rendering**: each role sees relevant modules only.
- **Global auth state with Context API**: centralized session and user state handling.
- **Protected Routes**: route guards for authenticated and authorized access.
- **Reusable UI architecture**: shared `Table`, `Modal`, and layout components.
- **JWT Authentication** with stable API integration via Axios.
- **Pagination & Filtering** for scalable table/data management.

## Screenshots

### Login & Authentication
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

### Student Dashboard & Exams
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
- ReactJS (Hooks, Context API)
- React Router
- Axios
- Ant Design / Bootstrap
- JWT Authentication

## Key Features
- Multi-role system (Admin, Teacher, Student)
- Role-based UI rendering
- Authentication & Authorization (JWT)
- Protected Routes
- Reusable Layout (Sidebar, Header)
- Reusable components (Table, Modal, Form)
- Pagination & Filtering
- Dynamic data rendering from REST API

## Challenges & Solutions
- Managing authentication state across modules -> solved with Context API.
- Handling protected routes by role -> implemented route guards and role checks.
- Avoiding duplicated UI logic -> built reusable components and shared layouts.

## My Contributions
- Developed role-specific interfaces for Admin, Teacher, and Student.
- Built reusable layout and component patterns (Header, Sidebar, Table, Modal).
- Implemented authentication flow with Context API and JWT-based authorization.
- Integrated RESTful APIs using Axios.
- Implemented routing strategy with protected routes and role-based access.

## Quick Setup
```bash
# Clone repository
git clone <your-repo-url>

# Enter project folder
cd exam-prep-frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

### Environment Variables
Create `.env` in project root:

```env
VITE_API_BASE_URL=http://localhost:8080/api
```

### Build for Production
```bash
npm run build
```
## Project Structure

```text
quan-ly-nguoi-dung-frontend-v1/
├── .env                     # Environment variables
├── package.json
├── README.md
├── public/
└── src/
    ├── assets/             # Images, icons, static files
    ├── components/         # Reusable UI components
    ├── pages/              # Main application pages
    ├── services/           # API calls (auth, account, department)
    ├── hooks/              # Custom hooks (useAuth)
    ├── contexts/           # Global state / AuthContext
    ├── utils/              # Helper functions
    ├── layouts/            # Header / Sidebar layouts
    ├── App.jsx
    └── main.jsx
```


