# Health Center Project

Welcome to the Health Center repository! This project is a comprehensive web application designed to manage healthcare services, appointments, and patient records. It includes both a frontend for users and an admin panel for healthcare providers and administrators.

---

## **Development Timeline**

The project was developed over the course of 15 days, with each day focusing on specific tasks and milestones. Below is a summary of the work completed on each day:

### **Day 1: Project Setup**
- Initialized the project using Vite with React for both frontend and admin modules.
- Installed necessary dependencies (React Router, Axios, Toastify, etc.).
- Created the basic folder and file structure for the project.

### **Day 2: Backend API Integration**
- Designed API endpoints for user authentication, booking appointments, and fetching doctor data.
- Created controllers for handling doctor and admin functionalities (`doctorController.js`).
- Integrated MongoDB for database management.

### **Day 3: Frontend - Appointment Booking**
- Developed the Appointment page (`Appointment.jsx`) for users to book appointments.
- Implemented functionality to fetch available slots from the backend and display them.
- Incorporated user authentication for booking appointments.

### **Day 4: Frontend - My Appointments**
- Built the My Appointments page (`MyAppointments.jsx`) to display user-specific bookings.
- Added functionality to fetch appointments and display details like date, time, doctor, and payment status.

### **Day 5: Admin Panel - Dashboard**
- Created the Admin Dashboard page to display key metrics like total appointments, doctors, and patients.
- Integrated API to fetch dashboard data (`Admin/Dashboard.jsx`).

### **Day 6: Admin Panel - Appointment Management**
- Developed the All Appointments page in admin panel (`Admin/AllAppointments.jsx`) for managing all bookings.
- Implemented actions for canceling appointments from the admin side.

### **Day 7: Doctor Panel - Dashboard**
- Designed the Doctor Dashboard page (`DoctorDashboard.jsx`) to show earnings, appointments, and patients count.
- Integrated functionality to fetch dashboard data and latest appointments.

### **Day 8: Doctor Panel - Appointment Management**
- Built the Doctor Appointments page (`DoctorAppointments.jsx`) for doctors to view and manage their bookings.
- Added actions to mark appointments as completed or canceled.

### **Day 9: Slot Booking Logic**
- Implemented logic to calculate available slots dynamically based on current date and time.
- Added functionality to book slots and update backend data accordingly.

### **Day 10: User Authentication**
- Integrated authentication for users, doctors, and admins with token-based access control.
- Enabled role-based navigation and access to specific pages.

### **Day 11: UI Enhancements**
- Improved UI across the project:
  - Enhanced responsiveness and styling for mobile and desktop views.
  - Added icons for better navigation and action visibility.

### **Day 12: Notifications and Error Handling**
- Incorporated Toastify for displaying notifications and error messages.
- Handled edge cases like appointment conflicts and invalid inputs.

### **Day 13: Testing and Bug Fixes**
- Conducted end-to-end testing for all modules.
- Fixed bugs in appointment booking and admin actions.

### **Day 14: Deployment**
- Prepared the project for deployment by optimizing code and assets.
- Deployed the application on the server.

### **Day 15: Documentation**
- Created detailed documentation for the project, including API usage and navigation guides.

---

## **Key Features**
- **Frontend**:
  - Browse available doctors and book appointments.
  - View and manage user-specific bookings.
  - Responsive design for seamless experience on all devices.

- **Admin Panel**:
  - View key metrics and manage appointments.
  - Role-based access for administrators.
  - Detailed appointment management system.

- **Doctor Panel**:
  - Dashboard to track earnings, appointments, and patients.
  - Manage individual appointments with actions like canceling or completing.

---

## **Technologies Used**
- **Frontend**: React, Vite, Axios, Toastify
- **Admin Panel**: React, Vite
- **Backend**: Node.js, Express.js, MongoDB
- **Styling**: Tailwind CSS

---

## **Getting Started**

To get started with the project, clone the repository and follow the instructions in the respective `README.md` files for the frontend and admin modules.

### **Frontend Setup**
1. Navigate to the `frontend` directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### **Admin Panel Setup**
1. Navigate to the `admin` directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

---

## **Contributing**

Contributions are welcome! Feel free to fork the repository and submit pull requests to improve the project.

---

## **License**

This project is licensed under the MIT License.
