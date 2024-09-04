
# React WebRTC Video Call App

This project is a real-time video calling application built using React for the frontend and WebRTC with Socket.io for real-time communication. The app allows users to create or join rooms and start video calls with others in the same room.

## Features

- **Real-Time Video & Audio Communication**: High-quality video and audio streaming using WebRTC.
- **Room-Based Communication**: Users can create or join rooms for private video calls.
- **Socket.io Integration**: Real-time signaling and communication between peers for establishing WebRTC connections.
- **React Frontend**: Modern, responsive UI built with React.
- **Responsive Design**: Works on both desktop and mobile devices.
- **User-Friendly Interface**: Simple and intuitive UI for easy navigation.

## Tech Stack

- **Frontend**: React, HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Real-Time Communication**: WebRTC, Socket.io
- **Deployment**: [Specify deployment platform like Heroku, Vercel, etc.]

## Getting Started

### Prerequisites

- **Node.js**: Ensure Node.js is installed on your machine.
- **npm**: Node package manager is required to install dependencies.

### Installation

1. Clone the repository:


   git clone https://github.com/OrneyVortex/React-webRTC.git
   cd React-webRTC
  

2. Install dependencies for both client and server:


   # Navigate to client directory and install dependencies
   cd client
   npm install
   
   # Navigate to server directory and install dependencies
   cd ../server
   npm install


3. Start the server:

   npm start


   The server will run on \`http://localhost:8001\`.

4. Start the client:


   cd ../client
   npm start


   The client will typically run on \`http://localhost:3000\`.

### Usage

- **Create a Room**: Click on the "Create Room" button to generate a unique room ID.
- **Join a Room**: Enter an existing room ID to join a video call.
- **Share the Room ID**: Share the room ID with others to have them join your call.
- **Start Video Call**: Once in the room, your video and audio stream will be shared with others in the room.

## How It Works

1. **Signaling**: Socket.io is used for signaling between peers to establish the WebRTC connection.
2. **Peer Connection**: WebRTC handles the peer-to-peer connection for video and audio streaming.
3. **Room Management**: Each room is identified by a unique ID, allowing multiple calls to take place simultaneously without interference.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For any questions or suggestions, please reach out at [rahuloverhere999@gmail.com].
