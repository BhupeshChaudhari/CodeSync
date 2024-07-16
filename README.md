# SimulCode - Real Time Code Editor

A real-time collaborative code editor that allows multiple users to write and edit code simultaneously. Built with React, Node.js, and Socket.io, this application is perfect for pair programming, coding interviews, or collaborative learning.

## Features

- **Real-Time Collaboration :** Multiple users can edit code in real-time, seeing each other's changes instantly.
- **User Avatars :** Each user is represented by an avatar generated from their username.
- **Room Management :** Create or join rooms using unique Room IDs.
- **Code Synchronization :** Code updates are synchronized across all connected clients seamlessly.
- **Responsive Design :** Fully responsive layout suitable for different screen sizes.

## Technologies Used

- **Frontend:**
  - React
  - React Router
  - CodeMirror for code editing
  - Socket.io for real-time communication

- **Backend:**
  - Node.js
  - Express
  - Socket.io for handling WebSocket connections

- **Styling:**
  - CSS
  - Custom themes (e.g., Dracula theme for CodeMirror)

### Steps

1. Clone the repository:
```
   git clone https://github.com/yourusername/real-time-code-editor.git
   cd real-time-code-editor
```

2. Navigate to the backend folder and install dependencies:
```
   cd server
   npm install
```

3. Navigate to the frontend folder and install dependencies:
```
    cd ../client
    npm install
```

4. Start the server:
```
  cd ../server
  npm start
```

5. Start the frontend:
```
  cd ../client
  npm start
```

## Usage

- **Creating a Room** : Enter a username and click on "Create a new room" to generate a Room ID.
- **Joining a Room** : Paste an existing Room ID and enter a username to join the collaborative coding session.
- **Real-Time Editing** : Start coding! Changes will be reflected in real-time for all users in the room.

