# TaskFlow – Task Management Tool

TaskFlow is a modern **task management web application** designed to help individuals and teams organize, track, and prioritize their work efficiently. It comes with a **dashboard overview**, task statistics, and management of tasks with different statuses.

---

## Features

### Dashboard
- Overview of all tasks and their current status.
- Task statistics: total tasks, completed, pending, and in-progress.
- Task progress visualization.
- Recent activity log for easy tracking.

### Task Management
- Add new tasks with the following attributes:
  - Title
  - Description
  - Priority (High, Medium, Low)
  - Due Date
  - Status (Pending, In-progress, Completed)
- Edit or delete existing tasks.

### Pending Tasks
- View all pending tasks separately.
- Sort tasks by:
  - Due date
  - Priority

### Completed Tasks
- View all completed tasks.
- Monitor progress and history of finished tasks.

---

## Tech Stack

**Frontend**
- React (with React Router)
- Tailwind CSS
- Material UI / Lucide Icons
- Axios for API calls

**Backend**
- Node.js + Express
- MongoDB (Atlas)
- JWT Authentication
- Bcrypt for password hashing
- Cors & Body-parser

---

## Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/naisha-khan/TaskFlow.git
cd TaskFlow
