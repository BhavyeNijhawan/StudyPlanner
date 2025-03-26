# Study Planner

A web-based study planner application that helps you manage your tasks, classes, and exams with a calendar view.

## Features

- Create and manage tasks with details like subject, type, and due date
- View tasks in a daily dashboard
- Weekly calendar view with task visualization
- Add custom subjects
- Delete tasks

## Setup Instructions

### Backend Setup

1. Make sure you have Python 3.8+ installed
2. Navigate to the backend directory:
   ```bash
   cd backend
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   - Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - Unix/MacOS:
     ```bash
     source venv/bin/activate
     ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Run the Flask application:
   ```bash
   python app.py
   ```
   The backend server will start at http://localhost:5000

### Frontend Setup

The frontend is static HTML/JavaScript and doesn't require any build steps. Simply:

1. Open `index.html` in your web browser to access the dashboard
2. Click on the calendar icon in the sidebar to switch to the calendar view

## Usage

1. **Adding Tasks**:
   - Click the "New Task" button on the dashboard
   - Fill in the task details in the popup form
   - Click "Save" to create the task

2. **Viewing Tasks**:
   - Dashboard shows today's tasks
   - Calendar view shows tasks for the entire week
   - Use the navigation arrows to move between weeks

3. **Deleting Tasks**:
   - Click the trash icon next to a task to delete it

4. **Adding Subjects**:
   - Click the "+" button next to the subject dropdown when creating a task
   - Enter the new subject name
   - Click "Add" to add it to the list

## Tech Stack

- Frontend: HTML, JavaScript, TailwindCSS
- Backend: Python, Flask, SQLite
- Additional libraries: Flatpickr for date picking 