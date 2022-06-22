# hyperPad-Socket.io-Tutorial
Tutorial Level: Intermediate

## Creating the server
>1. Fork [this](https://replit.com/@RobinsonX/Socketio-Server-Template) repl  
>2. Delete line 19 - 21  
>3. Copy this on line 19  
```
socket.on("move", function(input, callback){
  socket.broadcast.emit("move", input);
})

socket.on("chat", function(input, callback){
  socket.broadcast.emit("chat", input);
})
```
>4. Run the server and copy the link  
>5. **And you're done!**  
test [test](www.youtube.com)
