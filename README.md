# socket.io-chat
A small demo of socket.io


### What is socket.io? 
Socket.IO is a library that enables instaneous two-way event-based communication between browser and server. It consists of a Node.js server and a Javascript client library for the browser.

### What is Websocket? 
Websocket is an entirely different communication protocol from HTTP, which is strictly unidirectional. Being a bidirectional protocol means that both the client and the server can push messages in both directions independently and without any linking to the previous request. Once a connection is established, the client and server communicate through the SAME TCP connection throughout the entire communication cycle. Whereas in HTTP, a separate connection is needed to be established for separate requests. 

### What are some use cases for Websocket? 
Because it uses a single TCP connection, speed is the key. Websocket is useful for social media platforms and chat services, gaming applications, and anything that relies on real-time data such as stock market or cryptocurrency tickers. 
