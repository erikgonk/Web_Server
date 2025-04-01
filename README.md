# WebServer – Build Your Own HTTP Server 🚀

**WebServer** is a simple HTTP server implemented in C++ as part of the 42 curriculum. It simulates the core functionality of a web server by handling HTTP requests, serving static files, and managing connections. This project provides a deep understanding of networking, HTTP protocols, and server-client architecture.

## Features

- ✅ **HTTP Request Handling**  
  - Parses and responds to HTTP **GET**, **POST**, **DELETE** and **OPTIONS** requests.
  
- ✅ **Static File Serving**  
  - Serves **HTML**, **CSS**, **JavaScript**, and image files from the server.
  
- ✅ **HTTP Response Codes**  
  - Handles standard HTTP status codes such as **200 OK**, **404 Not Found**, **500 Internal Server Error**, etc.
  
- ✅ **Basic Authentication**  
  - Implements simple **HTTP authentication** to restrict access to certain resources.
  
- ✅ **Request Logging**  
  - Logs incoming server requests, errors, and actions for troubleshooting and analysis.

- ✅ **Multi-threading**  
  - Allows the server to handle multiple client connections concurrently, improving performance and scalability.
  
- ✅ **Virtual Hosts**  
  - Supports multiple **virtual hosts**, allowing the server to host different domains with distinct configurations.

- ✅ **CGI Support**  
  - Executes dynamic content generation through **CGI** scripts, enabling server-side processing.

## Technologies Used

- 💻 **Language:** C++  
- 🌐 **Protocols:** HTTP/1.1, TCP/IP  
- ⚡ **Concurrency:** Multi-threading
- 🧑‍💻 **Additional Technologies:** CGI, Virtual Hosts, File System Management

1. Clone the repository:
   ```bash
   git clone https://github.com/erikgonk/Web_Server.git && cd Web_Server

2. Execute it:
   ```bash
   make r
   
3. Make Request:

Open another terminal and run:
   ```bash
   firefox "http://localhost:8080"
