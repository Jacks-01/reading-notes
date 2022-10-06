## Reading Notes
## Assignment:

Statement: This topic is important because...
___

### Questions:
___

## Reading

[Socket.io Chat Example](https://socket.io/get-started/chat/)

1.  Explain to a non-technical recruiter what the Chat Example (above) does.
	- this chat example is showing us how to set up a basic socket server and display a realtime flow of data between the server and the front end client.
2.  What proof of life are we getting on the backend from the above app?
	- we are getting rendered html 
3.  Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
	- we would use `socket.broadcast.emit`

[Rooms](https://socket.io/docs/v4/rooms)

1.  What is a room and how might a room be useful?
	- a room is an arbitrary channel that sockets can  join and leave
2.  How do you join a room?
	- `socket.to` or `socket.in`
3.  how do you leave a room?
	- `socket.leave`

[Namespaces](https://socket.io/docs/v4/namespaces/)

1.  What is a Namespace and what does it allow you to do?
	- it is a channel that allows you to split the logic of your app.
2.  Each namespace potentially has its own what? (hint: 3 things)
	- event handlers
	- rooms
	- middlewares
3.  Discuss a possible use case for separate namespaces
	- you may want a namespace specifically for authorized users.
	- multiple namespsaces for each user.



### Things I want to know more about:
___


### Sources (if any):
___
