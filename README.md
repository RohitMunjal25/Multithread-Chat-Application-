# Multithread-Chat-Application-
This is my first mini project in Java – a simple multithreaded chat application built using socket programming and Java threads. The goal was to understand client-server communication and how multithreading allows multiple clients to interact with the server simultaneously.

🛠️ Features
Real-time communication between multiple clients and a server

Server handles each client connection using a separate thread

Broadcast messages from one client to all connected clients

Clean console interface for sending and receiving messages

Basic input/output stream handling using BufferedReader and PrintWriter

🧠 What I Learned
Basics of socket programming (ServerSocket, Socket)

How to manage multiple threads using the Thread class

Synchronizing client interactions using shared server resources

Handling input/output streams in Java

Writing clean, modular code for a client-server architecture

🚀 How It Works
Server listens on a port and accepts incoming client connections.

Each client runs on a separate thread, allowing parallel communication.

Messages from one client are broadcasted to all others by the server.
