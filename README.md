# 🚀🔥 Super Admin Application 🔥🚀

## Overview
This Super Admin Application is designed to manage admins, doctors, and their accessible features within a healthcare-related environment. It allows a super admin to add and manage admin users, doctors, and assign features accessible to each role. The super admin can also create new features dynamically.

The application provides a centralized control system where the super admin can oversee and configure access rights and information for admins and doctors efficiently.

---

## 🚀Features
- Add, update, and manage Admin user details.
- Add, update, and manage Doctor details.
- Define and assign features that admins can access.
- Define and assign features that doctors can access.
- Create new features and assign them dynamically.
- Manage scan centers and metadata related to the healthcare domain.
- Role-based access control ensuring secure feature assignment.

---

## Technologies Used
- **Frontend:** React.js, JavaScript
- **Backend:** Ruby on Rails
- **Styling:** CSS (or any other styling library you use)
- **API:** RESTful APIs connecting frontend and backend

---

## Installation and Setup

### Prerequisites
- Node.js and npm installed (for frontend)
- Ruby and Rails installed (for backend)
- Database setup (e.g., PostgreSQL, MySQL, or SQLite)

### Backend Setup
1. Navigate to the backend directory:
    ```bash
    cd backend
    ```
2. Install dependencies:
    ```bash
    bundle install
    ```
3. Setup database:
    ```bash
    rails db:create
    rails db:migrate
    rails db:seed # if you have seed data
    ```
4. Start the Rails server:
    ```bash
    rails server
    ```

### Frontend Setup
1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the React development server:
    ```bash
    npm start
    ```
4. Open your browser and visit:
    ```
    http://localhost:3000
    ```

---

## Usage
- Log in as the Super Admin.
- Use the sidebar to navigate between Admins, Doctors, Scan Centers, Features, and Metadata.
- Add or edit records using the provided forms.
- Assign features to admins and doctors according to your organization’s needs.

---


