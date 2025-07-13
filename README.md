# 🕒 Employee Attendance & Training Monitoring System

A secure and intelligent employee attendance tracking system that also manages work modes (online/offline), monitors training progress, and provides a role-based dashboard for HR/Admins.

---

## 📌 Features

- ✅ **Employee Attendance Management**  
  Mark and manage daily attendance with timestamps, including late entries or absences.

- 🌐 **Online/Offline Work Mode Tracking**  
  Keep track of employees working remotely or from the office with daily mode logs.

- 🎓 **Training Progress Monitoring**  
  Assign training modules and track employees’ completion, feedback, and performance.

- 🔐 **Secure Role-based Dashboard**  
  Admin and Employee dashboards with different access levels using secure login authentication.

- 📊 **Analytics and Reports**  
  Generate attendance reports, training progress summaries, and performance insights.

---

## 🏗️ Tech Stack

| Technology     | Description                              |
|----------------|------------------------------------------|
| **Frontend**   | React.js + TailwindCSS                   |
| **Backend**    | Node.js + Express                        |
| **Database**   | MySQL / MongoDB (configurable)           |
| **Auth**       | JWT-based Auth with Role Validation      |
| **Deployment** | Render / Railway / Vercel                |

---

## 🔐 Roles and Access

| Role       | Access Rights                                                                 |
|------------|--------------------------------------------------------------------------------|
| **Admin**  | Manage employees, view analytics, assign training, track work modes           |
| **Employee** | Mark attendance, switch work mode, view training status                      |

---

## 🚀 Getting Started

### Prerequisites

- Node.js & npm
- MySQL or MongoDB
- Git

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/employee-attendance-system.git
   cd employee-attendance-system
   ```
2. **Install dependencies**
```bash  # Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```
3. **Set up environment variables**
**Create .env files in both backend and frontend directories.

Example for backend .env:***
```bash
PORT=5000
DB_URI=your_database_uri
JWT_SECRET=your_jwt_secret
```

**📁 Project Structure**
```bash
employee-attendance-system/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── utils/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   └── services/
│
└── README.md
```
**📸 Screenshots**
