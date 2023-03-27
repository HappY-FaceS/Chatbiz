# ChatBiz :

- Basic real-time chat application using websockets (socket.io)

- Websockets is a protocol that provides full-duplex communication over a single TCP connection. This means that both the client and the server can send and receive messages simultaneously without having to open a new connection for each message. Websockets are commonly used in applications that require real-time communication, such as chat applications or online gaming.

# Establishing a connection: 

- To establish a Websocket connection, the client
sends a HTTP request with a special "Upgrade" header to the server. 

- If the server supports Websockets, it responds with a HTTP response with a status code of "101 Switching Protocols" and a special "Upgrade" header indicating that the connection has been upgraded to a Websocket connection.

- Once the connection is established, the client and server can send and receive messages over the same TCP connection.

# Socket.io :

- Socket.IO is a npm library that enables low-latency, bidirectional and event-based communication between a client and a server.

- socket.on () has been used to consume the event/message .

- socket.emit() has been used to publish the event/message .

# To run on local: 

- `npm install`
- open the `localhost:3000`