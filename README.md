Messenger webApp with Firebase Database
This is a simple messenger app that utilizes Firebase as the backend database. Users can log in using their email address in the format name@gmail.com to view and send messages. Additionally, they can add a custom name (e.g., name@pro) to the email address to create a unique login.

Getting Started
Follow these steps to set up and run the messenger app:

Prerequisites
Create a Firebase project on the Firebase Console.
Set up Firebase Authentication with email and password.
Installation
Clone this repository to your local machine.
bash
Copy code
git clone https://github.com/yourusername/messenger-app.git
Create a Firebase web app in your Firebase project.

Copy the Firebase configuration object from your project settings and replace the placeholders in the JavaScript code with your own Firebase project details. The code can be found in firebase.js.

javascript
Copy code
var firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};
Set up Firebase Realtime Database, and update the rules to allow read and write permissions for your application. Be cautious about your security rules.
Usage

Sign in with an email address in the format name@gmail.com, and you can add a custom name (e.g., name@pro) to the email address to create a unique login.

Start sending and receiving messages.



Acknowledgments
Thanks to Firebase for providing a robust backend for this app.
