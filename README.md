# ChatRoom
A program, where you can start server (ChatServer) and anu number of clients under 50, (ChatClient) there you can connect and chat with other clients.
Notes:
@username<blank>message sends a DM to the respective client and only this client. When there is no client with this name known to the server, the sender just receives a corresponding error message by the server.
If the client sends WHOIS, (s)he and only (s)he, receives a list of all currently connected clients and since when they are connected.
If a client sends LOGOUT, the connection of this client is closed and all streams and of both sides are also closed.
If a client sends PINGU, all currently connected clients receive an important fact about penguins (what ever that might be :)).
