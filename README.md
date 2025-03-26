# 📚 Study Planner

A modern, intuitive web application designed to help students manage their academic life efficiently. Track your tasks, exams, and class schedules all in one place.

🔗 **Live Demo**: [Study Planner](https://studyplanner3.onrender.com/index.html)

## ✨ Features

### 📋 Task Management
- Create and track academic tasks
- Set due dates and time slots
- Categorize tasks by subject and type
- Real-time task deletion and updates

### 📅 Exam Scheduling
- Schedule and manage exams
- Track exam details including:
  - Module numbers
  - Room numbers
  - Seat assignments
  - Duration
  - Start times

### 📊 Dashboard
- Overview of daily activities
- Quick stats for tasks and exams
- Intuitive calendar view
- Easy navigation between different views

### 📆 Calendar Views
- Monthly calendar view
- Weekly schedule view
- Daily task overview
- Visual indicators for tasks and exams

## 🛠️ Technologies Used

### Frontend
- HTML5
- Tailwind CSS
- JavaScript (Vanilla)
- Font Awesome Icons
- Flatpickr (for date/time picking)

### Backend
- Python 3.11
- Flask Framework
- SQLAlchemy (ORM)
- PostgreSQL (Production)
- SQLite (Development)

### Deployment
- Frontend: Render (Static Site)
- Backend: Render (Web Service)
- Database: Render PostgreSQL

## 🚀 Getting Started

### Prerequisites
- Python 3.11 or higher
- Web browser (Chrome/Firefox/Safari)

### Local Development
1. Clone the repositories:
   ```bash
   git clone https://github.com/YourUsername/StudyPlanner.git
   git clone https://github.com/YourUsername/StudyPlannerBackend.git
   ```

2. Backend Setup:
   ```bash
   cd StudyPlannerBackend
   pip install -r requirements.txt
   python init_db.py
   python app.py
   ```

3. Frontend:
   - Open the HTML files in a web browser
   - Or use a local server like Live Server in VS Code

## 📱 Features by Page

### Dashboard (index.html)
- Overview of today's tasks and exams
- Quick task creation
- Task categorization by subject

### Calendar View (calendar.html)
- Weekly view of tasks and exams
- Visual task organization
- Quick task deletion

### Monthly View (month.html)
- Monthly calendar overview
- Task and exam distribution
- Easy navigation between months

### Exam Management (exams.html)
- Comprehensive exam scheduling
- Exam detail management
- Room and seat tracking

### Timetable (timetable.html)
- Weekly class schedule
- Subject-wise organization
- Time slot management

## 🔒 Environment Variables
- `FLASK_ENV`: Set to 'production' in deployment
- `DATABASE_URL`: PostgreSQL connection string (production)
- `PYTHON_VERSION`: 3.11.0

## 👥 Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments
- Tailwind CSS for the beautiful UI components
- Flask community for the excellent documentation
- Render for hosting services 
