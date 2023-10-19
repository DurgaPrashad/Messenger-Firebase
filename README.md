# Messenger webApp with Firebase Database

📱🔥 This is a simple messenger webapp that utilizes Firebase as the backend database. Users can log in using their email address in the format `name@gmail.com` to view and send messages. Additionally, they can add a custom name (e.g., `name@pro`) to the email address to create a unique login. ✉️✨

## Getting Started

### Prerequisites

1. Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).
2. Set up Firebase Authentication with email and password. 🔐

### Installation

1. Clone this repository to your local machine.

2. Create a Firebase web app in your Firebase project.

3. Copy the Firebase configuration object from your project settings and replace the placeholders in the JavaScript code with your own Firebase project details. The code can be found in `firebase.js`.

   ```javascript
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

Acknowledgments
Thanks to Firebase for providing a robust backend for this app. 🚀
