# **Ecommerce-Follow-Along**

This repository is for the mentor-led project where we are building an e-commerce application using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The project focuses on learning real-world development concepts and gaining hands-on experience in creating a full-stack application.

---

## **Milestone 1: Project Overview**

### **Project Description**
- The aim of this project is to develop a functional e-commerce application with features like user authentication, product management, and order handling.  
- The application will be built using the MERN stack, which enables full-stack development using JavaScript for both frontend and backend.  

### **What We Covered in the Session**
1. **Understanding the MERN Stack**  
   - **MERN** stands for **MongoDB, Express.js, React.js, and Node.js**.  
   - It is a popular stack for creating full-stack applications because it uses JavaScript throughout the project.  

2. **REST API Basics**  
   - A REST API allows the frontend and backend to communicate using HTTP methods (like GET, POST, PUT, DELETE).  
   - In this project, REST APIs will handle user authentication, product management, and order updates.  

3. **Database Schema Design**  
   - Schema design in **MongoDB** helps organize and structure the data for the application effectively.  

4. **Role of Authentication**  
   - Authentication ensures secure access by verifying users before allowing them to log in or make purchases.

---
>>>>>>> 833e7a9a5bbb76e2b811b60fb7132e5824599717




## **Milestone 2: Project Overview**

## **Project Description**
-This milestone focused on setting up the foundational structure of the e-commerce application and creating a  functional and styled Login Page.
-The milestone emphasized using the MERN stack with an organized folder structure, modern styling tools like Tailwind CSS, and environment variables for efficient development.

### **What We Covered in the Session**
1. **Project Folder Structure**
    -Organized the project into two main directories:
        .Frontend: Contains the React application to build the user interface.
        .Backend: Houses the Node.js server for handling API requests and logic.
    -This separation ensures scalability and ease of maintenance.

2. **Setting Up React for Frontend**
    -React App Initialization:
        .Used create-react-app to initialize the frontend project.
    -Routing:
        .Added routing using react-router-dom to handle navigation between pages in the application.
    -Login Page Creation:
        .Designed a Login Page with input fields for Email and Password.
        .Used Tailwind CSS for responsive and clean styling.

3.  **Configuring Node.js for Backend**
    -Basic Server Setup:
        .Set up a basic Express.js server to handle API  requests and serve static files.
    -Environment Variables:
        .Used the dotenv package to manage sensitive data (e.g., API keys, admin privileges).
    -API Route for Login:
        .Created a placeholder API route (/api/login) to prepare for future backend logic.

4. **Integrating Tailwind CSS**
    -Added Tailwind CSS to the React project for modern, utility-based styling.
    -Configured Tailwind to ensure responsiveness across different screen sizes.

5. **Role of the Login Page**
    -The Login Page is the starting point for user authentication in the e-commerce application.
    -Validates user input and prepares for integration with backend APIs for authentication.


## Milestone 3: Project Setup for Backend

### What Was Achieved
- **MongoDB Setup**:
  - Connected to MongoDB Atlas with a cluster created using GitHub authentication.
  - Configured the database user and network access.
- **Backend Folder Structure**:
  - Organized backend into `config`, `routes`, and `models`.
- **Server Setup**:
  - Built a Node.js server using Express.js.
  - Configured dotenv for environment variables.
- **Database Connection**:
  - Established a connection to MongoDB using Mongoose.
- **Error Handling**:
  - Added middleware for basic error handling.

### Key Features
- Fully functional Express server running on port 5000.
- API endpoint `/api/users` that responds with a test message.



## **Milestone 5: Creating the Sign-Up Page**

## **Project Description**
- This milestone focused on adding a functional and user-friendly Sign-Up Page to the frontend of the e-commerce application.
- The goal was to allow new users to register by entering their details, such as name, email, and password, while ensuring proper validation of inputs.
- This milestone built upon the existing structure established in previous milestones, utilizing the MERN stack, Tailwind CSS, and React Router.

### **What We Covered in the Session**
1. **Enhancing the Frontend**
   - Added a **Sign-Up Page** component to the frontend:
     - Includes input fields for **Name**, **Email**, and **Password**.
     - Styled the form using **Tailwind CSS** for responsiveness and a modern look.
     - Included a navigation link on the Login Page to redirect users to the Sign-Up Page.

2. **Form Validation**
   - Implemented basic validation to ensure:
     - Name is not empty.
     - Email is in a valid format (e.g., `example@domain.com`).
     - Password meets security requirements (e.g., minimum length).
   - Form validation prevents invalid data from being submitted to the server.

3. **React Router Integration**
   - Added a new route (`/sign-up`) in the application for the Sign-Up Page.
   - Ensured smooth navigation between the Login Page and the Sign-Up Page via the "Sign Up" button/link.

4. **Updating the App Structure**
   - Created a new component: `SignUp.jsx` (in the `components/Auth` folder) for the Sign-Up Page.
   - Updated the `Routes.js` file to include the new `/sign-up` route.
   - Updated the `App.jsx` file to render the Sign-Up Page as part of the application's routing.

5. **Importance of the Sign-Up Page**
   - The Sign-Up Page is crucial for user onboarding in the e-commerce application.
   - Provides a secure and clean interface for users to create an account.
   - Prepares for future backend integration to store and verify user data.

### **Steps Completed**
- Built a responsive Sign-Up Page with Tailwind CSS.
- Implemented form validation to ensure accurate user input.
- Integrated the Sign-Up Page with the existing application via React Router.
- Updated the Login Page to include a link to navigate to the Sign-Up Page.

### **Future Steps**
- Integrate the Sign-Up form with backend APIs for user registration.
- Enhance form validation with additional checks (e.g., password strength, email uniqueness).
- Add unit tests to ensure the functionality of the Sign-Up form.

---