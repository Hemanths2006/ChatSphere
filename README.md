live website https://hemanths2006.github.io/ChatSphere/


ChatSphere

ChatSphere is a modern, real-time chat web application that enables seamless communication using Firebase Realtime Database. It features a sleek, animated UI, responsive design, and dynamic message handling.

Features

Username Authentication: Users enter a username before accessing chat, stored locally.

Real-time Messaging: Messages update instantly without refreshing, using Firebase Realtime Database.

Animated UI: Smooth transitions and effects for an engaging chat experience.

Responsive Design: Fully optimized for desktop and mobile devices.

User-friendly Interface: Styled chat bubbles, input fields, and interactive buttons.

Error Handling: User-friendly messages for Firebase errors.

Keyboard Shortcuts: 'Enter' key to send messages.

Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Firebase Realtime Database

Styling: CSS (with framework support if needed)

Storage: Local Storage for username persistence

Setup Instructions

Clone the repository:

git clone https://github.com/your-username/ChatSphere.git
cd ChatSphere

Open index.html in a browser or use a local server for development.

Configure Firebase:

Create a Firebase project at Firebase Console

Enable Realtime Database

Replace the Firebase configuration in firebase-config.js with your project details.

Run the application and start chatting!

Project Structure

ChatSphere/
│── index.html       # Main chat UI
│── styles.css       # Styling and animations
│── script.js        # Chat functionality
│── firebase-config.js # Firebase setup
│── README.md        # Project documentation

Future Enhancements

User authentication with Firebase Authentication.

Message timestamps.

Private chat rooms.

Custom themes.

License

This project is licensed under the MIT License.
