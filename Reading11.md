# Reading 11

## Web Sockets

What is a Web Socket?
A computer comunications protocol, providing full-duplex communication channels over a single TCP connection

Describe the Web Socket request/response handshake and what happens once the connection is established.
The handshake starts with a HTTP request/reponse, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communcation switches to a bidirectional binary protocol which does not comform to the HTTP protocol

Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
request


## Socket.io Tutorial

What does the event handler io.on() do?
Connect,
Message,
Disconnect,
Reconnect,
Ping,
Join and, 
leave

Describe some possible proof of life or proof that the code works as expected


What does socket.emit() do?
It can create custom events


## Socket.io vs Web Sockets

What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
WebSocket is the communitcation Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket stays open all the time, so they allow real-time data transfer.
Socket.IO is a library that enables real-time and full-duplex comminication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into 2 parts; both Websocket vx Socket.io are event-driven libraries

When would you use Socket.IO?


When would you use WebSockets?
If you need a fallback option


## Video

## OSI Model Explained

What are a couple of key takeaways from this video?


## TCP Handshakes Explained

Translate the gist of this video to a non-technical friendgit 