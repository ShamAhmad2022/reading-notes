
# Socket.io
It's really very important for me to know more about Socket.io so I can get a better understanding of Event Driven Applications and to learn new things

## Web Sockets

1. What is a Web Socket?
    
    A: WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. 

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

    A: The client and server can exchange data in real-time, They can send messages to each other using WebSocket frames, The connection remains open enabling bi-directional communication,Both the client and server can close the connection if needed

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

    A: requested


## Socket.io Tutorial

1. What does the event handler io.on() do?
    
    A: handle various events that occur on the server side

2. Describe some possible proof of life or proof that the code works as expected

    A: Emit and Receive Events, Room Joining and Leaving, Disconnect Handling, Error Handling, Client-Server Connection

3. What does socket.emit() do?

    A: send a custom event from the client-side to the server-side or from the server-side to a specific client


## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
    
    A: WebSocket is the underlying protocol for real-time bidirectional communication, while Socket.IO is a higher-level library that utilizes WebSocket and provides additional features and cross-platform compatibility, making it easier to implement real-time applications.

2. When would you use Socket.IO?

    A:  real-time communication between the client and server

3. When would you use WebSockets?

    A: required low-level control, high performance, and native support for the WebSocket protocol


## Reflection
1. What are your learning goals after reading and reviewing the class README?

    A: to learn more about the subject and about socket.io