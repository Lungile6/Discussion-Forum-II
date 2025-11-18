# TCP Client/Server Program

This project implements a simple TCP client and server in C. The server listens for incoming connections, accepts a client, receives a message, and then echoes the message back to the client. The client connects to the server, sends a message, and then receives and prints the echoed message.

## How to Compile

Navigate to the `TCP Client Program` directory in your terminal:

```bash
cd TCP\ Client\ Program/
```

Compile the server and client programs using `gcc`:

```bash
gcc tcp_server.c -o tcp_server
gcc tcp_client.c -o tcp_client
```

## How to Run

First, start the server in one terminal:

```bash
./tcp_server
```

The server will start listening on port 8000.

Then, in another terminal, run the client:

```bash
./tcp_client
```

The client will prompt you to enter a message, send it to the server, and then display the echoed response.
