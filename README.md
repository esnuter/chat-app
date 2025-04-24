# Real-Time Chat Application

A real-time chat application built with Flask and Socket.IO. Users can join with auto-generated usernames, send messages, update their usernames, and see notifications when others join/leave. Avatars are dynamically generated based on gender and username.

## Features
- Real-time messaging using WebSockets
- Auto-generated usernames and avatars
- Username updates (propagated to all users)
- Join/leave notifications
- Responsive UI with styled system messages

## What I Learned
- **Backend**:  
  - Integrated Flask with Socket.IO for real-time communication  
  - Managed user sessions and broadcasted events (connect/disconnect)  
  - Utilized external APIs for avatar generation  

- **Frontend**:  
  - Dynamically updated the UI using vanilla JavaScript  
  - Styled messages differently for sent/received/system notifications  
  - Implemented CSS variables for consistent theming  

- **Key Concepts**:  
  - WebSocket event handling (emit/listen)  
  - State synchronization across clients  
  - Error handling for user disconnections  

A simple yet practical project to explore real-time web fundamentals! 🚀
