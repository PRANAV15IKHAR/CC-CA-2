PranavIkhar-CC-CA2-Activity
This project consists of a React.js front-end application (my-app) and a Spring Boot-based back-end split into two modules (Backend-1 and Backend-2). The project is designed to manage student information, including details and registration data, with MongoDB Atlas as the database.

Features
Student Details Page

Displays student details (name, address, phone number).
Back-end handled by Backend-1 (deployed to Render).
Student Registration Page

Enables adding new student data with fields: name, placement status, and CGPA.
Back-end handled by Backend-2 (deployed to Render).
React Front-End (my-app)

Front-end app built with React.js to provide an intuitive UI for the above functionalities.
Project Structure
my-app/: React.js front-end application.
Backend-1/: Spring Boot application handling student details.
Backend-2/: Spring Boot application handling student registration.


Setup Instructions
Prerequisites
Node.js and npm installed.
Java 17 or later.
MongoDB Atlas cluster set up and ready.
Git installed on your system.

Steps to Run
Clone the Repository

Navigate to Backend-1 and Backend-2 folders.
Open application.properties in each folder and update the MongoDB Atlas URI with your credentials:
properties
Copy code
spring.data.mongodb.uri=mongodb+srv://<username>:<password>@<cluster-url>/<database-name>
Build and run each back-end module:

# Backend-1
cd Backend-1
./mvnw spring-boot:run
# Backend-2
cd ../Backend-2
./mvnw spring-boot:run

Set Up Front-End
Navigate to the my-app folder:
cd ../my-app
Install dependencies:
npm install
Start the React application:
npm start
Access the Application


Deployment
Back-End:
Both Backend-1 and Backend-2 are deployed on Render.
Update the API endpoints in the React app (my-app/src) to point to the Render URLs of Backend-1 and Backend-2.

Front-End:
Deploy my-app to Netlify or any other hosting platform.
Technologies Used
Front-End: React.js
Back-End: Spring Boot (Java)
Database: MongoDB Atlas
Hosting Platforms: Render, Netlify (or similar)


