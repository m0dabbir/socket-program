# 🔌 TCP/IP Socket Programming in C++

This project demonstrates a basic client-server communication model using TCP sockets in C++. It establishes a two-way data exchange over a network using standard socket APIs.

## 🧠 Objective

To create a reliable communication channel between a client and server using TCP/IP. It helps understand how low-level networking works in real-time applications.

## ⚙️ How It Works

### Server:
- Creates a socket
- Binds it to an IP address and port
- Listens for incoming connections
- Accepts a client and exchanges data

### Client:
- Creates a socket
- Connects to the server using IP and port
- Sends and receives messages

## 🛠️ Technologies Used

- C++  
- TCP/IP Socket API (`<sys/socket.h>`, `<netinet/in.h>`, etc.)
- Linux-based development environment (Ubuntu or similar)

## 📦 Files

- `server.cpp` – Server-side implementation  
- `client.cpp` – Client-side implementation  
- `Makefile` (optional)
