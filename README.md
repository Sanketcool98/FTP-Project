Basic FTP Client/Server:
	ftpclient.c : C source file for the client program
	ftpserver.c : C source file for the server program
	
Server Running Command:
	1) cc ftpserver.c -o server
	2) ./server <listen-port>
	
Client Running Command:
	1) cc ftpclient.c -o client
	2) ./client <server-ip> <server-listen-port> 
	
Other Commands:
	1) ls: list of files in the current directory.
	2) get <filename> : Copies a file from the server to the client.
	3) put <filename> : Copies a file from the client to the server.
	4) quit : Exiting the client program.
