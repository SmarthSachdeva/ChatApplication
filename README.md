# Realtime Chat Application using Node.js and Socket.IO

This is a simple Realtime Chat Application built with Node.js and Socket.IO. The application allows users to connect and chat with each other in real-time using websockets. It's a lightweight and efficient solution for implementing chat functionality in web applications.

## Features

- Realtime messaging: Users can send and receive messages instantly.
- Multiple Rooms: Users can join different chat rooms to have separate conversations.
- User Nickname: Users can choose a nickname to identify themselves in the chat.
- Typing Indicator: Shows when other users are typing in the current chat room.
- Message History: Stores and displays a limited number of previous messages for new users.

## Technologies Used

- Node.js: A JavaScript runtime for server-side development.
- Express.js: A minimal and flexible Node.js web application framework.
- Socket.IO: A library that enables real-time, bidirectional, and event-based communication between clients and the server.
- HTML and CSS: Frontend components for the chat interface.
- JavaScript: Client-side scripting for interacting with the server and updating the UI.
- npm: Node Package Manager for managing dependencies.

## Setup Instructions

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd realtime-chat-application`
3. Install dependencies: `npm install`
4. Start the server: `node app.js`
5. Open your web browser and access the application at `http://localhost:3000`

## How to Use

1. Enter a nickname in the welcome screen and click "Join Chat."
2. You'll be redirected to the chat page.
3. Choose a chat room from the list or create a new one.
4. Start typing your message in the input box and hit "Enter" to send.
5. Other users in the same room will see your message in real-time, and you'll see theirs.
6. You can switch to different rooms using the dropdown menu at the top.
7. When someone is typing, you'll see an indicator below their nickname.

## Future Improvements

1. Add user authentication to support private and personalized chats.
2. Implement message history pagination for better performance with large chat histories.
3. Enable file sharing and multimedia support.
4. Implement user avatars or profile pictures.
5. Add a notification system for new messages when a user is not active.
6. Improve the user interface to make it more user-friendly and responsive.

## NPM Commands

- To install project dependencies: `npm install`
- To start the application: `node app.js`
