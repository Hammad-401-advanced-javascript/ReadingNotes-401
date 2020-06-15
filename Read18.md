# Web Sockets

**A communication Protocol which provides bidirectional communication between the Client and the Server over a TCP connection,
WebSocket open all the time so they allow the real-time data transfer.**

## Socket.io
**A library which enables real-time and full duplex communication between the Client and the Web servers. Generally, it is
divided into two parts, each of which use WebSockets, but also provide additional functionality such as broadcasting, 
namespacing, and other means of segmenting connected clients into groups.**

#### Client Side: it is the library that runs inside the browser

#### Server Side: It is the library for Node.js

**In an event driven node app, the entire app is in memory, and (through a common event pool), all
parts of your application can emit and hear events, communicating with each other. However, no outside application
can participate in these events natively. --> With Socket.io, the entire purpose is to have events shared between
‘disconnected’ participants. Through a mediator (server), clients connect, emit events, and respond to events from the server.**

![image](https://www.websocket.org/img/websocket-architecture.jpg)
