# Attendance Management System

A Full Stack Attendance Management System designed to streamline employee attendance tracking and management. The application provides secure authentication, employee management, attendance recording, and report generation capabilities.

## Features

- Employee Attendance Tracking
- Admin Authentication (JWT)
- Employee Management
- Attendance Report Generation
- Excel Export Functionality
- Daily Attendance Monitoring
- PIN Verification
- Location-Based Attendance Support
- Responsive User Interface
- Secure Backend APIs

## Tech Stack

### Frontend
- React.js
- React Router
- Tailwind CSS
- Vite

### Backend
- Node.js
- Express.js
- JWT Authentication
- Bcrypt.js

### Database
- Supabase

### Other Tools
- XLSX (Excel Report Generation)
- Netlify (Deployment)

## Project Structure

```
Attendance_System/
│
├── frontend/
│   └── attandance-marker/
│
├── backend/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   └── config/
│
└── netlify.toml
```

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Attendance_System.git
cd Attendance_System
```

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend/attandance-marker
npm install
npm run dev
```

## Environment Variables

Create a `.env` file inside the backend folder and add:

```env
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

JWT_SECRET=your_jwt_secret

ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
```

## Future Enhancements

- QR Code Attendance
- Face Recognition Attendance
- Email Notifications
- Attendance Analytics Dashboard
- Leave Management System
- Mobile Application

## Author

Sathwika Anumula

## License

This project is developed for educational and portfolio purposes.
