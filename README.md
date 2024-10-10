### Table of Contents
#### Features
#### Technologies Used
#### Project Structure
#### Setup Instructions
#### Environment Variables
#### Available Scripts
#### Future Improvements

## Features
Firebase Authentication for secure admin login.
Firestore to manage content (CRUD: Create, Read, Update, Delete).
Admin Dashboard to view and manage content.
Responsive design with React Router for navigation.
Easy setup and integration with Firebase.
## Technologies Used
React – Front-end framework for building user interfaces.
Firebase – Used for authentication, database (Firestore), and hosting.
Firestore – NoSQL database for storing content.
React Router – For handling navigation in the app.

## Setup Instructions
Prerequisites
Node.js (v12 or higher)
npm (v6 or higher)
Firebase account (create one at Firebase Console)

## Steps to Set Up the Project
1.Clone the repository:
```bash
git clone https://github.com/your-username/cms-react-app.git
cd cms-react
```
2.Install dependencies:
```bash 
npm install
```
3.Create a Firebase project:

Go to Firebase Console, create a new project, and enable Authentication (Email/Password) and Firestore Database.
4. Add Firebase credentials:
 Edit .env file in the root of the project and add your Firebase credentials:
```bash
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```
## Available Scripts
In the project directory, you can run:

```bash
npm start
```
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

```bash
npm run build
```
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

### Future Improvements
#### Role-based Access: Allow multiple admin roles with different permissions.
#### Firebase Storage Integration: Manage media like images and files.
#### Content Types: Allow more complex content types (e.g., articles, pages, categories).
#### Cloud Functions: Implement server-side logic to handle advanced operations.


Firebase-Powered CMS
This project is a Content Management System (CMS) built using React and Firebase. It allows admin users to log in, manage content dynamically, and store the content in Firebase Firestore. Firebase Authentication is used for admin login, and Firebase Firestore handles CRUD operations for content.
