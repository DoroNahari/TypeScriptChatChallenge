# type-script-group-chat
## Description
Creating a group chat room, using TypeScript Node.js & Socket.io
<br/>
<br/>

![Alt text](README_resources/Nodejs_Chat_Demo.png?raw=true "Node.js Chat Demo")


<br/>

## About the Node modules:
**[Express](https://expressjs.com)** - Express is lightweight web application framework for Node.js. For this simple group chat, it is not necessary to use Express, but if you are planning to continue the development, this is nice to have.  

**[Socket.io](https://socket.io)** - Socket.io is the key module in this tutorial which enables the realtime communication between the clients and the server.
for more info and documentation go to [socket.io](https://socket.io).

<br/>

## Credits
**This exercise is based on the example supplied by socket.io:**  
 https://github.com/socketio/chat-example

<br/>

## Prerequisites
in order to develop and run this application the following should be installed: 
 - Node
 - NPM
 - TypeScript
 
I recommend Intellij Idea IDE or VS Code in order to develop and run the application but you can use you own IDE.

 

## Short explanation about the application
this is a Node.js application that uses Express to run HTTP server.
the application built from server side code that runs in the server(Node.js) and client side code that runs in the browser.
(server folder with the server code and client folder with the client code).

the code written in TypeScript and being compiled to JavaScript.
there is a package.json file (NPM) and we can run the following commands: 
 - ```npm install``` - in order to install all the packages the application uses.
 - ```npm run build-project``` - in order to build the JavaScript output code into dist folder and also build and prepare 
 the client JavaScript code to run in the browser.
 - ```npm start``` - in order to run the application.

## Challenge
 currently the application shows the username you entered in the join the chat popup. 
 
 we would like to add the following features

First challenge
 - Show the message being sent in the chat.
 **(Server already implemented, only Client side change needed)**.
 - Show which user has connected/joined to the chat. 
 **(Server already implemented, only Client side change needed)**.
 
 Second challenge
 - Show the user who wrote the message next to the message from first challenge.
 **(both Server and Client side changes needed, UI implementation already include just use it)**.
 - Show which user has disconnected/left from the chat.
 **(both Server and Client side changes needed, UI implementation already include just use it)**.
 
 Third challenge
 - Show the number of users connected to the chat.
 **(both Server and Client side changes needed, UI implementation already include just use it)**.
 
 Fourth challenge
 - Show a list of connected users.
 **(both Server and Client side (including UI - html) changes needed)**.
 - (Optional) Show which user is typing...(and of course when he stopped).
 **(both Server and Client side changes needed)**.