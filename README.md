# Multiplexed TCP + UDP broadcast linux chat program

A program I wrote in C in the 3rd semester that allows multiple clients to connect to a chat server using the **select** linux system call via TCP sockets, then any message sent by a client is being broadcasted to all connected clients via UDP.  

The clients contact the server just for registration.
All communication happens directly between the peers (clients) without passing through the server.

Server manages arrival and departure confirmations.

![chat](https://user-images.githubusercontent.com/39191865/159064534-01cd2444-5bb1-42d0-8b20-dde54b6e8540.png)
