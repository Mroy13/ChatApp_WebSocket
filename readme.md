# WebSocket Chat Application

This is a real-time chat application built using Node.js, Express.js, Socket.IO for real-time communication, and EJS for server-side rendering.
This application utilizes EJS for server-side rendering, providing a flexible and dynamic user interface without relying on a specific frontend framework.
## Tech Stack

- Node.js
- Express.js
- Socket.IO
- EJS

## Features

- **Real-Time Communication**: Users can connect to specific rooms and chat in real-time.

## To-Do / Upcoming Features

1. **One-to-One Chatting**: Enable private messaging between users.
2. **Chat History Storage**: Implement storage for users to access previous conversations.
3. **Group Creation**: Allow users to create and join custom chat groups.


## How to Use

1. Clone the repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Install dependencies.

   ```bash
   npm install
   ```

3. Start the server.

   ```bash
   npm start
   ```

4. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

5. Connect to a specific room using the endpoint.

   Example: [http://localhost:3000/chat/1/mroy13](http://localhost:3000/chat/1/mroy13)

## Endpoints

- `/chat/:roomid/:username`: Connect to a specific room by replacing `:roomid` with the desired room ID and `:username` with your username.

