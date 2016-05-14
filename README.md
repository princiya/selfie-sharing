# selfie-sharing
hack session at jsconfbp, 2016 organised by mozilla hacker lounge

This is a simple app to click selfies and share with friends using web sockets, getUserMedia() and node.js

To run the app do the following:

- node websocket (creates a web socket server)
- node app (creates a node express server)
- Open a browser and run localhost:5000/server/serverCamera.html
- Open a browser and run localhost:5000/client/clientImage.html

This is a client - server architecture

Server runs and captures your selfie

Any client(s) connected can have access to this selfie

This is made possible using web sockets
