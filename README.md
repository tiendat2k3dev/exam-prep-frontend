# Exam Preparation System (Frontend)

## Overview
A React-based web application supporting Admin, Teacher, and Student roles to manage exams, classes, and results

## Demo 🔗
[![Live Demo](https://img.shields.io/badge/-Live%20Demo-brightgreen)](https://thitracnghiem-sandy.vercel.app)

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
- **CI/CD Pipeline**: Automated deployment via Vercel.

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
- Vercel (CI/CD Deployment)

## Key Features
### 🔐 Authentication & Authorization
- Multi-role system (Admin, Teacher, Student)
- JWT-based authentication
- Protected routes with role-based access control
- Password reset & verification flow

### 🎨 UI/UX
- Role-based UI rendering
- Reusable Layout (Sidebar, Header)
- Reusable components (Table, Modal, Form)
- Responsive design

### 📊 Data Management
- Pagination & Filtering
- Dynamic data rendering from REST API
- State management with Context API

## Challenges & Solutions
- Managing authentication state across modules -> solved with Context API.
- Handling protected routes by role -> implemented route guards and role checks.
- Avoiding duplicated UI logic -> built reusable components and shared layouts.

## My Contributions (Team of 7 members)
- **Developed UI for 15+ screens** across all three roles (Admin, Teacher, Student)
- **Implemented authentication flow** with Context API and JWT-based authorization
- **Built reusable component architecture** including Table, Modal, Filter, and Layout components
- **Integrated RESTful APIs** using Axios with interceptors for token management
- **Implemented routing strategy** with protected routes and role-based access control
- **Collaborated with team** to ensure consistent UI/UX across the application

## Quick Setup
```bash
# Clone repository
git clone https://github.com/tiendat2k3dev/exam-prep-frontend

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
## GitHub Profile Optimization
- **Suggested bio**: `Frontend Developer | ReactJS | Building scalable UI`
- **Recommended pinned repositories**:
  - `exam-prep-frontend`
