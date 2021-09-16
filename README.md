# TCP-Socket-and-UDP-Socket-File-Transfer-Server
This is a socket programming term project from the course VE489 Computer Networks. In this project, a server based on TCP-socket is created to transfer files to remote clients. A UDP-socket-based selective repeat protocol server is also implemented to transfer files reliably to clients. Duplicate ACK and NACK mechanisms are added to improve the UDP server's transfer efficiency. For more detailed descriptions and requirements, please refer to <i>ProjectDescription.pdf</i>.
## Mininet Installation
To run the servers and the clinets, Mininet must be installed in advance.
* Open up a terminal and install Mininet.
```sudo apt-get install mininet```
* Launch a simple Mininet network using ```sudo mn``` to test if it is working.
* If errors prompt up, try launching again or run ```sudo mn -c``` to cleanup.
* After successfully lauching the Mininet, a network with two hosts (h1 and h2) and one switch (s1) will be created and the Mininet CLI will be opened.
* To test connectivity between h1 and h2 in the Mininet CLI, run ```h1 ping h2```.
* Enter ctrl C to stop ping.
* Enter exit or ctrl D to quit Mininet CLI.
