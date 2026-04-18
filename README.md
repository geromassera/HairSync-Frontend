# HairSync - Management System Frontend 💇‍♂️📱

This is the web-based client for the **HairSync** ecosystem. It provides a modern, intuitive, and responsive interface for professional stylists and salon administrators to manage appointments, services, and client relationships in real-time.

## 🌟 Features
- **Interactive Dashboard:** Real-time overview of daily and weekly schedules.
- **Dynamic Appointment Booking:** Seamless scheduling flow with instant feedback.
- **Role-Based Views:** Custom interfaces for Administrators (full control) and Employees (schedule management).
- **Secure Authentication:** Integrated JWT handling with persisted sessions and protected routes.
- **Responsive Design:** Optimized for desktop and mobile devices to allow on-the-go management.

## 🛠️ Tech Stack
- **Library:** React (TypeScript)
- **State Management:** Context API / Hooks
- **HTTP Client:** Axios (Interceptors for JWT injection)
- **Routing:** React Router v6
- **Styling:** CSS Modules / Tailwind CSS (Ajustar según lo usado)
- **Build Tool:** Vite / Create React App (Ajustar según lo usado)

## 🏗️ Architecture & Patterns
The frontend is structured to follow professional development standards:

- **Component-Driven Development:** Reusable and modular UI components.
- **Services Layer:** Abstracted API calls using Axios to keep components clean of business logic.
- **Custom Hooks:** Encapsulated logic for authentication, data fetching, and form handling.
- **Guarded Routes:** Implementation of higher-order components (HOCs) or wrappers to protect sensitive views based on user roles.

## 🔐 Frontend Security
- **JWT Management:** Secure storage and automatic injection of tokens in request headers.
- **Role-Based Access Control (RBAC):** Frontend-level enforcement of permissions to ensure a consistent user experience.
- **Data Validation:** Client-side validation to improve UX before sending data to the backend.

## ⚙️ Setup & Installation

1. **Clone the repository:**
   ```
   git clone [https://github.com/geromassera/HairSync-Frontend.git](https://github.com/geromassera/HairSync-Frontend.git)

2. **Install dependencies:**
   ```npm install ```
   
4. **Configure Environment:**
Create a .env file and set your Backend API URL:
   ```VITE_API_URL=https://localhost:XXXX/api```

5. **Run the application:**
  ```npm run dev```
## 👥 Collaborators
This project was developed as part of a degree project at **Universidad Tecnológica Nacional (UTN)** by:
- [Gerónimo Massera](https://github.com/geromassera) - Full-Stack
- [Nicolas Boscia](https://github.com/NicoBoscia) - Full-Stack
- [Nicolas Admet](https://github.com/nicoadmet) - Full-Stack

---
*Special thanks to our tutors at UTN for their guidance during the development of this project.*
