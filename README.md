# Real-Time Collaborative Code Editor

![CodeSync Logo](https://your-logo-url.com/logo.png)  <!-- Replace with actual logo URL -->

A real-time collaborative code editor that allows multiple users to write and edit code simultaneously. Built with React, Node.js, and Socket.io, this application is perfect for pair programming, coding interviews, or collaborative learning.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Real-Time Collaboration:** Multiple users can edit code in real-time, seeing each other's changes instantly.
- **User Avatars:** Each user is represented by an avatar generated from their username.
- **Room Management:** Create or join rooms using unique Room IDs.
- **Code Synchronization:** Code updates are synchronized across all connected clients seamlessly.
- **Responsive Design:** Fully responsive layout suitable for different screen sizes.

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

## Installation

### Prerequisites

- Node.js (>= 14.x)
- npm (or yarn)

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/real-time-code-editor.git
   cd real-time-code-editor
