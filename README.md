#3313 Lab
The server receives a string from the client, does something to it, and send it back. Transformed sting is not exactly the same as the string transmitted to the server and it is in some way dependent on the string transmitted to server.

The server handles an arbitrary number of clients  at the same time.

The Server terminates gracefully (no core dumps, unhandled exceptions, and so on) by typing something on the server or the client.  All sockets are closed and all threads terminated. When the server terminates, the clients terminate as well (possibly with new input on the client). Demonstrated from the command prompt.

The client asks for the input. It displays received string from the server. The process keeps repeating. There must be some error checking present.

The client connects to the server. It sends data to the server and receives from the server. 

The clients should terminate gracefully when the user enters 'done' (no core dumps, unhandled exceptions, and so on). Demonstrated from the command prompt.






