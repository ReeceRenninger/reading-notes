# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Message Queues

[Socket.io Chat Example](https://socket.io/get-started/chat/)

- The chat example above allows users to send messages to each other even when a user is not online.  So if you wanted to send a message for someone to get once they log in, you could use this since the communication lines stay open even if all the other users are offline.
- When running node index.js command in our terminal we should see a prompt saying listening on *: port#Chosen.
- If you want to send a message to everyone EXCEPT  certain emitting socket you would use a BROADCAST flag for emitting from that socket.

```javascript
io.on('connection', (socket) => {
  socket.broadcast.emit('hi');
});
```

[Rooms](https://socket.io/docs/v4/rooms)

- A room is an arbitrary channel that sockets can join and leave. These are only server side, and they can be useful for testing your connections to multiple rooms or sending messages to specific rooms.
- To join a room you would use socket.join('some room').
- To leave a room you would use disconnecting event shown below:

```javascript
io.on("connection", socket => {
  socket.on("disconnecting", () => {
    console.log(socket.rooms); // the Set contains at least the socket ID
  });

  socket.on("disconnect", () => {
    // socket.rooms.size === 0
  });
});
```


[Namespaces](https://socket.io/docs/v4/namespaces/)

- A namespace is a communication channel that allows you to split the logic of your application over a single shared connection "this is also called multiplexing".
- Each namespace has its own event handlers:

```javascript
io.of("/orders").on("connection", (socket) => {
  socket.on("order:list", () => {});
  socket.on("order:create", () => {});
});

io.of("/users").on("connection", (socket) => {
  socket.on("user:list", () => {});
});
```
Rooms:

```javascript
const orderNamespace = io.of("/orders");

orderNamespace.on("connection", (socket) => {
  socket.join("room1");
  orderNamespace.to("room1").emit("hello");
});

const userNamespace = io.of("/users");

userNamespace.on("connection", (socket) => {
  socket.join("room1"); // distinct from the room in the "orders" namespace
  userNamespace.to("room1").emit("holà");
});
```

Middlewares: 

```javascript
const orderNamespace = io.of("/orders");

orderNamespace.use((socket, next) => {
  // ensure the socket has access to the "orders" namespace, and then
  next();
});

const userNamespace = io.of("/users");

userNamespace.use((socket, next) => {
  // ensure the socket has access to the "users" namespace, and then
  next();
});
```

- Possible use cases that were described in the reading were if you wanted to create a special namespace that only authorized users have access to. So a secret chat room of sorts. This would separate the logic related to those users in a separate place from the rest of the application.  

## Bookmark

[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

## Reflection

- I think I would like to build out a complete messaging room front and back end after reading through these sites and reading the README. It would be a big step in understanding how this works so it could be implemented into future apps that would allow users to communicate with each other. 

## Class Notes

## Things I want to know more about
