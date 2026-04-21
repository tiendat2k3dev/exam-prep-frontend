# Hệ thống luyện thi Trắc nghiệm

[![Demo](https://img.shields.io/badge/-Live%20Demo-brightgreen)](https://thitracnghiem-sandy.vercel.app)

## Overview
Phát triển ứng dụng web thi trắc nghiệm với 3 vai trò: Admin, Teacher, Student, hỗ trợ quản lý lớp học, đề thi và theo dõi kết quả học tập.

## Screenshots
### Login & Authentication

![Login](src/assets/images/login.png)
### Forgot Password  
![Forgot Password](src/assets/images/quenmatkhau.png)
### Verification & Password Reset
![Verification](src/assets/images/xacthucvadoimatkhau.png)
### Admin
- **Dashboard**  
  ![Dashboard](src/assets/images/dashboard.png)

- **User Management**  
  ![User](src/assets/images/nguoidung.png)

- **Class Management**  
  ![Class](src/assets/images/lop.png)

- **Assignment / Class Assignment**  
  ![Assignment](src/assets/images/phancong.png)

### Teacher

- **Teacher Dashboard**  
  ![Dashboard](src/assets/images/dashboard_teacher.png)

- **Exam Management**  
  ![Exam](src/assets/images/quanlydethi.png)

- **Question Management**  
  ![Questions](src/assets/images/quanlycauhoi.png)

- **Category Management**  
  ![Categories](src/assets/images/quanlydanhmuc.png)

- **Student Management**  
  ![Students](src/assets/images/quanlyhocvien.png)

- **Class Exam Management**  
  ![Classes](src/assets/images/quanlylop.png)
### Student

**Student Dashboard**  
![Dashboard](src/assets/images/dashboard_student.png)

**Practice Exam**  
![Practice Exam](src/assets/images/thithu.png)

**Official Exam**  
![Official Exam](src/assets/images/thithat.png)


**Do Exam**  
![Do Exam](src/assets/images/lambaithi.png)

**Practice Exam History**  
![Practice History](src/assets/images/lichsuthithu.png)

**Official Exam History**  
![Official History](src/assets/images/lichsuthithat.png)

### Modals & Features
**Update Profile Modal**  
![Update Profile](src/assets/images/capnhatthongtin.png)
 **Change Password Modal**  

![Change Password](src/assets/images/capnhatmatkhau.png)
**404 Not Found Page** 
![404 Page](src/assets/images/404.png)

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-19.2.4-blue?style=flat&logo=react)
![Vite](https://img.shields.io/badge/Vite-7.3.1-orange?style=flat&logo=vite)
![Ant Design](https://img.shields.io/badge/Ant%20Design-6.3.2-yellow?style=flat&logo=antdesign)
![React Router](https://img.shields.io/badge/React%20Router-7.13.1-red?style=flat&logo=reactrouter)

### Thư viện chính
- **Quản lý state**: React Context API.
- **UI**: Ant Design, Bootstrap 5.
- **Routing**: React Router DOM.
- **Gọi API**: Axios.
- **Thông báo**: React Toastify.
- **Icons**: FontAwesome, React Icons.
- **Date handling**: Dayjs.
- **Build tool**: Vite.
## Tính năng
### Chung
- Đăng nhập/Đăng ký, quên mật khẩu, xác thực và đổi mật khẩu
- Bảo vệ routes theo vai trò (Admin/Teacher/Student) với AuthContext và ProtectedRoute
- Responsive layouts với Sider/Header tùy role
- Quản lý bảng với filter, search, pagination, actions (BaseTable, AppPagination)
- Modals CRUD (add/edit/view) cho entities
- Error handling (ErrorBoundary, 404 page)
- Toast notifications và charts (ScoreChart)

### Admin
- Dashboard thống kê
- Quản lý users (CRUD, table/filter)
- Quản lý classes (CRUD, add users)
- Phân công teacher cho classes (assignTeacher)

### Teacher
- Dashboard với QuickActions và ScoreChart
- Quản lý exams (CRUD, preview, assign to class)
- Quản lý questions (CRUD)
- Quản lý categories
- Quản lý students và exam-classes

### Student
- Dashboard cá nhân
- Lịch sử thi thử/thi thật
- Đề thi yêu thích
- Thi thử (practice) và thi thật (official) với timer
- Luyện tập (Bailuyentap, LichSuluyentap)
## Vai trò của tôi
- **Frontend Developer**: Thiết kế và implement toàn bộ UI/UX với React 19 + Ant Design.
- Xây dựng role-based authentication (AuthContext, hooks, protected routes).
- Phát triển components tái sử dụng: tables, modals, filters, pagination, charts.
- Tích hợp API services (axios) cho CRUD operations trên users/classes/exams/questions/students.
- Tạo layouts responsive cho 3 roles với custom CSS.
- Chụp và organize screenshots cho documentation.
- Deploy demo trên Vercel với vercel.json config.
- Ensure error handling, loading states, và performance với Vite.
