# Chat Application

This repository contains a Chat Application developed with a graphical user interface (GUI) for both server and client sides. The application allows multiple clients to connect to a server and exchange messages in a chat-like interface.

## Server Side

**ServerWithGUI.java**:

- This class represents the server-side code of the Chat Application.
- It establishes a server socket and listens for incoming client connections.
- The server maintains a list of connected clients, manages user additions and removals, and facilitates communication between clients.
- The server also supports private messaging between clients.

## Client Side

**ClientWithGUI.java**:

- This class represents the client-side code of the Chat Application.
- It provides a graphical user interface for users to connect to the server, send and receive messages, and interact with other connected users.
- Users can send messages to all connected users or send private messages to specific users.
- The client GUI also displays the list of online users.

## Running the Application

**Server Setup**:

1. Compile and run the `ServerWithGUI.java` file to start the server.
2. The server GUI will appear, indicating that it is waiting for client connections.

**Client Setup**:

1. Compile and run the `ClientWithGUI.java` file to start a client instance.
2. Enter the server IP address and port number in the respective fields.
3. Provide a unique username for the client and click the "Connect" button to establish a connection with the server.
4. Once connected, users can send messages in the chat area. They can also view online users, send private messages, and disconnect from the server using the provided buttons.

**Note**: Ensure that the server is running before attempting to connect any clients.

## Features

- **Multi-User Chat**: Multiple users can connect to the server and engage in group conversations.
- **Private Messaging**: Users can send private messages to specific individuals by prefixing the message with the recipient's username.
- **Online User List**: Clients can view the list of users currently online.
- **Connectivity Status**: The application provides feedback on the connection status, indicating whether the client is connected or disconnected from the server.

