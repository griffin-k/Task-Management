# Todo List App  

## Overview  
This is a simple and intuitive **Todo List Application** that helps users organize and manage their tasks efficiently. Users can log in, create categorized blocks for different types of work, and track tasks by status: **Pending**, **Started**, or **Completed**. Tasks and blocks can be added, edited, or deleted as needed, ensuring flexibility and usability.  

## Features  
- **User Authentication**: Secure login and personalized task management.  
- **Task Categorization**: Create blocks to organize tasks into different categories or types of work.  
- **Task Management**:  
  - Add, edit, or delete tasks within blocks.  
  - Track the status of tasks: **Pending**, **Started**, or **Completed**.  
- **Responsive Design**: Built with Tailwind CSS to ensure compatibility across devices.  
- **Real-time Updates**: All changes are synced instantly using Firebase Realtime Database.  

## Technologies Used  
- **Frontend**:  
  - HTML  
  - Tailwind CSS  
  - JavaScript  

- **Backend**:  
  - Firebase Realtime Database  

## Installation  

### Prerequisites  
Before you begin, ensure you have the following:  
- A modern web browser (e.g., Chrome, Firefox).  
- A Firebase account and project set up.  



### Set Up Firebase

Go to the Firebase Console.
Create a new project or use an existing one.
Enable the Realtime Database feature in the Firebase Console.
Obtain your Firebase configuration keys (API Key, Project ID, etc.).
Replace the placeholder content in firebase-config.js with your Firebase configuration:
   ```javascript

const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-auth-domain",
  databaseURL: "your-database-url",
  projectId: "your-project-id",
  storageBucket: "your-storage-bucket",
  messagingSenderId: "your-messaging-sender-id",
  appId: "your-app-id"
};
firebase.initializeApp(firebaseConfig);

  ```

Open the index.html file in your browser to launch the application.

### How to Use

**Log In**
- Use the login form to authenticate using your credentials.

**Create Blocks**
- Add blocks to categorize your tasks (e.g., "Work", "Personal", "Shopping").

**Add Tasks**
- Within each block, add tasks and set their initial status.

**Manage Tasks**
- Update the status of tasks to Pending, Started, or Completed.
- Edit or delete tasks or blocks as required.




