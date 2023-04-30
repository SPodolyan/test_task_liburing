# Test task (liburing)
Source code for client and server.
LIBURING library is used for semi-synchronous call of kernel functions 

Build instructions
==================
cmake it used to build these examples. Please ensure it is installed on your system. 
Run theis command once you check out this repo and change into its directory:

```
$ chmod +x build.sh && ./build.sh

```

This should place all executables inside of the ``build`` directory from where you can execute them.

Run instructions
==================

1) Open Terminal, navigate to build folder and run server:
	./server

2)  Open Terminal, navigate to build folder and run client
	./client
	
3) Type string in client and press ENTER. In 5 seconds the responce should come from the server
