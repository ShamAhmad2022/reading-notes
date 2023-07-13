# Message Queues
It's really very important for me to know more about Socket.io so I can get a better understanding of Event Driven Applications and to learn new things

## Socket.io Chat Example

1. Explain to a non-technical recruiter what the Chat Example (above) does.
    
    A: it's a chating system where the server can push messages to clients. Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients.

2. What proof of life are we getting on the backend from the above app?

    A: the state of the connection between the clients and the server

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

    A: broadcast


## Rooms

1. What is a room and how might a room be useful?
    
    A: A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients:



2. How do you join a room?

    A: call join to subscribe the socket to a given channel,then use to or in when broadcasting or emitting

3. how do you leave a room?

    A: call leave in the same fashion as join


## Namespaces

1. What is a Namespace and what does it allow you to do?
    
    A: A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection, like a smaller parts of a bigger components

2. Each namespace potentially has its own what? (hint: 3 things)

    A:  event handlers, rooms and middlewares


3. Discuss a possible use case for separate namespaces

    A: for a very simple example, the zoom meeting and the rooms inside each meeting


## Reflection
1. What are your learning goals after reading and reviewing the class README?

    A: to learn more about the subject and to know more about socket.io
    