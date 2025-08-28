# Multithreaded-Chat-Application

COMPANY: CODTECH IT SOLUTIONS

NAME: DEEKSHA N C

INTERN ID: CT04DY1225

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION:
This project implements a group chat system using Java sockets, demonstrating key concepts in networking, threading, and I/O. It was developed in Visual Studio Code (VS Code).

Core Functionality:
Server: Listens on port 1234 using ServerSocket, accepts client connections, and spawns a ClientHandler thread for each client.
Client: Prompts for a username, connects to the server via Socket, and manages sending/receiving messages. A background thread continuously listens for incoming messages.
ClientHandler: Runs in its own thread, handles one client’s messages, and uses a broadcast mechanism to relay messages to all onnected clients.
Tools & Libraries
Java Networking APIs: ServerSocket, Socket
I/O Classes: BufferedReader, BufferedWriter, etc.
Threads: For concurrent client handling
VS Code: Development and debugging environment

Key Features:
Multi-client support with usernames
Real-time group messaging
Broadcast mechanism for message distribution
Join/leave notifications
Thread-based design for concurrency
Graceful shutdown of sockets and streams

Significance:
The project provides practical experience in Java networking and multithreading, offering insights into how real-world messaging apps (e.g., WhatsApp, Slack) function. It can be extended with features like authentication, private messaging, or GUI support.

Learning Outcomes:

Implementing server-client communication with sockets
Handling multiple clients with threads
Using buffered streams for efficient I/O
Designing interactive console-based apps
Managing resources (closing sockets/streams properly)

OUTPUT:

<img width="1587" height="329" alt="Image" src="https://github.com/user-attachments/assets/1b5a85de-4ec1-4fb8-a86b-89c973260c4f" />

<img width="1584" height="319" alt="Image" src="https://github.com/user-attachments/assets/6ac48a86-f441-458d-8988-592744a8be82" />

<img width="1593" height="319" alt="Image" src="https://github.com/user-attachments/assets/516a39cc-a648-43bb-9a5b-14a0ab8210b7" />

<img width="1589" height="320" alt="Image" src="https://github.com/user-attachments/assets/c7798a6a-3bd8-4daf-b59b-b1b271c12242" />
