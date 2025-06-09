# MultithreadedChat-java-task3
Java Programming task-3, Multithreaded Chat Application, CodTech solutions 
Internship COMPANY: CODTECH IT SOLUTIONS 
NAME: ATHIRA ARUN 
INTERN ID: CT04DG364 
DOMAIN: JAVA PROGRAMMING
DURATION: 4 WEEKS 
MENTOR: NEELA SANTHOSH

## Overview
This is a simple client-server chat application built in Java using sockets and multithreading.  
The server supports multiple clients simultaneously, and all messages from clients are broadcast to every connected client in real-time.

## Features
- Server handles multiple clients concurrently using threads.
- Clients can join with a username.
- Real-time message broadcasting to all connected clients.
- Clients can exit the chat by typing `exit`.

## Files
- `MultiThreadedChatServer.java` — The server program.
- `ChatClient.java` — The client program.

## How to Run

### Prerequisites
- Java Development Kit (JDK) installed (version 8 or higher).
- Command line or terminal access.

### Steps

1. Open terminal/PowerShell and navigate to the project directory:

   ```bash
   cd "C:\Users\athir\OneDrive\Desktop\Task-3,Java"
2. Compile both java files
   ```bash
   javac MultiThreadedChatServer.java
   javac ChatClient.java
3. Start the server
   ```bash
   java MultiThreadedChatServer
4. Open a new terminal window for each client you want to run.
5. In each client terminal, navigate to the project directory and run the client:
   ```bash
   java ChatClient
6. When prompted, enter your username and start chatting.
7. To exit the chat, type:
   ```bash
   exit
How it Works
  -The server listens on port 12345 for incoming client connections.

  -Each client is handled in a separate thread.

  -When a client sends a message, the server broadcasts it to all other connected clients.

  -When a client disconnects, the server notifies other clients.

# Author
Athira Arun

# OUTPUT
![Image](https://github.com/user-attachments/assets/a7d70c60-974a-4a3f-b30d-2e89cfa49d9b)





