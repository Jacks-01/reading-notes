## Reading Notes
## Assignment: Socket.io

Statement: This topic is important because...
___

### Questions:
___

## Reading

[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

1.  What is a Web Socket?
	- a communication protocol over a tcp connection.
2.  Describe the Web Socket request/response handshake and what happens once the connection is established.
	- establishes a connection with the client from the web browser
	- uses polling to send real-time data between the two.
3.  Web Sockets provide a standardized way for the server to send content to a client without first receiving a **__**__ from that client.
	- request?

[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

1.  What does the event handler `io.on()` do?
	- establishes a connection to the client
2.  Describe some possible proof of life or proof that the code works as expected
	- use a callback with a console log 
3.  What does socket.emit() do?
	- emits an event to be recieved by a listener

[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

1.  What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
	- websocket is the protocol, or the very basic version and implementation. socket.io is just one implementation of it (npm package);
2.  When would you use Socket.IO?
	- anything that requires real-time communication 
3.  When would you use WebSockets?
	- anything that requires real-time connection.

## Videos

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

1.  What are a couple of key takeaways from this video?

[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

1.  Translate the gist of this video to a non-technical friend



### Things I want to know more about:
___


### Sources (if any):
___
[Socket.io Documentation](https://socket.io/docs/)

[Socket.io Server API](https://socket.io/docs/server-api)

[Socket.io Client API](https://socket.io/docs/client-api)

[Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)