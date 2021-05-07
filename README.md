# ITT440_LAB4
Socket programming in C

CHAT PROGRAM

chatServer.c

chatClient.c

WHAT IS IT? A simple program that uses TCP connection and sockets to establish a 2-way text-based communication between Server and Client.

HOW TO USE?

Configure static ip address on both server and client hosts
Compile and run chatServer.c
Compile and run chatClient.c
Input the IP address of the server
The server host has to send a response or type [exit] to cut off the connection
The client host can now reply
The server host can type [exit] or the client host can use [CTRL+C] to close the connection
WHY IS IT NOT WORKING FOR ME? Check the IP addresses on both hosts. For server side not being able to bind socket, simply wait for a few seconds (more details in chatServer.c).
