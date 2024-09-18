# **FiXit Web Application**

FiXit is a React-based web application that features a dynamic homepage, an About Us section, and a secure login page utilizing Google Authentication powered by Firebase.

## **Project Overview**

The FiXit web app allows users to easily navigate through various pages, including the **Home**, **About Us**, and **Login** sections. The integration of Google Login ensures a smooth and secure user experience, streamlining the authentication process.

## **Tech Stack**

- **Frontend**: React, React Router DOM
- **Authentication**: Firebase Google Authentication
- **Package Manager**: npm

## **Features**

- **Home Page**: Provides an overview and essential information about the app.
- **About Us Page**: Highlights the purpose and background of the application and its creators.
- **Login Page**: Users can securely sign in using their Google credentials, powered by Firebase Authentication.

## **Installation**

### **Prerequisites**

Ensure you have the following installed:

- **Node.js** (v16.x or later)
- **npm** (v7.x or later)

### **Setup Steps**

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/fixit-webapp.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd fixit-webapp
   ```

3. **Install project dependencies**:

   ```bash
   npm install
   ```

4. **Set up Firebase**:

   - Visit [Firebase Console](https://console.firebase.google.com/).
   - Create a new Firebase project.
   - Navigate to **Authentication** in the Firebase Console and enable Google Sign-In as a sign-in method.
   - Replace the placeholders in `src/firebase.js` with your Firebase config details.

5. **Start the development server**:

   ```bash
   npm start
   ```

6. **Open the app** in your browser:

   ```bash
   http://localhost:3000
   ```

## **Usage**

- Navigate between the **Home**, **About Us**, and **Login** pages.
- Use Google authentication to sign in from the **Login** page.

## **Commit History**

### **First Commit**: Initial Structure

- Established the base structure of the React application.
- Implemented routing using `react-router-dom` for smooth navigation between **Home**, **About Us**, and **Login** pages.

### **Second Commit**: Implemented GMAIL Login

- Integrated Firebase to handle authentication.
- Added Google Login functionality using `react-google-login` and Firebase, allowing users to securely sign in with their Google accounts.

