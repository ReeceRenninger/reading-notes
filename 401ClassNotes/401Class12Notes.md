# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Socket.io

[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

- A Web Socket is a computer communications protocol which provide communication channels over a TCP(Transmission Control Protocol) connection.
- To allow for compatibility the WebSocket will handshake using HTTP headers to change from the HTTP protocol to the WebSocket Protocol. Once this happens the protocol allows for interaction to occur between the browser and the server.
- Web sockets provide a standardized way for the server to send content to a client without first receiving a REQUEST from that client.

[Socket.io tutorial](https://www.tutorialspoint.com/socket.io/)

- the io.on event handler is a listener to a specified event name which triggers a provided callback function the the matching event is received.
- After doing your initial setup on your server you can run nodemon app.js if you have implemented your http.listen with some type of prompt to be printed once it launches.
- socket.emit() sends a message to all connected clients. This code will notify when a user connects to the server.

[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

- Socket.io is a library that enables real-time and full-duplex communication between clients and web servers.  To do this it uses WebSocket protocol to provide the interface.  WebSocket remains opens all the time so they allow for real time data transfer.
- You would use Socket.IO when you need to full-duplex communication in real-time, it can handle various support levels, gives additional features room support for basic publish infrastructure.
- WebSocket should be used when you do not need to broadcast, dont need fallback options, you need to establish protocol over a TCP connection.

## Videos:

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

- Open System Interconnection what developed to allow for different systems to communicate with each other even if operating with different software systems.  When dealing with file transfers (FTP is used), Web Surfing(HTTP/S), Emails (SMTP), and Virtual Terminals (TELNET). There are multiple layers that allow for OSI to work through all the different types of ways files can be moved around. The session layer helps handle authorization, authentication, and session management. Transport layer works in segmentation, flow control, error control, and connection. Network layer works primarily in pathing due to location and where you are trying to receive or send information.  Data link layer goes into how data is controlled and received from media and access to said media.  The physical layer converts the BITS (Binary Digits) that have been sent through the transport layer, to the network, to the data link layer changing forms as they move along ultimately becoming BITS. These layers are what allow for smooth functioning across the web. 

![Alt text](../imgs/Screenshot%202023-05-25%20225529.png)
[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

- The TCP handshake is how a client and user can communicate with each other.  It establishes a two-way connection between them after the "doors" have been opened on each side.  

## Bookmark

[Socket.io documentation](https://socket.io/docs/)

[Socket.io Server api](https://socket.io/docs/server-api)

[Socket.io Client api](https://socket.io/docs/client-api)

[Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

## Reflection

- Understand the OSI model better. I watched the video twice trying to understand all the different steps and how data is changed and sent etc.  It sounds really cool but also very confusing.  

## Class Notes

## Things I want to know more about
