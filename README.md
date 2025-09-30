# Chat App

A modern real-time chat application enabling instant messaging with multiple users across different chat rooms, built with cutting-edge web technologies.

## Overview

This web-based chat application provides seamless real-time communication capabilities using WebSocket technology. Users can create and join chat rooms, send instant messages, and experience live updates without page refreshes. The application demonstrates proficiency in real-time data synchronization and modern full-stack development practices.

## Key Features

- **Real-time Messaging**: Instant message delivery using Socket.io WebSocket connections
- **Multiple Chat Rooms**: Create, join, and switch between different chat rooms
- **User Management**: User authentication and active user tracking
- **Live User Status**: See who's online and in which rooms
- **Message History**: Persistent storage of chat messages in MongoDB
- **Typing Indicators**: Real-time typing status indicators
- **User Notifications**: Join/leave notifications and message alerts
- **Responsive UI**: Mobile-friendly chat interface
- **Private Messaging**: One-on-one direct messaging capability
- **Emoji Support**: Rich emoji picker for expressive communication

## Technologies Used

### Frontend
- **React**: Dynamic UI components and state management
- **Socket.io-client**: Real-time bidirectional communication
- **React Hooks**: Modern state and lifecycle management
- **CSS Modules/Styled Components**: Component-scoped styling
- **Axios**: HTTP requests for REST API calls

### Backend
- **Node.js**: Asynchronous event-driven server
- **Express**: Lightweight web framework
- **Socket.io**: WebSocket library for real-time features
- **MongoDB**: Document database for message and user storage
- **Mongoose**: MongoDB ODM
- **JWT**: Secure authentication
- **bcrypt**: Password hashing

## Project Structure

```
chat-app/
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/      # Chat UI components
│   │   ├── pages/           # Main pages (Login, Chat, Rooms)
│   │   ├── socket/          # Socket.io client configuration
│   │   ├── context/         # React context for global state
│   │   └── utils/           # Helper functions
│   └── public/
├── server/                 # Node.js backend
│   ├── controllers/        # Route handlers
│   ├── models/             # Database models
│   ├── routes/             # API endpoints
│   ├── socket/             # Socket.io server logic
│   ├── middleware/         # Authentication middleware
│   └── config/             # Server configuration
└── docs/                   # Documentation
```

## My Contributions

- **Real-time Features**: Built complete Socket.io implementation for bidirectional real-time communication
- **Message Persistence**: Designed and implemented MongoDB schema for efficient message storage and retrieval
- **Room Management**: Created dynamic room creation and management system
- **UI Development**: Designed intuitive chat interface with smooth user experience
- **Socket Event Handling**: Implemented comprehensive event system for all chat interactions
- **Performance Optimization**: Optimized WebSocket connections and message delivery for scalability

## Installation & Setup

1. Clone the repository
2. Install dependencies for both client and server
3. Configure environment variables (MongoDB URI, JWT secret)
4. Start MongoDB service
5. Run server and client development servers concurrently

## Features in Detail

### Chat Functionality
- Send and receive messages in real-time
- Message timestamps and sender information
- Scroll to view message history
- Auto-scroll to latest messages

### Room Features
- Create new chat rooms
- Browse available rooms
- Join/leave rooms dynamically
- See active users in each room

### User Experience
- Smooth animations and transitions
- Loading states and error handling
- Responsive design for all devices
- Clean and modern UI

## Technical Highlights

- **WebSocket Architecture**: Efficient bi-directional communication with minimal latency
- **Event-Driven Design**: Clean separation of socket events and handlers
- **State Synchronization**: Consistent state across all connected clients
- **Connection Management**: Automatic reconnection and connection status handling
- **Scalable Design**: Architecture ready for horizontal scaling

## Future Enhancements

- File and image sharing
- Video/voice calling integration
- Message encryption
- Advanced user roles and permissions
- Message search functionality
- Rich text formatting
- Read receipts
- Push notifications

---

*This project demonstrates expertise in real-time web applications, WebSocket technology, and modern full-stack development.*
