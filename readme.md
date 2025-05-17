demonstrates the evolution of Java socket server implementations.

## Structure
- `Client.java` - Socket client implementations
- `Server.java` - Server implementations with different threading models

## Implementation Progression
1. **Single-Threaded Server**: Basic implementation that handles one client at a time, demonstrating core socket communication but limiting scalability.

2. **Multi-Threaded Server**: Creates a new thread for each client connection, allowing multiple clients to connect simultaneously but potentially consuming excessive resources with many connections.

3. **Thread-Pool Server**: Uses a fixed thread pool for efficient client handling, providing better resource management and scalability for production environments.

## Purpose
This project was created to understand the fundamental mechanics of socket programming in Java and explore how different threading models address scalability challenges. The progression illustrates the trade-offs between implementation simplicity and application performance as client load increases.
