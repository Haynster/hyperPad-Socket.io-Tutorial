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

## Creating the hyperPad Project
>1. Create the new project
>2. Go in Global Behaviours and add 2 Behaviours **Socket.io Client** and **Connect to Socket**
>3. Click on the **Socket.io Client** Behaviour and add the link to the forked repl
>4. Click on **Connect to Socket** and add your *Socket.io Client* behaviour to it

---

Before you continue, You need knowledge on these things:  
`Dictonaries`
`Arrays`
`General Behaviour Knowledge`
