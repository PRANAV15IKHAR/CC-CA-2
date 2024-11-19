# **PranavIkhar-CC-CA2-Activity**

This project is a **full-stack application** combining a **React.js front-end** and a **Spring Boot-based back-end**, split into two modules (**Backend-1** and **Backend-2**). It manages student information, including details and registration data, using **MongoDB Atlas** as the database.

---

## **Features**

### 1. **Student Details Page**
- Displays student information: **name**, **address**, and **phone number**.
- Back-end functionality handled by **Backend-1** (deployed to Render).

### 2. **Student Registration Page**
- Enables adding new student data, including fields for **name**, **placement status**, and **CGPA**.
- Back-end functionality handled by **Backend-2** (deployed to Render).

### 3. **React Front-End (my-app)**
- User-friendly **React.js** front-end for seamless interaction with both features.

---

## **Project Structure**
- **my-app/**: React.js front-end application.
- **Backend-1/**: Spring Boot application managing student details.
- **Backend-2/**: Spring Boot application managing student registration.

---

## **Deployment**

### **Back-End**
- Both **Backend-1** and **Backend-2** are deployed on **Render**.
- Ensure the React app's API endpoints (`my-app/src`) point to the Render URLs of these back-end modules.

### **Front-End**
- Deploy **my-app** to **Netlify** or any other hosting platform.

---

## **Technologies Used**

- **Front-End**: React.js
- **Back-End**: Spring Boot (Java)
- **Database**: MongoDB Atlas
- **Hosting Platforms**: Render, Netlify (or similar)
