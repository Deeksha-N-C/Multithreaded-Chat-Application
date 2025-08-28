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


<img width="576" height="130" alt="Image" src="https://github.com/user-attachments/assets/fbf5ae73-4b8b-4214-b675-751ee66832f6" />

<img width="724" height="288" alt="Image" src="https://github.com/user-attachments/assets/a2a47c67-8e2a-4395-a360-6d97944c073f" />

<img width="715" height="233" alt="Image" src="https://github.com/user-attachments/assets/652ddb40-4e2a-422e-bc7a-4be6a46e6a92" />

<img width="727" height="222" alt="Image" src="https://github.com/user-attachments/assets/9ea1eca7-cb4c-4b55-88bd-7a46b8bc7525" />
